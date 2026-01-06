<template>
  <section id="hakkimizda" class="py-20 px-6 bg-gradient-to-br from-purple-50 via-pink-50 to-orange-50 relative overflow-hidden">
    <!-- Decorative blobs -->
    <div class="cute-blob w-96 h-96 bg-purple-300 top-0 right-0"></div>
    <div class="cute-blob w-80 h-80 bg-pink-300 bottom-0 left-0"></div>
    
    <div class="max-w-7xl mx-auto relative z-10">
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <!-- Image -->
        <div class="order-2 md:order-1">
          <div class="relative">
            <div class="absolute -top-6 -left-6 w-32 h-32 bg-bubblegum-300 rounded-full opacity-50 blur-2xl animate-pulse"></div>
            <div class="absolute -bottom-6 -right-6 w-40 h-40 bg-sunshine-300 rounded-full opacity-50 blur-2xl animate-pulse" style="animation-delay: 1s;"></div>
            <div class="relative h-[500px] rounded-[3rem] overflow-hidden shadow-2xl border-8 border-white group">
              <img 
                src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?w=800&q=80" 
                alt="Professional therapist"
                class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500"
              />
            </div>
            <div class="absolute -top-8 -right-8 text-6xl animate-wiggle">💝</div>
            <div class="absolute -bottom-8 -left-8 text-6xl animate-bounce-slow">🌈</div>
          </div>
        </div>
        
        <!-- Content -->
        <div class="order-1 md:order-2 space-y-8">
          <div class="inline-flex items-center gap-4 mb-4">
            <span class="text-6xl animate-bounce-slow">💝</span>
            <h2 class="section-title">
              Hakkımızda
            </h2>
          </div>
          
          <div class="space-y-6 text-xl text-gray-800 leading-relaxed font-medium">
            <div class="bg-white p-6 rounded-3xl shadow-lg border-4 border-bubblegum-200">
              <p>
                🌟 <strong class="text-bubblegum-600 text-2xl">Uysal Psikolog Kliniği</strong> olarak, çocukların duygusal ve psikolojik 
                gelişimlerine katkı sağlamak için uzman kadromuzla hizmet veriyoruz.
              </p>
            </div>
            <div class="bg-white p-6 rounded-3xl shadow-lg border-4 border-mint-200">
              <p>
                🎨 Uzman oyun terapistlerimiz, her çocuğun benzersiz ihtiyaçlarına göre özel programlar hazırlayarak, 
                onların sağlıklı bir şekilde büyümelerine destek olur.
              </p>
            </div>
            <div class="bg-white p-6 rounded-3xl shadow-lg border-4 border-sunshine-200">
              <p>
                🏠 Güvenli, sıcak ve çocuk dostu ortamımızda, küçük hastalarımızın kendilerini rahat hissetmeleri 
                ve oyun yoluyla iyileşme süreçlerini desteklemeyi amaçlıyoruz.
              </p>
            </div>
          </div>
          
          <div class="grid grid-cols-3 gap-4 pt-8">
            <div class="bg-gradient-to-br from-bubblegum-100 to-bubblegum-200 p-6 rounded-3xl text-center shadow-lg border-4 border-white hover:scale-105 transition-transform">
              <div class="text-2xl mb-2">⭐</div>
              <div class="text-4xl font-fun font-bold text-bubblegum-700 mb-2">10+</div>
              <div class="text-sm font-bold text-bubblegum-800">Yıl Deneyim</div>
            </div>
            <div class="bg-gradient-to-br from-mint-100 to-mint-200 p-6 rounded-3xl text-center shadow-lg border-4 border-white hover:scale-105 transition-transform">
              <div class="text-2xl mb-2">💝</div>
              <div class="text-4xl font-fun font-bold text-mint-700 mb-2">500+</div>
              <div class="text-sm font-bold text-mint-800">Mutlu Aile</div>
            </div>
            <div class="bg-gradient-to-br from-sunshine-100 to-sunshine-200 p-6 rounded-3xl text-center shadow-lg border-4 border-white hover:scale-105 transition-transform">
              <div class="text-2xl mb-2">🔒</div>
              <div class="text-4xl font-fun font-bold text-sunshine-700 mb-2">100%</div>
              <div class="text-sm font-bold text-sunshine-800">Gizlilik</div>
            </div>
          </div>
          
          <div class="pt-6">
            <a href="#iletisim" class="btn-primary">
              ✨ Bizimle İletişime Geçin
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>


