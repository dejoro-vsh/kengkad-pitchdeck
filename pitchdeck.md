---
theme: seriph
class: text-center hero-bg flex flex-col justify-center items-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: fade-out
colorSchema: dark
css: unocss
title: KengKad Enterprise Pitch Deck
routerMode: hash
fonts:
  sans: 'Prompt'
  serif: 'Prompt'
---

<style>
  .hero-bg {
    background-image: linear-gradient(rgba(11, 17, 32, 0.85), rgba(11, 17, 32, 0.95)), url('https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=1200&q=80');
    background-size: cover;
    background-position: center;
  }
  body {
    background-color: #0B1120;
    color: #F8FAFC;
  }
</style>

# <span class="text-white">Keng</span><span class="text-[#38BDF8]">Kad</span>

<div class="text-2xl mt-4 font-light text-gray-300 tracking-wide">
  Enterprise System Architects. เราเปลี่ยนเทคโนโลยีที่ซับซ้อน ให้เป็นกลไกขับเคลื่อนธุรกิจที่เสถียร ปลอดภัย และสร้างกำไร
</div>

<div class="mt-8 flex justify-center gap-6">
  <div class="px-4 py-2 rounded-lg bg-[#1E293B]/80 backdrop-blur-md border border-[#334155] shadow-xl">🚀 High-Performance</div>
  <div class="px-4 py-2 rounded-lg bg-[#1E293B]/80 backdrop-blur-md border border-[#334155] shadow-xl">💳 Payment Infra</div>
  <div class="px-4 py-2 rounded-lg bg-[#1E293B]/80 backdrop-blur-md border border-[#334155] shadow-xl">⚙️ Engine Logic</div>
</div>

<div class="absolute bottom-24 left-0 right-0 flex justify-center animate-bounce z-50">
  <div class="px-6 py-3 rounded-full bg-[#38BDF8] border border-[#38BDF8] text-[#0B1120] font-semibold cursor-pointer shadow-[0_0_20px_rgba(56,189,248,0.4)] backdrop-blur-sm hover:scale-105 transition-transform" @click="$nav.next">
    เริ่มต้นการนำเสนอ (คลิก) &rarr;
  </div>
</div>

<div class="absolute bottom-8 left-0 right-0 flex justify-center z-50">
  <div class="text-xs text-[#94A3B8] bg-black/50 px-4 py-1 rounded-full backdrop-blur-sm">
    คุณสามารถใช้ปุ่มลูกศร (ซ้าย-ขวา) บนคีย์บอร์ด หรือ Spacebar ในการเปลี่ยนหน้าได้
  </div>
</div>

<!-- Slide 2 -->
---
layout: two-cols
class: px-8 py-10
---

# <span class="text-[#38BDF8]">The Tech-Business Gap</span>

<h3 class="text-xl font-light text-gray-300 mb-8 leading-relaxed">
  <span class="font-bold text-white">90% ของ Startups & SME</span> สเกลระบบไม่ได้เพราะโครงสร้างซอฟต์แวร์เปราะบาง
</h3>

<div v-click class="mb-4 p-4 rounded-xl bg-red-900/20 border border-red-500/30 transition hover:bg-red-900/40">
  <div class="text-red-300 font-bold mb-1 flex items-center gap-2">💥 System Downtime</div>
  <div class="text-sm text-[#94A3B8]">ระบบล่มช่วง Peak Hour (เที่ยง/เย็น สำหรับร้านอาหาร)</div>
</div>

<div v-click class="mb-4 p-4 rounded-xl bg-orange-900/20 border border-orange-500/30 transition hover:bg-orange-900/40">
  <div class="text-orange-300 font-bold mb-1 flex items-center gap-2">💸 Security & Leakage</div>
  <div class="text-sm text-[#94A3B8]">การทุจริต เงินขาด และช่องโหว่ในระบบจ่ายเงิน</div>
</div>

<div v-click class="mb-4 p-4 rounded-xl bg-yellow-900/20 border border-yellow-500/30 transition hover:bg-yellow-900/40">
  <div class="text-yellow-300 font-bold mb-1 flex items-center gap-2">📈 High Infra Cost</div>
  <div class="text-sm text-[#94A3B8]">ค่าใช้จ่าย Cloud ที่สูงเกินจริงจากการจัดการทรัพยากรไม่ดี</div>
</div>

::right::

