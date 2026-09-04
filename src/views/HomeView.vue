<script setup>
import Navbar from '../components/Navbar.vue'
import Hero from '../components/Hero.vue'
import About from '../components/About.vue'
import Services from '../components/Services.vue'
import Gallery from '../components/Gallery.vue'
import Testimonials from '../components/Testimonials.vue'
import Location from '../components/Location.vue'
import Footer from '../components/Footer.vue'
import Contact from '../components/Contact.vue'
</script>

<template>
  <div class="min-h-screen bg-[#0b0b0b] text-white">
    <Navbar />

    <main>
      <Hero />
      <About />
      <Services />
      <Gallery />
        <Testimonials />
      <Location />
        <Contact />
    </main> 

    <Footer />
  </div>
</template>