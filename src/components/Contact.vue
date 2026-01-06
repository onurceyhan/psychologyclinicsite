<template>
  <section id="iletisim" class="py-20 px-6 bg-gradient-to-br from-mint-50 via-sky-50 to-bubblegum-50 relative overflow-hidden">
    <!-- Decorative elements -->
    <div class="cute-blob w-96 h-96 bg-mint-300 top-0 left-0"></div>
    <div class="cute-blob w-80 h-80 bg-bubblegum-300 bottom-0 right-0"></div>
    
    <div class="max-w-7xl mx-auto relative z-10">
      <div class="text-center mb-16">
        <div class="inline-flex items-center gap-4 mb-6">
          <span class="text-6xl animate-bounce-slow">📞</span>
          <h2 class="section-title">
            İletişim & Randevu
          </h2>
          <span class="text-6xl animate-bounce-slow" style="animation-delay: 0.5s;">✉️</span>
        </div>
        <p class="text-2xl text-gray-700 max-w-3xl mx-auto mt-4 font-bold">
          Çocuğunuz için en iyi desteği sağlamak üzere sizinleyiz! 💝
        </p>
      </div>
      
      <div class="grid md:grid-cols-2 gap-12">
        <!-- Contact Info -->
        <div class="space-y-6">
          <div class="card bg-gradient-to-br from-mint-100 to-mint-200 border-mint-300 hover:border-mint-500">
            <div class="flex items-start space-x-4">
              <div class="text-6xl animate-bounce-slow">📍</div>
              <div>
                <h3 class="text-2xl font-fun font-bold text-gray-800 mb-3">Adres</h3>
                <p class="text-gray-700 text-lg font-medium">
                  Pınadağı Mahallesi, Uysal Sokak No:123<br />
                  İstanbul, Türkiye 🏠
                </p>
              </div>
            </div>
          </div>
          
          <div class="card bg-gradient-to-br from-sky-100 to-sky-200 border-sky-300 hover:border-sky-500">
            <div class="flex items-start space-x-4">
              <div class="text-6xl animate-wiggle">📞</div>
              <div>
                <h3 class="text-2xl font-fun font-bold text-gray-800 mb-3">Telefon</h3>
                <p class="text-gray-700 text-lg font-medium">
                  +90 (555) 123-4567 ☎️<br />
                  <span class="text-base bg-white px-3 py-1 rounded-full inline-block mt-2">
                    ⏰ Pazartesi - Cuma: 09:00 - 18:00
                  </span>
                </p>
              </div>
            </div>
          </div>
          
          <div class="card bg-gradient-to-br from-bubblegum-100 to-bubblegum-200 border-bubblegum-300 hover:border-bubblegum-500">
            <div class="flex items-start space-x-4">
              <div class="text-6xl animate-pulse">✉️</div>
              <div>
                <h3 class="text-2xl font-fun font-bold text-gray-800 mb-3">E-posta</h3>
                <p class="text-gray-700 text-lg font-medium">
                  info@uysalpsikolog.com<br />
                  randevu@uysalpsikolog.com 📧
                </p>
              </div>
            </div>
          </div>
          
          <div class="card bg-gradient-to-br from-sunshine-100 via-peach-100 to-sunshine-200 border-sunshine-400 hover:border-sunshine-600 relative overflow-hidden">
            <div class="absolute top-0 right-0 text-9xl opacity-10">🎁</div>
            <h3 class="text-3xl font-fun font-bold text-gray-800 mb-4 flex items-center relative z-10">
              <span class="text-5xl mr-4 animate-wiggle">🎁</span>
              İlk Görüşme Ücretsiz!
            </h3>
            <p class="text-gray-700 text-lg font-medium relative z-10">
              İlk tanışma seansınız bizden hediye! 🌟 Çocuğunuzun ihtiyaçlarını birlikte değerlendirelim.
            </p>
          </div>
        </div>
        
        <!-- Contact Form -->
        <div class="card bg-gradient-to-br from-white to-bubblegum-50 border-bubblegum-300 hover:border-bubblegum-500">
          <div class="flex items-center gap-3 mb-8">
            <span class="text-5xl animate-wiggle">📝</span>
            <h3 class="text-3xl font-fun font-bold text-gray-800">
              Randevu Formu
            </h3>
          </div>
          
          <form @submit.prevent="handleSubmit" class="space-y-6">
            <div>
              <label class="block text-gray-800 font-bold mb-3 text-lg">✨ İsim Soyisim *</label>
              <input 
                type="text" 
                required
                v-model="form.name"
                class="w-full px-6 py-4 rounded-2xl border-4 border-mint-200 focus:border-mint-400 focus:outline-none transition-all text-lg font-medium hover:border-mint-300"
                placeholder="Adınız ve soyadınız"
              />
            </div>
            
            <div>
              <label class="block text-gray-800 font-bold mb-3 text-lg">📧 E-posta *</label>
              <input 
                type="email" 
                required
                v-model="form.email"
                class="w-full px-6 py-4 rounded-2xl border-4 border-sky-200 focus:border-sky-400 focus:outline-none transition-all text-lg font-medium hover:border-sky-300"
                placeholder="ornek@email.com"
              />
            </div>
            
            <div>
              <label class="block text-gray-800 font-bold mb-3 text-lg">📱 Telefon *</label>
              <input 
                type="tel" 
                required
                v-model="form.phone"
                class="w-full px-6 py-4 rounded-2xl border-4 border-sunshine-200 focus:border-sunshine-400 focus:outline-none transition-all text-lg font-medium hover:border-sunshine-300"
                placeholder="+90 (555) 123-4567"
              />
            </div>
            
            <div>
              <label class="block text-gray-800 font-bold mb-3 text-lg">🎂 Çocuğun Yaşı</label>
              <input 
                type="number" 
                v-model="form.childAge"
                class="w-full px-6 py-4 rounded-2xl border-4 border-purple-200 focus:border-purple-400 focus:outline-none transition-all text-lg font-medium hover:border-purple-300"
                placeholder="Örn: 5"
              />
            </div>
            
            <div>
              <label class="block text-gray-800 font-bold mb-3 text-lg">💬 Mesajınız</label>
              <textarea 
                rows="4"
                v-model="form.message"
                class="w-full px-6 py-4 rounded-2xl border-4 border-pink-200 focus:border-pink-400 focus:outline-none transition-all resize-none text-lg font-medium hover:border-pink-300"
                placeholder="Bizimle paylaşmak istediğiniz detaylar..."
              ></textarea>
            </div>
            
            <button type="submit" class="btn-primary w-full text-center text-xl">
              🌟 Randevu Talebi Gönder
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue'

const form = ref({
  name: '',
  email: '',
  phone: '',
  childAge: '',
  message: ''
})

const handleSubmit = () => {
  alert('Randevu talebiniz alındı! En kısa sürede sizinle iletişime geçeceğiz.')
  // Reset form
  form.value = {
    name: '',
    email: '',
    phone: '',
    childAge: '',
    message: ''
  }
}
</script>


