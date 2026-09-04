```vue
<template>
  <section
    id="services"
    class="relative overflow-hidden bg-[#0b0b0b] py-24 sm:py-32"
  >
    <div class="mx-auto max-w-7xl px-6 lg:px-8">

      <!-- EN-TÊTE -->
      <div class="max-w-3xl">
        <div class="mb-5 flex items-center gap-4">
          <span class="h-px w-10 bg-[#c9a96e]"></span>

          <span
            class="text-xs uppercase tracking-[0.3em] text-[#c9a96e]"
          >
            Nos prestations
          </span>
        </div>

        <h2
          class="text-4xl font-semibold leading-tight tracking-tight
                 text-white sm:text-5xl lg:text-6xl"
        >
          Des vêtements pensés
          <span class="font-light italic text-[#c9a96e]">
            pour vous.
          </span>
        </h2>

        <p
          class="mt-7 max-w-2xl text-base leading-8 text-white/55
                 sm:text-lg"
        >
          De la conception aux dernières finitions, HOMME SAGE vous
          accompagne pour créer des tenues élégantes, uniques et
          adaptées à votre style.
        </p>
      </div>

      <!-- CARTES SERVICES -->
      <div class="mt-16 grid gap-px bg-white/10 md:grid-cols-2 lg:grid-cols-3">

        <!-- SERVICE 01 -->
        <article
          class="group relative bg-[#0b0b0b] p-8 transition duration-500
                 hover:bg-[#111111] sm:p-10"
        >
          <div class="flex items-start justify-between">
            <span
              class="text-sm font-medium tracking-[0.2em] text-[#c9a96e]"
            >
              01
            </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1"
              stroke="currentColor"
              class="h-7 w-7 text-white/30 transition duration-500
                     group-hover:rotate-45 group-hover:text-[#c9a96e]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M7 17 17 7m0 0H7m10 0v10"
              />
            </svg>
          </div>

          <h3
            class="mt-16 text-2xl font-semibold text-white
                   sm:text-3xl"
          >
            Confection
            <span class="font-light italic text-[#c9a96e]">
              sur mesure
            </span>
          </h3>

          <p class="mt-5 text-sm leading-7 text-white/50">
            Une tenue créée selon vos mesures, vos préférences et
            l'occasion pour laquelle vous souhaitez la porter.
          </p>

          <div class="mt-8 h-px w-12 bg-[#c9a96e] transition-all duration-500
                      group-hover:w-20"></div>
        </article>

        <!-- SERVICE 02 -->
        <article
          class="group relative bg-[#0b0b0b] p-8 transition duration-500
                 hover:bg-[#111111] sm:p-10"
        >
          <div class="flex items-start justify-between">
            <span
              class="text-sm font-medium tracking-[0.2em] text-[#c9a96e]"
            >
              02
            </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1"
              stroke="currentColor"
              class="h-7 w-7 text-white/30 transition duration-500
                     group-hover:rotate-45 group-hover:text-[#c9a96e]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M7 17 17 7m0 0H7m10 0v10"
              />
            </svg>
          </div>

          <h3
            class="mt-16 text-2xl font-semibold text-white
                   sm:text-3xl"
          >
            Retouches
            <span class="font-light italic text-[#c9a96e]">
              & ajustements
            </span>
          </h3>

          <p class="mt-5 text-sm leading-7 text-white/50">
            Nous ajustons vos vêtements avec précision pour améliorer
            leur coupe, leur confort et leur rendu.
          </p>

          <div class="mt-8 h-px w-12 bg-[#c9a96e] transition-all duration-500
                      group-hover:w-20"></div>
        </article>

        <!-- SERVICE 03 -->
        <article
          class="group relative bg-[#0b0b0b] p-8 transition duration-500
                 hover:bg-[#111111] sm:p-10"
        >
          <div class="flex items-start justify-between">
            <span
              class="text-sm font-medium tracking-[0.2em] text-[#c9a96e]"
            >
              03
            </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1"
              stroke="currentColor"
              class="h-7 w-7 text-white/30 transition duration-500
                     group-hover:rotate-45 group-hover:text-[#c9a96e]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M7 17 17 7m0 0H7m10 0v10"
              />
            </svg>
          </div>

          <h3
            class="mt-16 text-2xl font-semibold text-white
                   sm:text-3xl"
          >
            Tenues
            <span class="font-light italic text-[#c9a96e]">
              personnalisées
            </span>
          </h3>

          <p class="mt-5 text-sm leading-7 text-white/50">
            Une création adaptée à votre personnalité, votre style
            et à l'image que vous souhaitez transmettre.
          </p>

          <div class="mt-8 h-px w-12 bg-[#c9a96e] transition-all duration-500
                      group-hover:w-20"></div>
        </article>

        <!-- SERVICE 04 -->
        <article
          class="group relative bg-[#0b0b0b] p-8 transition duration-500
                 hover:bg-[#111111] sm:p-10"
        >
          <div class="flex items-start justify-between">
            <span
              class="text-sm font-medium tracking-[0.2em] text-[#c9a96e]"
            >
              04
            </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1"
              stroke="currentColor"
              class="h-7 w-7 text-white/30 transition duration-500
                     group-hover:rotate-45 group-hover:text-[#c9a96e]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M7 17 17 7m0 0H7m10 0v10"
              />
            </svg>
          </div>

          <h3
            class="mt-16 text-2xl font-semibold text-white
                   sm:text-3xl"
          >
            Conseil
            <span class="font-light italic text-[#c9a96e]">
              & style
            </span>
          </h3>

          <p class="mt-5 text-sm leading-7 text-white/50">
            Nous vous aidons à choisir les matières, les coupes et
            les détails qui correspondent à votre projet.
          </p>

          <div class="mt-8 h-px w-12 bg-[#c9a96e] transition-all duration-500
                      group-hover:w-20"></div>
        </article>

        <!-- SERVICE 05 -->
        <article
          class="group relative bg-[#0b0b0b] p-8 transition duration-500
                 hover:bg-[#111111] sm:p-10"
        >
          <div class="flex items-start justify-between">
            <span
              class="text-sm font-medium tracking-[0.2em] text-[#c9a96e]"
            >
              05
            </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1"
              stroke="currentColor"
              class="h-7 w-7 text-white/30 transition duration-500
                     group-hover:rotate-45 group-hover:text-[#c9a96e]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M7 17 17 7m0 0H7m10 0v10"
              />
            </svg>
          </div>

          <h3
            class="mt-16 text-2xl font-semibold text-white
                   sm:text-3xl"
          >
            Tenues
            <span class="font-light italic text-[#c9a96e]">
              événementielles
            </span>
          </h3>

          <p class="mt-5 text-sm leading-7 text-white/50">
            Mariages, cérémonies, événements professionnels ou
            occasions spéciales : une tenue pensée pour marquer
            l'instant.
          </p>

          <div class="mt-8 h-px w-12 bg-[#c9a96e] transition-all duration-500
                      group-hover:w-20"></div>
        </article>

        <!-- SERVICE 06 -->
        <article
          class="group relative bg-[#0b0b0b] p-8 transition duration-500
                 hover:bg-[#111111] sm:p-10"
        >
          <div class="flex items-start justify-between">
            <span
              class="text-sm font-medium tracking-[0.2em] text-[#c9a96e]"
            >
              06
            </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1"
              stroke="currentColor"
              class="h-7 w-7 text-white/30 transition duration-500
                     group-hover:rotate-45 group-hover:text-[#c9a96e]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M7 17 17 7m0 0H7m10 0v10"
              />
            </svg>
          </div>

          <h3
            class="mt-16 text-2xl font-semibold text-white
                   sm:text-3xl"
          >
            Création
            <span class="font-light italic text-[#c9a96e]">
              unique
            </span>
          </h3>

          <p class="mt-5 text-sm leading-7 text-white/50">
            Une idée particulière ? Nous transformons votre vision
            en une pièce qui vous ressemble.
          </p>

          <div class="mt-8 h-px w-12 bg-[#c9a96e] transition-all duration-500
                      group-hover:w-20"></div>
        </article>

      </div>

      <!-- CTA -->
      <div
        class="mt-16 flex flex-col items-start justify-between gap-8
               border-t border-white/10 pt-10 sm:flex-row sm:items-center"
      >
        <div>
          <p class="text-xl font-medium text-white">
            Vous avez un projet en tête ?
          </p>

          <p class="mt-2 text-sm text-white/40">
            Parlons de votre prochaine tenue.
          </p>
        </div>

        <a
          href="#contact"
          class="inline-flex items-center gap-3 border border-[#c9a96e]
                 px-7 py-4 text-xs font-medium uppercase tracking-[0.2em]
                 text-[#c9a96e] transition duration-300
                 hover:bg-[#c9a96e] hover:text-black"
        >
          Prendre rendez-vous

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
```
