<template>
  <section
    id="accueil"
    class="relative flex min-h-screen items-center overflow-hidden"
  >
    <!-- IMAGE DE FOND -->
    <div
      class="absolute inset-0 bg-cover bg-center"
      style="
        background-image:
          linear-gradient(
            to right,
            rgba(11, 11, 11, 0.98) 0%,
            rgba(11, 11, 11, 0.82) 45%,
            rgba(11, 11, 11, 0.35) 100%
          ),
          url('https://images.unsplash.com/photo-1551488831-00ddcb6c6bd3?auto=format&fit=crop&w=2000&q=85');
      "
    ></div>

    <!-- LÉGER VOILE -->
    <div class="absolute inset-0 bg-black/20"></div>

    <!-- CONTENU -->
    <div
      class="relative z-10 mx-auto w-full max-w-7xl px-6 pb-20 pt-32 lg:px-8"
    >
      <div class="max-w-3xl">

        <!-- PETIT LABEL -->
        <div class="mb-7 flex items-center gap-4">
          <span class="h-px w-12 bg-[#c9a96e]"></span>

          <span
            class="text-xs font-medium uppercase tracking-[0.35em] text-[#c9a96e]"
          >
            Tailleur à Yaoundé
          </span>
        </div>

        <!-- TITRE -->
        <h1
          class="text-5xl font-semibold leading-[1.05] tracking-tight
                 text-white sm:text-6xl lg:text-8xl"
        >
          L'élégance
          <span class="block font-light italic text-[#c9a96e]">
            commence ici.
          </span>
        </h1>

        <!-- DESCRIPTION -->
        <p
          class="mt-8 max-w-xl text-base leading-7 text-white/65
                 sm:text-lg"
        >
          Des créations pensées pour vous. Confection sur mesure,
          retouches et tenues personnalisées réalisées avec précision
          et passion.
        </p>

        <!-- BOUTONS -->
        <div class="mt-10 flex flex-col gap-4 sm:flex-row">

          <a
            href="#contact"
            class="inline-flex items-center justify-center gap-3
                   bg-[#c9a96e] px-7 py-4 text-sm font-semibold
                   text-black transition duration-300
                   hover:bg-[#e0c48d]"
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

          <a
            href="#galerie"
            class="inline-flex items-center justify-center
                   border border-white/30 px-7 py-4 text-sm
                   font-medium text-white transition duration-300
                   hover:border-[#c9a96e] hover:text-[#c9a96e]"
          >
            Voir nos réalisations
          </a>

        </div>

        <!-- INFORMATIONS -->
        <div
          class="mt-16 flex flex-wrap gap-x-10 gap-y-5
                 border-t border-white/10 pt-7"
        >

          <div>
            <p class="text-xs uppercase tracking-widest text-white/40">
              Spécialité
            </p>

            <p class="mt-1 text-sm text-white/80">
              Confection sur mesure
            </p>
          </div>

          <div>
            <p class="text-xs uppercase tracking-widest text-white/40">
              Localisation
            </p>

            <p class="mt-1 text-sm text-white/80">
              Yaoundé, Cameroun
            </p>
          </div>

          <div>
            <p class="text-xs uppercase tracking-widest text-white/40">
              Expérience
            </p>

            <p class="mt-1 text-sm text-white/80">
              Travail personnalisé
            </p>
          </div>

        </div>
      </div>
    </div>

    <!-- INDICATEUR SCROLL -->
    <div
      class="absolute bottom-8 right-8 hidden items-center gap-4
             lg:flex"
    >
      <span
        class="text-[10px] uppercase tracking-[0.3em] text-white/40"
      >
        Découvrir
      </span>

      <span class="h-12 w-px bg-[#c9a96e]/60"></span>
    </div>

  </section>
</template>