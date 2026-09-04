```vue
<template>
  <section
    id="gallery"
    class="relative overflow-hidden bg-[#0b0b0b] py-24 sm:py-32"
  >
    <div class="mx-auto max-w-7xl px-6 lg:px-8">

      <!-- =========================
           EN-TÊTE
      ========================== -->
      <div
        class="flex flex-col justify-between gap-8 lg:flex-row lg:items-end"
      >
        <div class="max-w-3xl">

          <div class="mb-5 flex items-center gap-4">
            <span class="h-px w-10 bg-[#c9a96e]"></span>

            <span
              class="text-xs uppercase tracking-[0.3em] text-[#c9a96e]"
            >
              Nos réalisations
            </span>
          </div>

          <h2
            class="text-4xl font-semibold leading-tight tracking-tight
                   text-white sm:text-5xl lg:text-6xl"
          >
            L'élégance dans
            <span class="font-light italic text-[#c9a96e]">
              chaque détail.
            </span>
          </h2>

          <p
            class="mt-7 max-w-2xl text-base leading-8 text-white/55 sm:text-lg"
          >
            Découvrez quelques-unes de nos créations, pensées et réalisées
            avec soin pour révéler votre personnalité et votre style.
          </p>

        </div>

        <div class="hidden lg:block">
          <span
            class="text-xs uppercase tracking-[0.25em] text-white/30"
          >
            Collection / 01—06
          </span>
        </div>
      </div>


      <!-- =========================
           GALERIE
      ========================== -->
      <div
        class="mt-16 grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-12"
      >

        <!-- =========================
             IMAGE 01 — GRANDE
        ========================== -->
        <article
          class="group relative overflow-hidden bg-[#111111]
                 md:col-span-1 lg:col-span-7 lg:row-span-2"
        >
          <div class="aspect-[4/5] h-full overflow-hidden">

            <img
              src="https://images.pexels.com/photos/6765069/pexels-photo-6765069.jpeg?auto=compress&cs=tinysrgb&w=1600"
              alt="Création sur mesure HOMME SAGE"
              class="h-full w-full object-cover transition duration-700
                     ease-out group-hover:scale-105"
            />

            <div
              class="absolute inset-0 bg-gradient-to-t
                     from-black/80 via-black/10 to-transparent"
            ></div>

          </div>

          <div class="absolute inset-x-0 bottom-0 p-7 sm:p-9">

            <span
              class="text-[10px] uppercase tracking-[0.3em] text-[#c9a96e]"
            >
              01 — Sur mesure
            </span>

            <h3
              class="mt-3 text-2xl font-medium text-white sm:text-3xl"
            >
              Lignes intemporelles
            </h3>

            <div
              class="mt-5 h-px w-10 bg-[#c9a96e]
                     transition-all duration-500
                     group-hover:w-20"
            ></div>

          </div>
        </article>


        <!-- =========================
             IMAGE 02
        ========================== -->
        <article
          class="group relative overflow-hidden bg-[#111111]
                 lg:col-span-5"
        >

          <div class="aspect-[4/3] overflow-hidden">

            <img
              src="https://images.pexels.com/photos/6765068/pexels-photo-6765068.jpeg?auto=compress&cs=tinysrgb&w=1400"
              alt="Atelier de confection masculine"
              class="h-full w-full object-cover transition duration-700
                     ease-out group-hover:scale-105"
            />

            <div
              class="absolute inset-0 bg-black/20
                     transition duration-500
                     group-hover:bg-black/5"
            ></div>

          </div>

          <div
            class="absolute left-6 top-6 opacity-0
                   transition duration-500
                   group-hover:opacity-100"
          >
            <span
              class="text-[10px] uppercase tracking-[0.3em] text-white"
            >
              02 — Savoir-faire
            </span>
          </div>

        </article>


        <!-- =========================
             IMAGE 03
        ========================== -->
        <article
          class="group relative overflow-hidden bg-[#111111]
                 lg:col-span-5"
        >

          <div class="aspect-[4/3] overflow-hidden">

            <img
              src="https://images.pexels.com/photos/6765071/pexels-photo-6765071.jpeg?auto=compress&cs=tinysrgb&w=1400"
              alt="Prise de mesures pour une tenue sur mesure"
              class="h-full w-full object-cover transition duration-700
                     ease-out group-hover:scale-105"
            />

            <div
              class="absolute inset-0 bg-black/20
                     transition duration-500
                     group-hover:bg-black/5"
            ></div>

          </div>

          <div
            class="absolute left-6 top-6 opacity-0
                   transition duration-500
                   group-hover:opacity-100"
          >
            <span
              class="text-[10px] uppercase tracking-[0.3em] text-white"
            >
              03 — Personnalisation
            </span>
          </div>

        </article>


        <!-- =========================
             IMAGE 04
        ========================== -->
        <article
          class="group relative overflow-hidden bg-[#111111]
                 lg:col-span-4"
        >

          <div class="aspect-[3/4] overflow-hidden">

            <img
              src="https://images.pexels.com/photos/6765639/pexels-photo-6765639.jpeg?auto=compress&cs=tinysrgb&w=1200"
              alt="Costumes masculins dans un atelier"
              class="h-full w-full object-cover transition duration-700
                     ease-out group-hover:scale-105"
            />

            <div
              class="absolute inset-0 bg-gradient-to-t
                     from-black/70 to-transparent opacity-70"
            ></div>

          </div>

          <div class="absolute inset-x-0 bottom-0 p-6">

            <span
              class="text-[10px] uppercase tracking-[0.3em] text-[#c9a96e]"
            >
              04 — Élégance
            </span>

            <h3
              class="mt-2 text-xl font-medium text-white"
            >
              Le goût du détail
            </h3>

          </div>

        </article>


        <!-- =========================
             IMAGE 05
        ========================== -->
        <article
          class="group relative overflow-hidden bg-[#111111]
                 lg:col-span-4"
        >

          <div class="aspect-[3/4] overflow-hidden">

            <img
              src="https://images.unsplash.com/photo-1585488439465-7f4e5c1e5f18?auto=format&fit=crop&w=1200&q=85"
              alt="Style masculin élégant"
              class="h-full w-full object-cover transition duration-700
                     ease-out group-hover:scale-105"
            />

            <div
              class="absolute inset-0 bg-gradient-to-t
                     from-black/70 to-transparent opacity-70"
            ></div>

          </div>

          <div class="absolute inset-x-0 bottom-0 p-6">

            <span
              class="text-[10px] uppercase tracking-[0.3em] text-[#c9a96e]"
            >
              05 — Style
            </span>

            <h3
              class="mt-2 text-xl font-medium text-white"
            >
              Une signature personnelle
            </h3>

          </div>

        </article>


        <!-- =========================
             IMAGE 06
        ========================== -->
        <article
          class="group relative overflow-hidden bg-[#111111]
                 lg:col-span-4"
        >

          <div class="aspect-[3/4] overflow-hidden">

            <img
              src="https://images.unsplash.com/photo-1617127365659-c47fa864d8bc?auto=format&fit=crop&w=1200&q=85"
              alt="Homme en costume élégant"
              class="h-full w-full object-cover transition duration-700
                     ease-out group-hover:scale-105"
            />

            <div
              class="absolute inset-0 bg-gradient-to-t
                     from-black/70 to-transparent opacity-70"
            ></div>

          </div>

          <div class="absolute inset-x-0 bottom-0 p-6">

            <span
              class="text-[10px] uppercase tracking-[0.3em] text-[#c9a96e]"
            >
              06 — Création
            </span>

            <h3
              class="mt-2 text-xl font-medium text-white"
            >
              Pensé pour vous
            </h3>

          </div>

        </article>

      </div>


      <!-- =========================
           CTA
      ========================== -->
      <div
        class="mt-16 flex flex-col items-start justify-between gap-8
               border-t border-white/10 pt-10
               sm:flex-row sm:items-center"
      >

        <div>

          <p class="text-xl font-medium text-white">
            Une idée de création ?
          </p>

          <p class="mt-2 text-sm text-white/40">
            Donnez vie à votre vision avec HOMME SAGE.
          </p>

        </div>


        <a
          href="#contact"
          class="inline-flex items-center gap-3
                 border border-[#c9a96e]
                 px-7 py-4
                 text-xs font-medium uppercase tracking-[0.2em]
                 text-[#c9a96e]
                 transition duration-300
                 hover:bg-[#c9a96e]
                 hover:text-black"
        >

          Discuter de votre projet

          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="h-5 w-5"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"
            />
          </svg>

        </a>

      </div>

    </div>
  </section>
</template>

