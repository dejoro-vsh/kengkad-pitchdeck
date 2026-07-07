<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute bottom-0 left-0 right-0 p-4 flex justify-between items-center text-sm text-gray-300 z-50 pointer-events-none"
  >
    <!-- Left side branding -->
    <div class="flex items-center gap-2 opacity-60">
      <span class="font-bold tracking-widest uppercase text-xs">KengKad Enterprise System</span>
    </div>
    
    <!-- Navigation Buttons -->
    <div class="flex gap-4 pointer-events-auto items-center bg-black/40 backdrop-blur-md px-4 py-2 rounded-full border border-white/10 shadow-xl">
      <button 
        @click="$nav.prev" 
        class="px-3 py-1 rounded bg-white/10 hover:bg-white/20 transition flex items-center gap-1 cursor-pointer"
        :class="{ 'opacity-30 pointer-events-none': $nav.currentPage === 1 }"
        title="หน้าก่อนหน้า"
      >
        &larr; กลับ
      </button>
      
      <span class="font-mono">{{ $nav.currentPage }} / {{ $nav.total }}</span>
      
      <button 
        @click="$nav.next" 
        class="px-4 py-1 rounded bg-gradient-to-r from-blue-600 to-cyan-500 hover:from-blue-500 hover:to-cyan-400 text-white transition shadow-[0_0_10px_rgba(37,99,235,0.5)] flex items-center gap-1 cursor-pointer"
        :class="{ 'opacity-30 pointer-events-none': $nav.currentPage === $nav.total }"
        title="หน้าถัดไป"
      >
        ถัดไป &rarr;
      </button>
    </div>
  </footer>
</template>
