
<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const testimonials = [
  {
    name: 'Alexandre M.',
    role: 'Client HOMME SAGE',
    image:
      'https://images.unsplash.com/photo-1500648767791-00dcc994a43e?auto=format&fit=crop&w=900&q=85',
    text:
      "Une expérience exceptionnelle du début à la fin. L'écoute, les conseils et surtout la précision de la coupe m'ont vraiment marqué.",
  },
  {
    name: 'Thomas N.',
    role: 'Client HOMME SAGE',
    image:
      'https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=900&q=85',
    text:
      "Je voulais une tenue élégante, sobre et parfaitement adaptée. Le résultat est exactement ce que j'avais en tête.",
  },
  {
    name: 'William K.',
    role: 'Client HOMME SAGE',
    image:
      'https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?auto=format&fit=crop&w=900&q=85',
    text:
      "La différence se trouve dans les détails. Les finitions, la coupe et les recommandations ont complètement changé mon expérience.",
  },
]

const current = ref(0)
let interval = null

const next = () => {
  current.value = (current.value + 1) % testimonials.length
}

const previous = () => {
  current.value =
    (current.value - 1 + testimonials.length) % testimonials.length
}

const goTo = (index) => {
  current.value = index
}

onMounted(() => {
  interval = setInterval(next, 6000)
})

onUnmounted(() => {
  clearInterval(interval)
})
</script>

