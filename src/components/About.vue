<template>
  <section
    id="apropos"
    class="relative overflow-hidden bg-[#0b0b0b] py-24 sm:py-32"
  >
    <div class="mx-auto max-w-7xl px-6 lg:px-8">

      <!-- EN-TÊTE -->
      <div class="grid gap-10 lg:grid-cols-[0.8fr_1.2fr] lg:items-end">

        <div>
          <div class="mb-5 flex items-center gap-4">
            <span class="h-px w-10 bg-[#c9a96e]"></span>

            <span
              class="text-xs uppercase tracking-[0.3em] text-[#c9a96e]"
            >
              Notre savoir-faire
            </span>
          </div>

          <h2
            class="max-w-xl text-4xl font-semibold leading-tight
                   tracking-tight text-white sm:text-5xl lg:text-6xl"
          >
            L'art de créer
            <span class="font-light italic text-[#c9a96e]">
              pour vous.
            </span>
          </h2>
        </div>

        <p
          class="max-w-2xl text-base leading-8 text-white/55
                 lg:justify-self-end lg:text-lg"
        >
          Chez <strong class="font-medium text-white">HOMME SAGE</strong>,
          chaque tenue est pensée pour révéler votre personnalité.
          Nous accordons une attention particulière aux détails,
          aux finitions et à la précision de chaque confection.
        </p>

      </div>

      <!-- CONTENU PRINCIPAL -->
      <div class="mt-20 grid gap-8 lg:grid-cols-2">

        <!-- BLOC IMAGE -->
        <div
          class="group relative min-h-[480px] overflow-hidden
                 bg-[#151515]"
        >
          <img
            src="https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=1200&q=85"
            alt="Confection sur mesure"
            class="absolute inset-0 h-full w-full object-cover
                   grayscale transition duration-700
                   group-hover:scale-105 group-hover:grayscale-0"
          />

          <!-- OVERLAY -->
          <div
            class="absolute inset-0 bg-gradient-to-t
                   from-black/80 via-black/10 to-transparent"
          ></div>

          <!-- TEXTE SUR IMAGE -->
          <div class="absolute bottom-0 left-0 p-8 sm:p-10">
            <p
              class="text-xs uppercase tracking-[0.3em]
                     text-[#c9a96e]"
            >
              HOMME SAGE
            </p>

            <p
              class="mt-3 max-w-sm text-2xl font-light
                     leading-tight text-white"
            >
              Une tenue qui vous ressemble,
              jusque dans les moindres détails.
            </p>
          </div>

          <!-- CADRE -->
          <div
            class="pointer-events-none absolute inset-5
                   border border-white/15"
          ></div>
        </div>

        <!-- TEXTE -->
        <div class="flex flex-col justify-center lg:pl-12">

          <span
            class="text-7xl font-semibold leading-none
                   text-white/5 sm:text-8xl"
          >
            01
          </span>

          <h3
            class="mt-2 text-3xl font-semibold text-white
                   sm:text-4xl"
          >
            Plus qu'un vêtement,
            <span class="font-light italic text-[#c9a96e]">
              une identité.
            </span>
          </h3>

          <p
            class="mt-7 text-base leading-8 text-white/55"
          >
            Notre approche repose sur une idée simple :
            une belle tenue doit avant tout être faite pour
            la personne qui la porte.
          </p>

          <p
            class="mt-5 text-base leading-8 text-white/55"
          >
            Du choix du tissu aux dernières finitions, nous
            travaillons chaque détail avec soin afin de proposer
            des pièces élégantes, confortables et adaptées à
            votre style.
          </p>

          <!-- POINTS FORTS -->
          <div class="mt-10 grid gap-5 sm:grid-cols-2">

            <div class="border-l border-[#c9a96e] pl-5">
              <h4 class="text-sm font-semibold text-white">
                Sur mesure
              </h4>

              <p class="mt-2 text-sm leading-6 text-white/45">
                Des créations adaptées à votre silhouette
                et à vos envies.
              </p>
            </div>

            <div class="border-l border-[#c9a96e] pl-5">
              <h4 class="text-sm font-semibold text-white">
                Finitions soignées
              </h4>

              <p class="mt-2 text-sm leading-6 text-white/45">
                Une attention particulière portée à chaque détail.
              </p>
            </div>

            <div class="border-l border-[#c9a96e] pl-5">
              <h4 class="text-sm font-semibold text-white">
                Écoute
              </h4>

              <p class="mt-2 text-sm leading-6 text-white/45">
                Nous prenons le temps de comprendre votre besoin.
              </p>
            </div>

            <div class="border-l border-[#c9a96e] pl-5">
              <h4 class="text-sm font-semibold text-white">
                Style personnel
              </h4>

              <p class="mt-2 text-sm leading-6 text-white/45">
                Votre tenue doit refléter votre personnalité.
              </p>
            </div>

          </div>

        </div>

      </div>

      <!-- STATISTIQUES -->
      <div
        class="mt-24 grid border-y border-white/10
               sm:grid-cols-3"
      >

        <div class="px-6 py-8 text-center sm:border-r sm:border-white/10">
          <p class="text-3xl font-semibold text-[#c9a96e]">
            100%
          </p>

          <p
            class="mt-2 text-xs uppercase tracking-[0.2em]
                   text-white/40"
          >
            Sur mesure
          </p>
        </div>

        <div class="px-6 py-8 text-center sm:border-r sm:border-white/10">
          <p class="text-3xl font-semibold text-[#c9a96e]">
            01
          </p>

          <p
            class="mt-2 text-xs uppercase tracking-[0.2em]
                   text-white/40"
          >
            Style personnalisé
          </p>
        </div>

        <div class="px-6 py-8 text-center">
          <p class="text-3xl font-semibold text-[#c9a96e]">
            ∞
          </p>

          <p
            class="mt-2 text-xs uppercase tracking-[0.2em]
                   text-white/40"
          >
            Possibilités
          </p>
        </div>

      </div>

    </div>
  </section>
</template>