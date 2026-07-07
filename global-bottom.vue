<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute bottom-0 left-0 right-0 p-4 flex justify-between items-center text-sm text-[#F8FAFC] z-50 pointer-events-none"
  >
    <!-- Left side branding -->
    <div class="flex items-center gap-2 opacity-90">
      <span class="font-bold tracking-widest text-lg"><span class="text-white">Keng</span><span class="text-[#38BDF8]">Kad</span></span>
    </div>
    
    <!-- Navigation Buttons -->
    <div class="flex gap-4 pointer-events-auto items-center bg-[#1E293B]/90 backdrop-blur-md px-4 py-2 rounded-full border border-[#334155] shadow-xl">
      <button 
        @click="$nav.prev" 
        class="px-3 py-1 rounded bg-[#0B1120] text-[#94A3B8] hover:text-white transition flex items-center gap-1 cursor-pointer border border-[#334155]"
        :class="{ 'opacity-30 pointer-events-none': $nav.currentPage === 1 }"
        title="หน้าก่อนหน้า"
      >
        &larr; กลับ
      </button>
      
      <span class="font-mono text-[#94A3B8]">{{ $nav.currentPage }} / {{ $nav.total }}</span>
      
      <button 
        @click="$nav.next" 
        class="px-4 py-1 rounded bg-[#38BDF8] hover:bg-[#0EA5E9] text-[#0F172A] font-semibold transition shadow-[0_0_10px_rgba(56,189,248,0.3)] flex items-center gap-1 cursor-pointer"
        :class="{ 'opacity-30 pointer-events-none': $nav.currentPage === $nav.total }"
        title="หน้าถัดไป"
      >
        ถัดไป &rarr;
      </button>
    </div>
  </footer>
</template>