<div class="h-full flex flex-col justify-center items-center p-8 pl-12">
  <div v-click class="relative w-full aspect-square rounded-full flex items-center justify-center border-4 border-red-500/30 shadow-[0_0_50px_rgba(248,113,113,0.15)] bg-gradient-to-b from-red-900/20 to-transparent">
    <div class="text-center">
      <h2 class="text-6xl font-black text-transparent bg-clip-text bg-gradient-to-b from-red-400 to-red-600 mb-4 drop-shadow-lg">Loss</h2>
      <p class="text-lg text-[#94A3B8] max-w-[200px] mx-auto leading-tight">ทุกนาทีที่ระบบหยุดชะงัก คือเม็ดเงินของธุรกิจที่ปลิวหายไป</p>
    </div>
  </div>
</div>

<!-- Slide 3 -->
---
layout: default
class: px-12 py-10
---

# <span class="text-[#38BDF8]">Our Solution: Battle-Tested Infrastructure</span>

<p class="text-lg text-[#94A3B8] mb-8"><span class="text-white">Keng</span><span class="text-[#38BDF8]">Kad</span> ส่งมอบแพลตฟอร์มระดับ <span class="text-[#0B1120] bg-[#38BDF8] font-bold px-2 py-1 rounded">Enterprise-Grade</span> ที่เปิดใช้งานได้ทันที</p>

<div class="grid grid-cols-2 gap-6">
  <div v-click class="p-6 rounded-2xl bg-[#1E293B] border border-[#334155] hover:border-[#38BDF8] hover:shadow-[0_0_20px_rgba(56,189,248,0.2)] transition-all duration-300 group relative overflow-hidden">
    <div class="absolute -right-4 -top-4 text-7xl opacity-5 group-hover:scale-110 transition-transform">💳</div>
    <div class="text-3xl mb-3">💳</div>
    <h3 class="text-xl font-bold text-white mb-2">Payment & POS (HowToPay)</h3>
    <p class="text-sm text-[#94A3B8]">ระบบจัดการธุรกรรมและการขายหน้าร้านที่ปลอดภัยสูง</p>
  </div>
  
  <div v-click class="p-6 rounded-2xl bg-[#1E293B] border border-[#334155] hover:border-[#38BDF8] hover:shadow-[0_0_20px_rgba(56,189,248,0.2)] transition-all duration-300 group relative overflow-hidden">
    <div class="absolute -right-4 -top-4 text-7xl opacity-5 group-hover:scale-110 transition-transform">🔍</div>
    <div class="text-3xl mb-3">🔍</div>
    <h3 class="text-xl font-bold text-white mb-2">Search & Discovery</h3>
    <p class="text-sm text-[#94A3B8]">ระบบสืบค้นประสิทธิภาพสูง รองรับ Big Data (yopi.co.th)</p>
  </div>
  
  <div v-click class="p-6 rounded-2xl bg-[#1E293B] border border-[#334155] hover:border-[#38BDF8] hover:shadow-[0_0_20px_rgba(56,189,248,0.2)] transition-all duration-300 group relative overflow-hidden">
    <div class="absolute -right-4 -top-4 text-7xl opacity-5 group-hover:scale-110 transition-transform">⚛️</div>
    <div class="text-3xl mb-3">⚛️</div>
    <h3 class="text-xl font-bold text-white mb-2">AntiGravity Logic System</h3>
    <p class="text-sm text-[#94A3B8]">สถาปัตยกรรม File-Based Ownership ลดภาระฐานข้อมูล สเกลยืดหยุ่น</p>
  </div>
  
  <div v-click class="p-6 rounded-2xl bg-[#1E293B] border border-[#334155] hover:border-[#38BDF8] hover:shadow-[0_0_20px_rgba(56,189,248,0.2)] transition-all duration-300 group relative overflow-hidden">
    <div class="absolute -right-4 -top-4 text-7xl opacity-5 group-hover:scale-110 transition-transform">🛡️</div>
    <div class="text-3xl mb-3">🛡️</div>
    <h3 class="text-xl font-bold text-white mb-2">DevSecOps Automation</h3>
    <p class="text-sm text-[#94A3B8]">รันบน Proxmox Cluster + GitLab CI/CD มั่นใจเสถียรภาพ 100%</p>
  </div>
</div>

<!-- Slide 4 -->
---
layout: center
class: px-12 text-center
---

# <span class="text-[#38BDF8]">Market Opportunity: Food & Hotels SME</span>

