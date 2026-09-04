```vue
<template>
  <section
    id="contact"
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
            Parlons de votre projet
          </span>
        </div>

        <h2
          class="text-4xl font-semibold leading-tight
                 tracking-tight text-white
                 sm:text-5xl lg:text-6xl"
        >
          Votre prochaine tenue
          <span class="font-light italic text-[#c9a96e]">
            commence ici.
          </span>
        </h2>

        <p
          class="mt-6 max-w-2xl text-sm leading-7 text-white/45 sm:text-base"
        >
          Décrivez-nous votre projet et nous vous recontacterons
          pour échanger sur vos envies, vos besoins et les détails
          de votre prochaine création.
        </p>

      </div>


      <!-- =========================
           CONTENT
      ========================== -->
      <div
        class="mt-16 grid gap-10 lg:grid-cols-12 lg:gap-16"
      >

        <!-- =========================
             FORMULAIRE
        ========================== -->
        <div class="lg:col-span-7">

          <form
            class="border border-white/10 bg-[#0f0f0f] p-6
                   sm:p-10"
            @submit.prevent
          >

            <div
              class="mb-10 flex items-center justify-between"
            >
              <div>
                <p
                  class="text-[10px] uppercase
                         tracking-[0.25em] text-[#c9a96e]"
                >
                  Rendez-vous
                </p>

                <p class="mt-2 text-sm text-white/40">
                  Quelques informations pour commencer.
                </p>
              </div>

              <span
                class="hidden text-xs tracking-[0.2em]
                       text-white/20 sm:block"
              >
                01 / 03
              </span>
            </div>


            <!-- NOM -->
            <div class="grid gap-8 sm:grid-cols-2">

              <div class="group">
                <label
                  for="name"
                  class="text-[10px] uppercase
                         tracking-[0.2em] text-white/40"
                >
                  Nom complet
                </label>

                <input
                  id="name"
                  type="text"
                  placeholder="Votre nom"
                  class="mt-3 w-full border-0 border-b
                         border-white/15 bg-transparent
                         px-0 py-3 text-sm text-white
                         outline-none transition
                         placeholder:text-white/20
                         focus:border-[#c9a96e]"
                />
              </div>


              <!-- TELEPHONE -->
              <div class="group">
                <label
                  for="phone"
                  class="text-[10px] uppercase
                         tracking-[0.2em] text-white/40"
                >
                  Téléphone
                </label>

                <input
                  id="phone"
                  type="tel"
                  placeholder="+237 ..."
                  class="mt-3 w-full border-0 border-b
                         border-white/15 bg-transparent
                         px-0 py-3 text-sm text-white
                         outline-none transition
                         placeholder:text-white/20
                         focus:border-[#c9a96e]"
                />
              </div>

            </div>


            <!-- EMAIL -->
            <div class="mt-8">

              <label
                for="email"
                class="text-[10px] uppercase
                       tracking-[0.2em] text-white/40"
              >
                Email
              </label>

              <input
                id="email"
                type="email"
                placeholder="votre@email.com"
                class="mt-3 w-full border-0 border-b
                       border-white/15 bg-transparent
                       px-0 py-3 text-sm text-white
                       outline-none transition
                       placeholder:text-white/20
                       focus:border-[#c9a96e]"
              />

            </div>


            <!-- SERVICE -->
            <div class="mt-8">

              <label
                for="service"
                class="text-[10px] uppercase
                       tracking-[0.2em] text-white/40"
              >
                Votre projet
              </label>

              <div class="relative">

                <select
                  id="service"
                  class="mt-3 w-full appearance-none
                         border-0 border-b border-white/15
                         bg-transparent px-0 py-3
                         text-sm text-white outline-none
                         transition
                         focus:border-[#c9a96e]"
                >
                  <option
                    value=""
                    disabled
                    selected
                    class="bg-[#0f0f0f]"
                  >
                    Sélectionnez une option
                  </option>

                  <option
                    value="sur-mesure"
                    class="bg-[#0f0f0f]"
                  >
                    Confection sur mesure
                  </option>

                  <option
                    value="personnalisation"
                    class="bg-[#0f0f0f]"
                  >
                    Personnalisation
                  </option>

                  <option
                    value="evenement"
                    class="bg-[#0f0f0f]"
                  >
                    Tenue événementielle
                  </option>

                  <option
                    value="conseil"
                    class="bg-[#0f0f0f]"
                  >
                    Conseil & style
                  </option>

                  <option
                    value="autre"
                    class="bg-[#0f0f0f]"
                  >
                    Autre projet
                  </option>
                </select>

                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="pointer-events-none absolute
                         right-0 top-1/2 h-4 w-4
                         -translate-y-1/2 text-white/30"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="m19.5 8.25-7.5 7.5-7.5-7.5"
                  />
                </svg>

              </div>

            </div>


            <!-- MESSAGE -->
            <div class="mt-8">

              <label
                for="message"
                class="text-[10px] uppercase
                       tracking-[0.2em] text-white/40"
              >
                Votre message
              </label>

              <textarea
                id="message"
                rows="4"
                placeholder="Parlez-nous de votre projet..."
                class="mt-3 w-full resize-none
                       border-0 border-b border-white/15
                       bg-transparent px-0 py-3 text-sm
                       leading-7 text-white outline-none
                       transition placeholder:text-white/20
                       focus:border-[#c9a96e]"
              ></textarea>

            </div>


            <!-- SUBMIT -->
            <div
              class="mt-10 flex flex-col gap-5
                     sm:flex-row sm:items-center
                     sm:justify-between"
            >

              <p
                class="max-w-xs text-[10px] leading-5
                       text-white/25"
              >
                Vos informations seront utilisées uniquement
                pour répondre à votre demande.
              </p>

              <button
                type="submit"
                class="inline-flex shrink-0 items-center
                       justify-center gap-3
                       bg-[#c9a96e] px-7 py-4
                       text-xs font-medium uppercase
                       tracking-[0.2em] text-black
                       transition duration-300
                       hover:bg-white"
              >
                Envoyer ma demande

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

          </form>

        </div>


        <!-- =========================
             INFORMATIONS CONTACT
        ========================== -->
        <div
          class="flex flex-col justify-between
                 lg:col-span-5"
        >

          <div>

            <p
              class="text-[10px] uppercase
                     tracking-[0.25em] text-[#c9a96e]"
            >
              Contact direct
            </p>

            <p
              class="mt-5 max-w-md text-2xl font-light
                     leading-relaxed text-white sm:text-3xl"
            >
              Une question ?
              <br />
              <span class="text-white/40">
                Parlons-en directement.
              </span>
            </p>


            <!-- TELEPHONE -->
            <a
              href="tel:+237000000000"
              class="group mt-10 flex items-center
                     gap-5 border-t border-white/10
                     pt-7"
            >

              <div
                class="flex h-11 w-11 items-center
                       justify-center border
                       border-[#c9a96e]/30
                       text-[#c9a96e]
                       transition duration-300
                       group-hover:bg-[#c9a96e]
                       group-hover:text-black"
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
                    d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25
                       a2.25 2.25 0 0 0 2.25-2.25v-1.372
                       c0-.516-.351-.966-.852-1.091l-4.423-1.106
                       c-.44-.11-.902.055-1.174.417l-.97 1.293
                       c-.282.376-.769.542-1.222.394
                       a12.035 12.035 0 0 1-7.405-7.405
                       c-.148-.453.018-.94.394-1.222l1.293-.97
                       c.362-.272.527-.734.417-1.174L6.752 3.102
                       A1.125 1.125 0 0 0 5.661 2.25H4.5
                       A2.25 2.25 0 0 0 2.25 4.5v2.25Z"
                  />
                </svg>
              </div>

              <div>
                <p
                  class="text-[10px] uppercase
                         tracking-[0.2em] text-white/30"
                >
                  Téléphone
                </p>

                <p
                  class="mt-1 text-sm text-white/70
                         transition group-hover:text-white"
                >
                  +237 00 00 00 00 00
                </p>
              </div>

            </a>


            <!-- EMAIL -->
            <a
              href="mailto:contact@hommesage.com"
              class="group flex items-center gap-5
                     border-t border-white/10 pt-7 mt-7"
            >

              <div
                class="flex h-11 w-11 items-center
                       justify-center border
                       border-[#c9a96e]/30
                       text-[#c9a96e]
                       transition duration-300
                       group-hover:bg-[#c9a96e]
                       group-hover:text-black"
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
                    d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25
                       2.25H4.5a2.25 2.25 0 0 1-2.25-2.25V6.75
                       m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15
                       a2.25 2.25 0 0 0-2.25 2.25
                       m19.5 0-9.75 6.75L2.25 6.75"
                  />
                </svg>
              </div>

              <div>
                <p
                  class="text-[10px] uppercase
                         tracking-[0.2em] text-white/30"
                >
                  Email
                </p>

                <p
                  class="mt-1 text-sm text-white/70
                         transition group-hover:text-white"
                >
                  contact@hommesage.com
                </p>
              </div>

            </a>

          </div>


          <!-- =========================
               WHATSAPP
          ========================== -->
          <a
            href="#"
            class="group mt-14 flex items-center
                   justify-between border
                   border-white/10 bg-[#0f0f0f]
                   p-6 transition duration-300
                   hover:border-[#c9a96e]/50
                   sm:p-7"
          >

            <div class="flex items-center gap-4">

              <div
                class="flex h-10 w-10 items-center
                       justify-center border
                       border-[#c9a96e]/30
                       text-[#c9a96e]"
              >
                <span class="text-sm font-semibold">
                  WA
                </span>
              </div>

              <div>
                <p
                  class="text-xs font-medium text-white"
                >
                  Échangeons sur WhatsApp
                </p>

                <p
                  class="mt-1 text-[10px] uppercase
                         tracking-[0.15em] text-white/30"
                >
                  Réponse rapide
                </p>
              </div>

            </div>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="h-5 w-5 text-[#c9a96e]
                     transition duration-300
                     group-hover:translate-x-1"
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


      <!-- =========================
           BOTTOM LINE
      ========================== -->
      <div
        class="mt-20 flex items-center gap-5"
      >

        <span class="h-px flex-1 bg-white/10"></span>

        <span
          class="text-[9px] uppercase
                 tracking-[0.3em] text-white/20"
        >
          HOMME SAGE — Tailleur • Yaoundé
        </span>

        <span class="h-px flex-1 bg-white/10"></span>

      </div>

    </div>
  </section>
</template>
```