<template>
  <section
    id="testimonials"
    class="relative overflow-hidden bg-[#0b0b0b] py-24 sm:py-32"
  >
    <!-- subtle background -->
    <div
      class="pointer-events-none absolute -left-40 top-20 h-96 w-96
             rounded-full bg-[#c9a96e]/5 blur-3xl"
    ></div>

    <div
      class="pointer-events-none absolute -right-40 bottom-20 h-96 w-96
             rounded-full bg-[#c9a96e]/5 blur-3xl"
    ></div>

    <div class="relative mx-auto max-w-7xl px-6 lg:px-8">

      <!-- HEADER -->
      <div class="grid gap-12 lg:grid-cols-12 lg:items-end">

        <div class="lg:col-span-8">
          <div class="mb-6 flex items-center gap-4">
            <span class="h-px w-12 bg-[#c9a96e]"></span>

            <span
              class="text-[10px] font-medium uppercase
                     tracking-[0.35em] text-[#c9a96e]"
            >
              L'expérience HOMME SAGE
            </span>
          </div>

          <h2
            class="max-w-4xl text-4xl font-light leading-[1.05]
                   tracking-tight text-white sm:text-5xl lg:text-7xl"
          >
            Ils portent
            <span class="font-serif italic text-[#c9a96e]">
              HOMME SAGE.
            </span>
          </h2>
        </div>

        <!-- GOOGLE RATING -->
        <div class="lg:col-span-4 lg:justify-self-end">

          <div
            class="border border-white/10 bg-white/[0.02]
                   px-7 py-6 backdrop-blur-sm"
          >

            <div class="flex items-start justify-between gap-8">

              <div>
                <p
                  class="text-[10px] uppercase
                         tracking-[0.3em] text-white/40"
                >
                  Avis clients
                </p>

                <div class="mt-3 flex items-end gap-3">
                  <span
                    class="text-5xl font-light leading-none text-white"
                  >
                    4.9
                  </span>

                  <span
                    class="mb-1 text-xs text-white/40"
                  >
                    / 5
                  </span>
                </div>
              </div>

              <!-- Google -->
              <div class="text-right">
                <div class="text-lg font-semibold text-white">
                  Google
                </div>

                <div
                  class="mt-2 flex gap-1 text-[#c9a96e]"
                  aria-label="5 étoiles"
                >
                  <span>★</span>
                  <span>★</span>
                  <span>★</span>
                  <span>★</span>
                  <span>★</span>
                </div>
              </div>

            </div>

            <div class="mt-5 h-px bg-white/10"></div>

            <p class="mt-4 text-xs leading-6 text-white/40">
              Une réputation construite sur la qualité,
              l'écoute et le souci du détail.
            </p>

          </div>

        </div>

      </div>


      <!-- CAROUSEL -->
      <div class="mt-20">

        <div
          class="grid overflow-hidden border border-white/10
                 lg:grid-cols-2"
        >

          <!-- IMAGE -->
          <div class="relative min-h-[460px] overflow-hidden sm:min-h-[560px]">

            <Transition
              name="fade"
              mode="out-in"
            >
              <img
                :key="testimonials[current].image"
                :src="testimonials[current].image"
                :alt="`Portrait de ${testimonials[current].name}`"
                class="absolute inset-0 h-full w-full object-cover"
              />
            </Transition>

            <!-- image overlay -->
            <div
              class="absolute inset-0 bg-gradient-to-t
                     from-black/70 via-black/10 to-transparent"
            ></div>

            <!-- client number -->
            <div class="absolute bottom-7 left-7 sm:bottom-10 sm:left-10">

              <span
                class="text-[10px] uppercase tracking-[0.3em]
                       text-white/50"
              >
                Client
              </span>

              <div class="mt-2 flex items-center gap-4">

                <span
                  class="text-4xl font-light text-white"
                >
                  {{ String(current + 1).padStart(2, '0') }}
                </span>

                <span class="h-px w-10 bg-[#c9a96e]"></span>

                <span
                  class="text-xs tracking-[0.15em] text-white/50"
                >
                  03
                </span>

              </div>

            </div>

          </div>


          <!-- TESTIMONIAL CONTENT -->
          <div
            class="flex min-h-[460px] flex-col justify-between
                   bg-[#101010] p-8 sm:min-h-[560px]
                   sm:p-12 lg:p-16"
          >

            <div>

              <!-- quote -->
              <div
                class="font-serif text-7xl leading-none
                       text-[#c9a96e]/40"
              >
                “
              </div>

              <Transition
                name="slide"
                mode="out-in"
              >
                <blockquote
                  :key="current"
                  class="mt-8 max-w-xl text-2xl font-light
                         leading-relaxed text-white sm:text-3xl"
                >
                  {{ testimonials[current].text }}
                </blockquote>
              </Transition>

            </div>


            <!-- CLIENT -->
            <div>

              <div class="mb-10 h-px bg-white/10"></div>

              <div class="flex items-end justify-between gap-6">

                <Transition
                  name="fade"
                  mode="out-in"
                >
                  <div :key="current">

                    <p
                      class="text-sm font-medium
                             tracking-wide text-white"
                    >
                      {{ testimonials[current].name }}
                    </p>

                    <p
                      class="mt-2 text-[10px] uppercase
                             tracking-[0.25em] text-white/35"
                    >
                      {{ testimonials[current].role }}
                    </p>

                  </div>
                </Transition>


                <!-- ARROWS -->
                <div class="flex gap-2">

                  <button
                    type="button"
                    @click="previous"
                    aria-label="Témoignage précédent"
                    class="flex h-11 w-11 items-center justify-center
                           border border-white/15 text-white/60
                           transition duration-300
                           hover:border-[#c9a96e]
                           hover:text-[#c9a96e]"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="1.5"
                      stroke="currentColor"
                      class="h-4 w-4"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M10.5 19.5 3 12m0 0 7.5-7.5M3 12h18"
                      />
                    </svg>
                  </button>

                  <button
                    type="button"
                    @click="next"
                    aria-label="Témoignage suivant"
                    class="flex h-11 w-11 items-center justify-center
                           border border-[#c9a96e]
                           text-[#c9a96e]
                           transition duration-300
                           hover:bg-[#c9a96e]
                           hover:text-black"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke-width="1.5"
                      stroke="currentColor"
                      class="h-4 w-4"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"
                      />
                    </svg>
                  </button>

                </div>

              </div>


              <!-- DOTS -->
              <div class="mt-8 flex items-center gap-3">

                <button
                  v-for="(_, index) in testimonials"
                  :key="index"
                  type="button"
                  @click="goTo(index)"
                  :aria-label="`Afficher le témoignage ${index + 1}`"
                  class="h-px transition-all duration-500"
                  :class="
                    current === index
                      ? 'w-12 bg-[#c9a96e]'
                      : 'w-5 bg-white/20 hover:bg-white/40'
                  "
                ></button>

              </div>

            </div>

          </div>

        </div>

      </div>


      <!-- BOTTOM TRUST BAR -->
      <div
        class="mt-12 grid border-y border-white/10
               sm:grid-cols-3"
      >

        <div
          class="border-b border-white/10 px-6 py-7
                 sm:border-b-0 sm:border-r sm:px-8"
        >
          <p
            class="text-[10px] uppercase
                   tracking-[0.25em] text-white/30"
          >
            Savoir-faire
          </p>

          <p class="mt-2 text-sm text-white">
            Confection & personnalisation
          </p>
        </div>


        <div
          class="border-b border-white/10 px-6 py-7
                 sm:border-b-0 sm:border-r sm:px-8"
        >
          <p
            class="text-[10px] uppercase
                   tracking-[0.25em] text-white/30"
          >
            Engagement
          </p>

          <p class="mt-2 text-sm text-white">
            Chaque détail compte
          </p>
        </div>


        <div class="px-6 py-7 sm:px-8">
          <p
            class="text-[10px] uppercase
                   tracking-[0.25em] text-white/30"
          >
            Rendez-vous
          </p>

          <a
            href="#contact"
            class="mt-2 inline-flex items-center gap-2
                   text-sm text-[#c9a96e]
                   transition hover:text-white"
          >
            Créer votre tenue

            <span>→</span>
          </a>
        </div>

      </div>

    </div>
  </section>
</template>

<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}

.slide-enter-active,
.slide-leave-active {
  transition:
    opacity 0.4s ease,
    transform 0.4s ease;
}

.slide-enter-from {
  opacity: 0;
  transform: translateX(20px);
}

.slide-leave-to {
  opacity: 0;
  transform: translateX(-20px);
}
</style>
