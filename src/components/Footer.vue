```vue
<template>
  <footer
    class="relative overflow-hidden border-t border-white/10 bg-[#080808]"
  >

    <!-- =========================
         MAIN FOOTER
    ========================== -->
    <div class="mx-auto max-w-7xl px-6 py-20 lg:px-8">

      <div
        class="grid gap-14 lg:grid-cols-12 lg:gap-8"
      >

        <!-- =========================
             BRAND
        ========================== -->
        <div class="lg:col-span-5">

          <a
            href="#"
            class="inline-block"
          >
            <span
              class="text-2xl font-semibold tracking-[0.18em]
                     text-white"
            >
              HOMME
            </span>

            <span
              class="ml-2 text-2xl font-light tracking-[0.18em]
                     text-[#c9a96e]"
            >
              SAGE
            </span>
          </a>

          <p
            class="mt-6 max-w-sm text-sm leading-7 text-white/40"
          >
            L'élégance pensée pour vous.
            Des créations sur mesure conçues avec précision,
            caractère et savoir-faire.
          </p>

          <a
            href="#contact"
            class="mt-8 inline-flex items-center gap-3
                   border border-[#c9a96e]
                   px-6 py-3
                   text-xs font-medium uppercase
                   tracking-[0.2em] text-[#c9a96e]
                   transition duration-300
                   hover:bg-[#c9a96e]
                   hover:text-black"
          >
            Prendre rendez-vous

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


        <!-- =========================
             NAVIGATION
        ========================== -->
        <div class="lg:col-span-2">

          <p
            class="text-[10px] uppercase
                   tracking-[0.25em] text-[#c9a96e]"
          >
            Navigation
          </p>

          <nav class="mt-6">

            <ul class="space-y-4">

              <li>
                <a
                  href="#home"
                  class="text-sm text-white/45
                         transition duration-300
                         hover:text-white"
                >
                  Accueil
                </a>
              </li>

              <li>
                <a
                  href="#about"
                  class="text-sm text-white/45
                         transition duration-300
                         hover:text-white"
                >
                  À propos
                </a>
              </li>

              <li>
                <a
                  href="#services"
                  class="text-sm text-white/45
                         transition duration-300
                         hover:text-white"
                >
                  Services
                </a>
              </li>

              <li>
                <a
                  href="#gallery"
                  class="text-sm text-white/45
                         transition duration-300
                         hover:text-white"
                >
                  Galerie
                </a>
              </li>

              <li>
                <a
                  href="#testimonials"
                  class="text-sm text-white/45
                         transition duration-300
                         hover:text-white"
                >
                  Témoignages
                </a>
              </li>

              <li>
                <a
                  href="#location"
                  class="text-sm text-white/45
                         transition duration-300
                         hover:text-white"
                >
                  Atelier
                </a>
              </li>

            </ul>

          </nav>

        </div>


        <!-- =========================
             CONTACT
        ========================== -->
        <div class="lg:col-span-3">

          <p
            class="text-[10px] uppercase
                   tracking-[0.25em] text-[#c9a96e]"
          >
            Contact
          </p>

          <div class="mt-6 space-y-5">

            <!-- Téléphone -->
            <a
              href="tel:+237000000000"
              class="group flex items-start gap-4"
            >

              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="mt-0.5 h-5 w-5 shrink-0 text-[#c9a96e]"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.174.417l-.97 1.293c-.282.376-.769.542-1.222.394a12.035 12.035 0 0 1-7.405-7.405c-.148-.453.018-.94.394-1.222l1.293-.97c.362-.272.527-.734.417-1.174L6.752 3.102A1.125 1.125 0 0 0 5.661 2.25H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z"
                />
              </svg>

              <span
                class="text-sm text-white/45
                       transition duration-300
                       group-hover:text-white"
              >
                +237 00 00 00 00 00
              </span>

            </a>


            <!-- Email -->
            <a
              href="mailto:contact@hommesage.com"
              class="group flex items-start gap-4"
            >

              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="mt-0.5 h-5 w-5 shrink-0 text-[#c9a96e]"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25H4.5a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0-9.75 6.75L2.25 6.75"
                />
              </svg>

              <span
                class="text-sm text-white/45
                       transition duration-300
                       group-hover:text-white"
              >
                contact@hommesage.com
              </span>

            </a>


            <!-- Adresse -->
            <div class="flex items-start gap-4">

              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="mt-0.5 h-5 w-5 shrink-0 text-[#c9a96e]"
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

              <span
                class="text-sm leading-6 text-white/45"
              >
                Votre adresse ici
                <br />
                Ville, Cameroun
              </span>

            </div>

          </div>

        </div>


        <!-- =========================
             SOCIAL
        ========================== -->
        <div class="lg:col-span-2">

          <p
            class="text-[10px] uppercase
                   tracking-[0.25em] text-[#c9a96e]"
          >
            Suivez-nous
          </p>

          <div class="mt-6 flex gap-3">

            <!-- Instagram -->
            <a
              href="#"
              aria-label="Instagram"
              class="flex h-10 w-10 items-center
                     justify-center border border-white/10
                     text-white/45
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
                <rect
                  width="18"
                  height="18"
                  x="3"
                  y="3"
                  rx="5"
                />
                <circle
                  cx="12"
                  cy="12"
                  r="4"
                />
                <circle
                  cx="17.5"
                  cy="6.5"
                  r=".75"
                  fill="currentColor"
                  stroke="none"
                />
              </svg>
            </a>


            <!-- Facebook -->
            <a
              href="#"
              aria-label="Facebook"
              class="flex h-10 w-10 items-center
                     justify-center border border-white/10
                     text-white/45
                     transition duration-300
                     hover:border-[#c9a96e]
                     hover:text-[#c9a96e]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                fill="currentColor"
                class="h-4 w-4"
              >
                <path
                  d="M14 8h3V4h-3c-3.314 0-5 1.686-5 5v3H6v4h3v4h4v-4h3.2l.8-4H13V9c0-.667.333-1 1-1Z"
                />
              </svg>
            </a>


            <!-- WhatsApp -->
            <a
              href="#"
              aria-label="WhatsApp"
              class="flex h-10 w-10 items-center
                     justify-center border border-white/10
                     text-white/45
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
                  d="M6.5 19.5 4.5 21l.7-2.7A8.5 8.5 0 1 1 6.5 19.5Z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M8.5 9.5c.5 2 2 3.5 4 4 .5.1 1-.1 1.3-.5l.5-.7"
                />
              </svg>
            </a>

          </div>

        </div>

      </div>


      <!-- =========================
           SEPARATOR
      ========================== -->
      <div
        class="mt-20 border-t border-white/10"
      ></div>


      <!-- =========================
           BOTTOM BAR
      ========================== -->
      <div
        class="flex flex-col gap-5 pt-8
               sm:flex-row sm:items-center
               sm:justify-between"
      >

        <p
          class="text-[10px] uppercase
                 tracking-[0.15em] text-white/25"
        >
          © 2026 HOMME SAGE. Tous droits réservés.
        </p>

        <div
          class="flex gap-6"
        >

          <a
            href="#"
            class="text-[10px] uppercase
                   tracking-[0.15em] text-white/25
                   transition duration-300
                   hover:text-white/60"
          >
            Mentions légales
          </a>

          <a
            href="#"
            class="text-[10px] uppercase
                   tracking-[0.15em] text-white/25
                   transition duration-300
                   hover:text-white/60"
          >
            Confidentialité
          </a>

        </div>

      </div>

    </div>


    <!-- =========================
         DECORATIVE TEXT
    ========================== -->
    <div
      class="pointer-events-none absolute -bottom-10
             left-1/2 hidden -translate-x-1/2
             select-none whitespace-nowrap
             text-[12vw] font-semibold
             tracking-[-0.04em] text-white/[0.015]
             lg:block"
    >
      HOMME SAGE
    </div>

  </footer>
</template>
```
