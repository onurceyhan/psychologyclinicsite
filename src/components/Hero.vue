<template>
  <section class="pt-32 pb-20 px-6 relative overflow-hidden">
    <!-- Decorative blobs -->
    <div class="cute-blob w-96 h-96 bg-bubblegum-300 -top-48 -left-48"></div>
    <div class="cute-blob w-80 h-80 bg-sunshine-300 top-20 right-0"></div>
    <div class="cute-blob w-72 h-72 bg-mint-300 bottom-0 left-1/4"></div>
    
    <div class="max-w-7xl mx-auto relative z-10">
      <div class="bg-gradient-to-br from-bubblegum-100 via-sunshine-50 to-mint-100 rounded-[3rem] overflow-hidden shadow-2xl border-8 border-white relative">
        <!-- Decorative stars -->
        <div class="absolute top-8 right-8 text-6xl animate-bounce-slow">⭐</div>
        <div class="absolute bottom-8 left-8 text-5xl animate-wiggle">🌟</div>
        <div class="absolute top-1/2 left-12 text-4xl animate-pulse">💫</div>
        
        <div class="grid md:grid-cols-2 gap-8 items-center">
          <!-- Left Content -->
          <div class="p-8 md:p-16 space-y-8 relative z-10">
            <div class="inline-block">
              <h1 class="text-6xl md:text-7xl font-fun font-bold mb-4 leading-tight">
                <span class="bg-gradient-to-r from-bubblegum-500 to-bubblegum-600 bg-clip-text text-transparent">
                  Uysal
                </span>
                <span class="inline-block animate-float text-6xl ml-3">✨</span>
              </h1>
              <h1 class="text-6xl md:text-7xl font-fun font-bold leading-tight">
                <span class="bg-gradient-to-r from-sunshine-500 via-peach-400 to-bubblegum-500 bg-clip-text text-transparent">
                  Psikolog Kliniği
                </span>
              </h1>
            </div>
            
            <p class="text-xl md:text-2xl text-gray-700 leading-relaxed max-w-md font-medium">
              🌈 Çocuklarınız için profesyonel ve sevgi dolu 
              <span class="text-bubblegum-600 font-bold">oyun terapisi</span> hizmeti! 
            </p>
            
            <div class="flex flex-wrap gap-4 pt-4">
              <a href="#oyun-terapisi" class="btn-primary inline-flex items-center gap-2">
                <span class="text-2xl">🎨</span>
                Oyun Terapisi
              </a>
              <a href="#iletisim" class="btn-secondary inline-flex items-center gap-2">
                <span class="text-2xl">📞</span>
                Hemen Ara
              </a>
            </div>
            
            <!-- Fun badges -->
            <div class="flex flex-wrap gap-3 pt-6">
              <span class="px-4 py-2 bg-white rounded-full text-sm font-bold text-bubblegum-600 shadow-lg border-2 border-bubblegum-200">
                ⭐ 10+ Yıl Deneyim
              </span>
              <span class="px-4 py-2 bg-white rounded-full text-sm font-bold text-mint-600 shadow-lg border-2 border-mint-200">
                💝 500+ Mutlu Aile
              </span>
            </div>
          </div>
          
          <!-- Right Image -->
          <div class="relative h-[450px] md:h-[600px] group">
            <div class="absolute inset-0 bg-gradient-to-br from-bubblegum-300 to-sunshine-300 rounded-3xl transform rotate-3 group-hover:rotate-6 transition-transform"></div>
            <img 
              src="https://images.unsplash.com/photo-1503454537195-1dcabb73ffb9?w=800&q=80" 
              alt="Therapist with child"
              class="absolute inset-4 w-[calc(100%-2rem)] h-[calc(100%-2rem)] object-cover rounded-3xl shadow-2xl"
            />
            <!-- Cute floating elements -->
            <div class="absolute -top-6 -right-6 text-6xl animate-bounce-slow">🎈</div>
            <div class="absolute -bottom-6 -left-6 text-6xl animate-wiggle">🧸</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

