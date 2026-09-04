```vue
<template>
  <section
    id="location"
    class="relative overflow-hidden bg-[#0b0b0b] py-24 sm:py-32"
  >
    <div class="mx-auto max-w-7xl px-6 lg:px-8">

      <!-- =========================
           HEADER
      ========================== -->
      <div class="max-w-3xl">

        <div class="mb-5 flex items-center gap-4">
          <span class="h-px w-10 bg-[#c9a96e]"></span>

          <span
            class="text-xs uppercase tracking-[0.3em] text-[#c9a96e]"
          >
            Notre atelier
          </span>
        </div>

        <h2
          class="text-4xl font-semibold leading-tight tracking-tight
                 text-white sm:text-5xl lg:text-6xl"
        >
          Venez découvrir
          <span class="font-light italic text-[#c9a96e]">
            HOMME SAGE.
          </span>
        </h2>

        <p
          class="mt-6 max-w-2xl text-sm leading-7 text-white/45 sm:text-base"
        >
          Un espace dédié à la création, aux échanges et au savoir-faire.
          Prenez rendez-vous et venez discuter de votre prochaine tenue
          directement avec nous.
        </p>

      </div>


      <!-- =========================
           CONTENT
      ========================== -->
      <div
        class="mt-16 grid gap-8 lg:grid-cols-12 lg:gap-12"
      >

        <!-- =========================
             INFORMATIONS
        ========================== -->
        <div
          class="lg:col-span-5"
        >

          <div
            class="border border-white/10 bg-[#0f0f0f]"
          >

            <!-- Adresse -->
            <div
              class="border-b border-white/10 p-8 sm:p-10"
            >

              <div class="flex gap-5">

                <div
                  class="flex h-11 w-11 shrink-0 items-center
                         justify-center border border-[#c9a96e]/30
                         text-[#c9a96e]"
                >
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
                      d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
                    />
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"
                    />
                  </svg>
                </div>

                <div>
                  <p
                    class="text-[10px] uppercase tracking-[0.25em]
                           text-[#c9a96e]"
                  >
                    Adresse
                  </p>

                  <p
                    class="mt-3 text-sm leading-6 text-white/70"
                  >
                    Votre adresse ici
                    <br />
                    Ville, Pays
                  </p>
                </div>

              </div>

            </div>


            <!-- Horaires -->
            <div
              class="border-b border-white/10 p-8 sm:p-10"
            >

              <div class="flex gap-5">

                <div
                  class="flex h-11 w-11 shrink-0 items-center
                         justify-center border border-[#c9a96e]/30
                         text-[#c9a96e]"
                >
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
                      d="M12 6v6l4 2"
                    />
                    <circle
                      cx="12"
                      cy="12"
                      r="9"
                    />
                  </svg>
                </div>

                <div class="w-full">

                  <p
                    class="text-[10px] uppercase tracking-[0.25em]
                           text-[#c9a96e]"
                  >
                    Horaires
                  </p>

                  <div
                    class="mt-3 space-y-2 text-sm text-white/60"
                  >
                    <div class="flex justify-between gap-6">
                      <span>Lundi — Vendredi</span>
                      <span>08:00 — 18:00</span>
                    </div>

                    <div class="flex justify-between gap-6">
                      <span>Samedi</span>
                      <span>09:00 — 15:00</span>
                    </div>

                    <div class="flex justify-between gap-6">
                      <span>Dimanche</span>
                      <span class="text-white/30">
                        Fermé
                      </span>
                    </div>
                  </div>

                </div>

              </div>

            </div>


            <!-- Rendez-vous -->
            <div class="p-8 sm:p-10">

              <p
                class="text-xs uppercase tracking-[0.2em]
                       text-white/30"
              >
                Visite sur rendez-vous
              </p>

              <p
                class="mt-3 text-sm leading-6 text-white/50"
              >
                Pour bénéficier d'un accompagnement personnalisé,
                nous vous recommandons de prendre rendez-vous avant
                votre visite.
              </p>

              <a
                href="#contact"
                class="mt-6 inline-flex items-center gap-3
                       text-xs font-medium uppercase
                       tracking-[0.2em] text-[#c9a96e]
                       transition duration-300
                       hover:text-white"
              >
                Prendre rendez-vous

                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="h-4 w-4 transition-transform
                         duration-300 group-hover:translate-x-1"
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

        </div>


        <!-- =========================
             CARTE
        ========================== -->
        <div
          class="relative min-h-[420px] overflow-hidden
                 border border-white/10 bg-[#111111]
                 lg:col-span-7"
        >

          <!-- Placeholder carte -->
          <div
            class="absolute inset-0 flex items-center
                   justify-center"
          >

            <div class="text-center">

              <div
                class="mx-auto flex h-16 w-16 items-center
                       justify-center rounded-full
                       border border-[#c9a96e]/30
                       text-[#c9a96e]"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="h-7 w-7"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"
                  />
                </svg>
              </div>

              <p
                class="mt-5 text-xs uppercase
                       tracking-[0.25em] text-white/40"
              >
                HOMME SAGE
              </p>

              <p class="mt-2 text-sm text-white/25">
                Votre localisation apparaîtra ici
              </p>

            </div>

          </div>


          <!-- Coordonnées décoratives -->
          <div
            class="absolute left-6 top-6
                   text-[9px] uppercase
                   tracking-[0.25em] text-white/20"
          >
            LOCATION / 01
          </div>

          <div
            class="absolute bottom-6 right-6
                   text-[9px] uppercase
                   tracking-[0.25em] text-white/20"
          >
            HOMME SAGE
          </div>

        </div>

      </div>


      <!-- =========================
           BOTTOM CTA
      ========================== -->
      <div
        class="mt-16 flex flex-col items-start
               justify-between gap-6 border-t
               border-white/10 pt-10
               sm:flex-row sm:items-center"
      >

        <div>
          <p class="text-lg text-white">
            Une question avant votre visite ?
          </p>

          <p class="mt-2 text-sm text-white/35">
            Contactez-nous directement.
          </p>
        </div>

        <a
          href="#contact"
          class="inline-flex items-center gap-3
                 border border-white/15 px-6 py-3
                 text-xs uppercase
                 tracking-[0.2em] text-white/70
                 transition duration-300
                 hover:border-[#c9a96e]
                 hover:text-[#c9a96e]"
        >
          Nous contacter

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
        </a>

      </div>

    </div>
  </section>
</template>
```
