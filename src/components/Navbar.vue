<template>
  <nav class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-md shadow-lg border-b-4 border-bubblegum-200">
    <div class="max-w-7xl mx-auto px-6 py-4">
      <div class="flex items-center justify-between">
        <!-- Logo -->
        <a href="#" class="font-display text-2xl md:text-3xl bg-gradient-to-r from-bubblegum-500 to-sunshine-500 bg-clip-text text-transparent hover:scale-105 transition-transform flex items-center gap-2">
          <span class="text-4xl animate-bounce-slow">🌈</span>
          Uysal Psikolog Kliniği
        </a>
        
        <!-- Desktop Navigation -->
        <div class="hidden md:flex items-center space-x-8">
          <a href="#oyun-terapisi" class="text-gray-700 hover:text-bubblegum-600 font-bold transition-all hover:scale-110">
            🎨 Oyun Terapisi
          </a>
          <a href="#hakkimizda" class="text-gray-700 hover:text-mint-600 font-bold transition-all hover:scale-110">
            💝 Hakkımızda
          </a>
          <a href="#ebeveyn-rehberi" class="text-gray-700 hover:text-sunshine-600 font-bold transition-all hover:scale-110">
            📚 Ebeveyn Rehberi
          </a>
          <a href="#iletisim" class="btn-primary">
            ✨ Randevu Al
          </a>
        </div>
        
        <!-- Mobile Menu Button -->
        <button 
          @click="mobileMenuOpen = !mobileMenuOpen"
          class="md:hidden p-2 text-bubblegum-600 hover:bg-bubblegum-100 rounded-2xl transition-all hover:scale-110"
        >
          <svg v-if="!mobileMenuOpen" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
          <svg v-else class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
          </svg>
        </button>
      </div>
      
      <!-- Mobile Menu -->
      <div v-if="mobileMenuOpen" class="md:hidden mt-4 pb-4 space-y-3 bg-gradient-to-br from-bubblegum-50 to-mint-50 rounded-3xl p-6 border-4 border-bubblegum-200">
        <a href="#oyun-terapisi" @click="mobileMenuOpen = false" class="block text-gray-700 hover:text-bubblegum-600 font-bold py-3 px-4 rounded-2xl hover:bg-white transition-all text-lg">
          🎨 Oyun Terapisi
        </a>
        <a href="#hakkimizda" @click="mobileMenuOpen = false" class="block text-gray-700 hover:text-mint-600 font-bold py-3 px-4 rounded-2xl hover:bg-white transition-all text-lg">
          💝 Hakkımızda
        </a>
        <a href="#ebeveyn-rehberi" @click="mobileMenuOpen = false" class="block text-gray-700 hover:text-sunshine-600 font-bold py-3 px-4 rounded-2xl hover:bg-white transition-all text-lg">
          📚 Ebeveyn Rehberi
        </a>
        <a href="#iletisim" @click="mobileMenuOpen = false" class="block btn-primary text-center mt-4">
          ✨ Randevu Al
        </a>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { ref } from 'vue'

const mobileMenuOpen = ref(false)
</script>