<p class="text-[#94A3B8] mb-10">มูลค่าตลาดซอฟต์แวร์และการจัดการธุรกรรมในประเทศไทย (Tech Spend Only)</p>

<div class="relative w-full max-w-3xl mx-auto flex flex-col">
  <div v-click class="p-6 rounded-t-3xl bg-[#1E293B] border-t border-x border-[#334155] shadow-2xl backdrop-blur-md">
    <div class="text-[#38BDF8] text-sm font-bold tracking-widest uppercase">Total Market (TAM)</div>
    <div class="text-4xl font-black text-white my-2">6,600 ล้านบาท / ปี</div>
    <div class="text-sm text-[#94A3B8]">550,000 ร้านอาหาร & โรงแรม SME</div>
  </div>
  
  <div v-click class="p-6 bg-[#0F172A] border-x border-[#334155] shadow-2xl backdrop-blur-md">
    <div class="text-cyan-300 text-sm font-bold tracking-widest uppercase">Serviceable Market (SAM)</div>
    <div class="text-3xl font-black text-white my-2">1,320 ล้านบาท / ปี</div>
    <div class="text-sm text-[#94A3B8]">110,000 ราย ที่เป็นกลุ่ม Premium & High-Volume</div>
  </div>
  
  <div v-click class="p-8 rounded-b-3xl bg-gradient-to-b from-[#38BDF8] to-blue-800 border border-[#38BDF8] shadow-[0_15px_40px_rgba(56,189,248,0.3)] backdrop-blur-md">
    <div class="text-blue-100 text-sm font-bold tracking-widest uppercase">3-Year Goal (SOM)</div>
    <div class="text-5xl font-black text-white my-2">39.6 ล้านบาท ARR</div>
    <div class="text-sm text-blue-100 font-medium">ยึดครอง 3% ของ SAM = 3,300 ราย ใน 36 เดือน</div>
  </div>
</div>

<!-- Slide 5 -->
---
layout: default
class: px-12 py-10
---

# <span class="text-[#38BDF8]">Monetization Architecture</span>

<p class="text-[#94A3B8] mb-10">โมเดลการสร้างรายได้ที่จับต้องได้จริง (How We Make Money)</p>

<div class="space-y-6">
  <div v-click class="flex items-center gap-6 p-5 rounded-2xl bg-[#1E293B]/50 border border-[#334155] hover:bg-[#1E293B] hover:-translate-y-1 transition-all duration-300 backdrop-blur-sm group">
    <div class="w-16 h-16 rounded-full bg-[#38BDF8]/20 flex items-center justify-center text-[#38BDF8] text-2xl shrink-0 group-hover:scale-110 transition-transform shadow-[0_0_15px_rgba(56,189,248,0.1)]">01</div>
    <div>
      <h3 class="text-xl font-bold text-white">Transaction-Based Fee (Take Rate)</h3>
      <p class="text-[#94A3B8] mt-1">เก็บค่าธรรมเนียม <span class="text-[#38BDF8] font-bold">0.5% - 1.5%</span> จากทุกยอดธุรกรรมที่ผ่านระบบ HowToPay Gateway</p>
    </div>
  </div>

  <div v-click class="flex items-center gap-6 p-5 rounded-2xl bg-[#1E293B]/50 border border-[#334155] hover:bg-[#1E293B] hover:-translate-y-1 transition-all duration-300 backdrop-blur-sm group">
    <div class="w-16 h-16 rounded-full bg-[#38BDF8]/20 flex items-center justify-center text-[#38BDF8] text-2xl shrink-0 group-hover:scale-110 transition-transform shadow-[0_0_15px_rgba(56,189,248,0.1)]">02</div>
    <div>
      <h3 class="text-xl font-bold text-white">SaaS Subscription & Premium Modules</h3>
      <p class="text-[#94A3B8] mt-1">ค่าบริการรายเดือน <span class="text-[#38BDF8] font-bold">590 - 1,190 บาท</span> สำหรับฟีเจอร์ระดับสูง (ควบคุมคลังสินค้าข้ามสาขา, ระบบจองห้องพัก)</p>
    </div>
  </div>

  <div v-click class="flex items-center gap-6 p-5 rounded-2xl bg-[#1E293B]/50 border border-[#334155] hover:bg-[#1E293B] hover:-translate-y-1 transition-all duration-300 backdrop-blur-sm group">
    <div class="w-16 h-16 rounded-full bg-[#38BDF8]/20 flex items-center justify-center text-[#38BDF8] text-2xl shrink-0 group-hover:scale-110 transition-transform shadow-[0_0_15px_rgba(56,189,248,0.1)]">03</div>
    <div>
      <h3 class="text-xl font-bold text-white">Data & Infrastructure Licensing</h3>
      <p class="text-[#94A3B8] mt-1">รายได้จากการปรับแต่งระบบระดับ Enterprise และการเชื่อมต่อผ่าน API สำหรับองค์กรขนาดใหญ่</p>
    </div>
  </div>
