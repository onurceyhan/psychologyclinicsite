<template>
  <div class="min-h-screen bg-gradient-to-br from-pink-50 via-yellow-50 to-blue-50">
    <Navbar />
    <Hero />
    <TherapySection />
    <About />
    <ParentGuide />
    <Contact />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import TherapySection from './components/TherapySection.vue'
import About from './components/About.vue'
import ParentGuide from './components/ParentGuide.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
</script>


