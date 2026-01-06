<template>
  <section id="oyun-terapisi" class="py-20 px-6 relative">
    <!-- Decorative elements -->
    <div class="absolute top-20 left-10 text-6xl opacity-20 animate-float">🌈</div>
    <div class="absolute bottom-20 right-10 text-6xl opacity-20 animate-bounce-slow">🎪</div>
    
    <div class="max-w-7xl mx-auto relative">
      <div class="text-center mb-16">
        <div class="inline-flex items-center gap-4 mb-6">
          <span class="text-6xl animate-wiggle">🎨</span>
          <h2 class="section-title">
            Çocuklarla Oyun Terapisi
          </h2>
          <span class="text-6xl animate-wiggle" style="animation-delay: 0.5s;">🎭</span>
        </div>
        <p class="text-2xl text-gray-700 max-w-3xl mx-auto mt-4 font-medium">
          Oyun yoluyla çocuklarınızın duygusal gelişimini destekliyoruz! 🌟
        </p>
      </div>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Card 1: Play Therapy -->
        <div class="card bg-gradient-to-br from-sunshine-100 via-peach-100 to-sunshine-200 border-sunshine-300 hover:border-sunshine-500 relative overflow-hidden">
          <div class="absolute top-0 right-0 text-4xl opacity-30">🌟</div>
          <div class="text-center relative z-10">
            <div class="w-40 h-40 mx-auto mb-6 relative">
              <div class="w-full h-full bg-gradient-to-br from-sunshine-400 to-peach-400 rounded-full flex items-center justify-center text-7xl shadow-2xl animate-bounce-slow border-4 border-white">
                🧸
              </div>
            </div>
            <h3 class="text-3xl font-fun font-bold text-gray-800 mb-4">
              Çocuk Oyun Terapisi
            </h3>
            <p class="text-gray-700 leading-relaxed text-lg font-medium">
              Oyun terapisi çocukların duygularını ifade etmelerine yardımcı olan etkili bir yöntemdir! 🎨
            </p>
          </div>
        </div>
        
        <!-- Card 2: Group Therapy -->
        <div class="card bg-gradient-to-br from-sky-100 via-blue-100 to-sky-200 border-sky-300 hover:border-sky-500 relative overflow-hidden">
          <div class="absolute bottom-0 left-0 text-4xl opacity-30">💫</div>
          <div class="text-center relative z-10">
            <div class="w-40 h-40 mx-auto mb-6 relative">
              <div class="w-full h-full bg-gradient-to-br from-sky-400 to-blue-400 rounded-full flex items-center justify-center text-7xl shadow-2xl animate-bounce-slow border-4 border-white" style="animation-delay: 0.2s;">
                🐰
              </div>
            </div>
            <h3 class="text-3xl font-fun font-bold text-gray-800 mb-4">
              Grup Terapisi
            </h3>
            <p class="text-gray-700 leading-relaxed text-lg font-medium">
              Çocukların sosyal becerilerini geliştiren eğlenceli grup terapi seansları! 🤝
            </p>
          </div>
        </div>
        
        <!-- Card 3: Individual Therapy -->
        <div class="card bg-gradient-to-br from-mint-100 via-emerald-100 to-mint-200 border-mint-300 hover:border-mint-500 relative overflow-hidden">
          <div class="absolute top-0 left-0 text-4xl opacity-30">✨</div>
          <div class="text-center relative z-10">
            <div class="w-40 h-40 mx-auto mb-6 relative">
              <div class="w-full h-full bg-gradient-to-br from-mint-400 to-emerald-400 rounded-full flex items-center justify-center text-7xl shadow-2xl animate-bounce-slow border-4 border-white" style="animation-delay: 0.4s;">
                🦊
              </div>
            </div>
            <h3 class="text-3xl font-fun font-bold text-gray-800 mb-4">
              Bireysel Terapi
            </h3>
            <p class="text-gray-700 leading-relaxed text-lg font-medium">
              Her çocuğun benzersiz ihtiyaçlarına özel bireysel terapi programları! 💝
            </p>
          </div>
        </div>
      </div>
      
      <!-- Benefits Section -->
      <div class="mt-20 grid md:grid-cols-2 gap-12 items-center">
        <div class="space-y-6">
          <h3 class="text-4xl md:text-5xl font-fun font-bold bg-gradient-to-r from-bubblegum-500 to-mint-500 bg-clip-text text-transparent mb-8">
            Oyun Terapisinin Faydaları
          </h3>
          <ul class="space-y-5">
            <li class="flex items-start space-x-4 bg-gradient-to-r from-bubblegum-50 to-pink-50 p-4 rounded-2xl border-2 border-bubblegum-200 hover:scale-105 transition-transform">
              <span class="text-4xl animate-pulse">🌟</span>
              <span class="text-gray-800 text-lg font-semibold">Duygusal ifade ve öz-farkındalığı geliştirir</span>
            </li>
            <li class="flex items-start space-x-4 bg-gradient-to-r from-sunshine-50 to-yellow-50 p-4 rounded-2xl border-2 border-sunshine-200 hover:scale-105 transition-transform">
              <span class="text-4xl animate-pulse" style="animation-delay: 0.1s;">💪</span>
              <span class="text-gray-800 text-lg font-semibold">Özgüven ve öz-saygıyı artırır</span>
            </li>
            <li class="flex items-start space-x-4 bg-gradient-to-r from-sky-50 to-blue-50 p-4 rounded-2xl border-2 border-sky-200 hover:scale-105 transition-transform">
              <span class="text-4xl animate-pulse" style="animation-delay: 0.2s;">🤝</span>
              <span class="text-gray-800 text-lg font-semibold">Sosyal becerileri güçlendirir</span>
            </li>
            <li class="flex items-start space-x-4 bg-gradient-to-r from-mint-50 to-emerald-50 p-4 rounded-2xl border-2 border-mint-200 hover:scale-105 transition-transform">
              <span class="text-4xl animate-pulse" style="animation-delay: 0.3s;">🎯</span>
              <span class="text-gray-800 text-lg font-semibold">Problem çözme becerilerini destekler</span>
            </li>
            <li class="flex items-start space-x-4 bg-gradient-to-r from-red-50 to-pink-50 p-4 rounded-2xl border-2 border-red-200 hover:scale-105 transition-transform">
              <span class="text-4xl animate-pulse" style="animation-delay: 0.4s;">❤️</span>
              <span class="text-gray-800 text-lg font-semibold">Ebeveyn-çocuk ilişkisini iyileştirir</span>
            </li>
          </ul>
        </div>
        <div class="relative h-[500px] rounded-[3rem] overflow-hidden shadow-2xl group">
          <div class="absolute inset-0 bg-gradient-to-br from-bubblegum-400 to-mint-400 transform group-hover:scale-110 transition-transform"></div>
          <img 
            src="https://images.unsplash.com/photo-1587616211892-22b256f6e5fb?w=800&q=80" 
            alt="Child playing"
            class="absolute inset-4 w-[calc(100%-2rem)] h-[calc(100%-2rem)] object-cover rounded-3xl"
          />
          <div class="absolute -top-8 -right-8 text-7xl animate-bounce-slow">🎈</div>
          <div class="absolute -bottom-8 -left-8 text-7xl animate-wiggle">🎪</div>
        </div>
      </div>
    </div>
  </section>
</template>