</div>

<!-- Slide 6 -->
---
layout: default
class: px-12 py-10
---

# <span class="text-[#38BDF8]">Why KengKad Wins?</span>

<p class="text-[#94A3B8] mb-8">เปรียบเทียบ Business Value กับตลาดปัจจุบัน</p>

<div class="overflow-hidden rounded-2xl border border-[#334155] shadow-2xl">
  <table class="w-full text-left border-collapse">
    <thead>
      <tr class="bg-[#1E293B] text-slate-300">
        <th class="p-4 font-bold border-b border-[#334155] w-1/4">คุณสมบัติ</th>
        <th class="p-4 font-bold border-b border-[#334155] w-1/3">แพลตฟอร์มทั่วไป</th>
        <th class="p-4 font-bold border-b border-[#334155] text-[#38BDF8] bg-[#38BDF8]/10 w-5/12">KengKad Engine</th>
      </tr>
    </thead>
    <tbody class="text-sm">
      <tr v-click class="bg-[#0B1120] hover:bg-[#1E293B] transition group">
        <td class="p-4 border-b border-[#1E293B] font-bold text-white group-hover:text-[#38BDF8] transition">เสถียรภาพ (Uptime)</td>
        <td class="p-4 border-b border-[#1E293B] text-[#94A3B8]">มีความเสี่ยงล่มเมื่อ Traffic หนาแน่น</td>
        <td class="p-4 border-b border-[#1E293B] text-[#38BDF8] bg-[#38BDF8]/5 font-bold flex items-center gap-2">⭐ Zero Downtime (Clustered)</td>
      </tr>
      <tr v-click class="bg-[#0B1120] hover:bg-[#1E293B] transition group">
        <td class="p-4 border-b border-[#1E293B] font-bold text-white group-hover:text-[#38BDF8] transition">ความปลอดภัย</td>
        <td class="p-4 border-b border-[#1E293B] text-[#94A3B8]">พัฒนาแบบเร่งรีบ มักมีช่องโหว่</td>
        <td class="p-4 border-b border-[#1E293B] text-[#38BDF8] bg-[#38BDF8]/5 font-bold flex items-center gap-2">🛡️ Security-First (มาตรฐานรัฐ)</td>
      </tr>
      <tr v-click class="bg-[#0B1120] hover:bg-[#1E293B] transition group">
        <td class="p-4 border-b border-[#1E293B] font-bold text-white group-hover:text-[#38BDF8] transition">ความเร็วในการสเกล</td>
        <td class="p-4 border-b border-[#1E293B] text-[#94A3B8]">ต้องเขียนโค้ดใหม่เกือบทั้งหมด</td>
        <td class="p-4 border-b border-[#1E293B] text-[#38BDF8] bg-[#38BDF8]/5 font-bold flex items-center gap-2">⚡ Plug-and-Play Architecture</td>
      </tr>
      <tr v-click class="bg-[#0B1120] hover:bg-[#1E293B] transition group">
        <td class="p-4 font-bold text-white group-hover:text-[#38BDF8] transition">ต้นทุน Infra</td>
        <td class="p-4 text-[#94A3B8]">สูงตามปริมาณ User (Cloud-Native แพง)</td>
        <td class="p-4 text-[#38BDF8] bg-[#38BDF8]/5 font-bold flex items-center gap-2">💰 Optimized Core ประหยัดคุ้มค่า</td>
      </tr>
    </tbody>
  </table>
</div>

<!-- Slide 7 -->
---
layout: center
class: px-12 text-center
---

# <span class="text-[#38BDF8]">The KengKad Task Force</span>

<p class="text-[#94A3B8] mb-12">ทีมนักรบโปรดักชันที่ส่งมอบงานได้จริง (10+ Years Experience)</p>

