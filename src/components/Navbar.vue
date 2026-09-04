```vue
<script setup>
import { ref } from 'vue'

const isMenuOpen = ref(false)

const closeMenu = () => {
  isMenuOpen.value = false
}
</script>

<template>
  <header
    class="fixed inset-x-0 top-0 z-50 border-b border-white/10
           bg-[#0b0b0b]/90 backdrop-blur-md"
  >
    <nav
      class="mx-auto flex h-20 max-w-7xl items-center
             justify-between px-6 lg:px-8"
    >

      <!-- =========================
           LOGO
      ========================== -->
      <a
        href="#accueil"
        @click="closeMenu"
        class="group flex items-center gap-3"
      >
        <div
          class="flex h-10 w-10 items-center justify-center
                 border border-[#c9a96e] text-[#c9a96e]
                 transition duration-300
                 group-hover:bg-[#c9a96e]
                 group-hover:text-black"
        >
          <span class="text-lg font-bold">
            HS
          </span>
        </div>

        <div class="leading-none">
          <span
            class="block text-lg font-semibold tracking-[0.2em]
                   text-white"
          >
            HOMME SAGE
          </span>

          <span
            class="mt-1 block text-[9px] uppercase
                   tracking-[0.3em] text-white/50"
          >
            Tailleur • Yaoundé
          </span>
        </div>
      </a>


      <!-- =========================
           DESKTOP MENU
      ========================== -->
      <div class="hidden items-center gap-8 md:flex">

        <a
          href="#accueil"
          class="text-sm text-white/70 transition
                 hover:text-[#c9a96e]"
        >
          Accueil
        </a>

        <a
          href="#apropos"
          class="text-sm text-white/70 transition
                 hover:text-[#c9a96e]"
        >
          À propos
        </a>

        <a
          href="#services"
          class="text-sm text-white/70 transition
                 hover:text-[#c9a96e]"
        >
          Services
        </a>

        <a
          href="#gallery"
          class="text-sm text-white/70 transition
                 hover:text-[#c9a96e]"
        >
          Réalisations
        </a>

        <a
          href="#testimonials"
          class="text-sm text-white/70 transition
                 hover:text-[#c9a96e]"
        >
          Avis
        </a>

        <a
          href="#location"
          class="text-sm text-white/70 transition
                 hover:text-[#c9a96e]"
        >
          Atelier
        </a>

        <a
          href="#contact"
          class="border border-[#c9a96e] px-5 py-3
                 text-xs font-medium uppercase
                 tracking-wider text-[#c9a96e]
                 transition duration-300
                 hover:bg-[#c9a96e]
                 hover:text-black"
        >
          Prendre rendez-vous
        </a>

      </div>


      <!-- =========================
           MOBILE BUTTON
      ========================== -->
      <button
        type="button"
        @click="isMenuOpen = !isMenuOpen"
        class="flex h-10 w-10 items-center justify-center
               border border-white/20 md:hidden"
        :aria-expanded="isMenuOpen"
        aria-label="Ouvrir le menu"
      >
        <div class="space-y-1.5">

          <span
            class="block h-px w-5 bg-white transition"
            :class="isMenuOpen ? 'translate-y-2 rotate-45' : ''"
          ></span>

          <span
            class="block h-px w-5 bg-white transition"
            :class="isMenuOpen ? 'opacity-0' : ''"
          ></span>

          <span
            class="block h-px w-5 bg-white transition"
            :class="isMenuOpen ? '-translate-y-2 -rotate-45' : ''"
          ></span>

        </div>
      </button>

    </nav>


    <!-- =========================
         MOBILE MENU
    ========================== -->
    <div
      v-if="isMenuOpen"
      class="border-t border-white/10
             bg-[#0b0b0b] md:hidden"
    >
      <div class="flex flex-col px-6 py-6">

        <a
          href="#accueil"
          @click="closeMenu"
          class="border-b border-white/10 py-4
                 text-sm text-white/70
                 transition hover:text-[#c9a96e]"
        >
          Accueil
        </a>

        <a
          href="#apropos"
          @click="closeMenu"
          class="border-b border-white/10 py-4
                 text-sm text-white/70
                 transition hover:text-[#c9a96e]"
        >
          À propos
        </a>

        <a
          href="#services"
          @click="closeMenu"
          class="border-b border-white/10 py-4
                 text-sm text-white/70
                 transition hover:text-[#c9a96e]"
        >
          Services
        </a>

        <a
          href="#gallery"
          @click="closeMenu"
          class="border-b border-white/10 py-4
                 text-sm text-white/70
                 transition hover:text-[#c9a96e]"
        >
          Réalisations
        </a>

        <a
          href="#testimonials"
          @click="closeMenu"
          class="border-b border-white/10 py-4
                 text-sm text-white/70
                 transition hover:text-[#c9a96e]"
        >
          Avis
        </a>

        <a
          href="#location"
          @click="closeMenu"
          class="border-b border-white/10 py-4
                 text-sm text-white/70
                 transition hover:text-[#c9a96e]"
        >
          Atelier
        </a>

        <a
          href="#contact"
          @click="closeMenu"
          class="mt-5 border border-[#c9a96e]
                 px-5 py-4 text-center
                 text-xs uppercase tracking-wider
                 text-[#c9a96e]
                 transition duration-300
                 hover:bg-[#c9a96e]
                 hover:text-black"
        >
          Prendre rendez-vous
        </a>

      </div>
    </div>

  </header>
</template>
```