<div class="grid grid-cols-4 gap-4">
  <div v-click class="flex flex-col items-center group cursor-default">
    <div class="w-24 h-24 rounded-full bg-[#1E293B] p-1 mb-4 shadow-lg border border-[#334155] group-hover:border-[#38BDF8] group-hover:scale-110 group-hover:shadow-[0_0_20px_rgba(56,189,248,0.3)] transition-all duration-300">
      <div class="w-full h-full rounded-full bg-[#0B1120] flex items-center justify-center text-3xl">👨‍💻</div>
    </div>
    <h3 class="font-bold text-white group-hover:text-[#38BDF8] transition">Vishnu (Nu)</h3>
    <p class="text-xs text-[#38BDF8] font-bold mt-1">Architect / Lead</p>
    <p class="text-xs text-[#94A3B8] mt-2 text-center">Infrastructure & DevSecOps</p>
  </div>
  
  <div v-click class="flex flex-col items-center group cursor-default">
    <div class="w-24 h-24 rounded-full bg-[#1E293B] p-1 mb-4 shadow-lg border border-[#334155] group-hover:border-[#38BDF8] group-hover:scale-110 group-hover:shadow-[0_0_20px_rgba(56,189,248,0.3)] transition-all duration-300">
      <div class="w-full h-full rounded-full bg-[#0B1120] flex items-center justify-center text-3xl">⚙️</div>
    </div>
    <h3 class="font-bold text-white group-hover:text-[#38BDF8] transition">Patanapon</h3>
    <p class="text-xs text-[#38BDF8] font-bold mt-1">DevOps / Infra</p>
    <p class="text-xs text-[#94A3B8] mt-2 text-center">Server Stability & AI</p>
  </div>
  
  <div v-click class="flex flex-col items-center group cursor-default">
    <div class="w-24 h-24 rounded-full bg-[#1E293B] p-1 mb-4 shadow-lg border border-[#334155] group-hover:border-[#38BDF8] group-hover:scale-110 group-hover:shadow-[0_0_20px_rgba(56,189,248,0.3)] transition-all duration-300">
      <div class="w-full h-full rounded-full bg-[#0B1120] flex items-center justify-center text-3xl">🧠</div>
    </div>
    <h3 class="font-bold text-white group-hover:text-[#38BDF8] transition">Yo</h3>
    <p class="text-xs text-[#38BDF8] font-bold mt-1">Backend / Systems</p>
    <p class="text-xs text-[#94A3B8] mt-2 text-center">Business Logic & Database</p>
  </div>
  
  <div v-click class="flex flex-col items-center group cursor-default">
    <div class="w-24 h-24 rounded-full bg-[#1E293B] p-1 mb-4 shadow-lg border border-[#334155] group-hover:border-[#38BDF8] group-hover:scale-110 group-hover:shadow-[0_0_20px_rgba(56,189,248,0.3)] transition-all duration-300">
      <div class="w-full h-full rounded-full bg-[#0B1120] flex items-center justify-center text-3xl">📱</div>
    </div>
    <h3 class="font-bold text-white group-hover:text-[#38BDF8] transition">Poramet (Nine)</h3>
    <p class="text-xs text-[#38BDF8] font-bold mt-1">Mobile / Product</p>
    <p class="text-xs text-[#94A3B8] mt-2 text-center">UX/UI & Application</p>
  </div>
</div>

<!-- Slide 8 -->
---
layout: center
class: text-center hero-bg
---

<div class="bg-[#0B1120]/90 p-12 rounded-3xl backdrop-blur-md border border-[#334155] shadow-[0_0_50px_rgba(0,0,0,0.5)]">
  <h1 class="text-4xl font-black mb-6 leading-relaxed">
    ยกระดับระบบหลังบ้าน<br/>ให้กลายเป็น <span class="text-[#38BDF8]">"เครื่องจักรสร้างรายได้"</span>
  </h1>
  
  <p class="text-lg text-[#94A3B8] mb-10 font-light">
    พร้อมออกแบบโครงสร้างพื้นฐานเพื่อสเกลธุรกิจของคุณให้เติบโตแบบไร้ขีดจำกัด
  </p>
  
  <div class="flex justify-center gap-8 text-lg">
    <a href="mailto:vishnu@kengkad.com" class="flex items-center gap-3 bg-[#38BDF8] px-8 py-4 rounded-full hover:bg-[#0EA5E9] hover:scale-105 transition-all cursor-pointer border border-[#38BDF8] text-[#0F172A] font-semibold">
      <span>ติดต่อนัดหมายประเมินระบบธุรกิจ</span>
    </a>
  </div>
</div>