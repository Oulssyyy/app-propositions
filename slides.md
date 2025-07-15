---
theme: seriph
background: ../assets/estate.jpg
title: ステラーフォース向けアプリケーション提案
info: |
  ## ステラーフォース向けアプリケーション提案
  業務効率化とデジタル変革のための革新的なソリューション

class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
colorSchema: light
favicon: /assets/stellarforce.png
---
<div class="absolute inset-0 bg-white bg-opacity-80 pointer-events-none z-10 flex flex-col items-center justify-center">   
  <h1 
    class="text-4xl font-bold mb-4 text-black"
    v-motion
    :initial="{ y: -40, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 200, duration: 700 } }"
  >
    ステラーフォース向けアプリケーション提案
  </h1>
  <div 
    v-motion
    :initial="{ y: 50, opacity: 0 }"
    :enter="{ y: 0, opacity: 1, transition: { delay: 700, duration: 800 } }"
  >
    <h2 class="text-2xl text-gray-900">業務効率化とデジタル変革のための革新的なソリューション</h2>
  </div>
  <div 
    class="mt-8 flex justify-center"
    v-motion
    :initial="{ scale: 0.8, opacity: 0 }"
    :enter="{ scale: 1, opacity: 1, transition: { delay: 1200, duration: 600, type: 'spring' } }"
  >
    <div class="bg-white bg-opacity-90 rounded-xl p-2 shadow-lg">
      <img 
        src="/assets/stellarforce.png" 
        alt="Stellar Force" 
        class="h-16 w-auto drop-shadow-xl"
        v-motion
        :initial="{ rotateY: 90 }"
        :enter="{ rotateY: 0, transition: { delay: 1500, duration: 700 } }"
      />
    </div>
  </div>
</div>


<style>
h1 {
  background: linear-gradient(45deg, #0d1333 0%, #0d47a1 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  font-size: 3.5rem !important;
}

h2 {
  color: #0d47a1;
  font-size: 2rem !important;
}
</style>

---
src: ./pages/idea1-mail-automation.md
---

---
src: ./pages/idea2-property-management.md
---

---
src: ./pages/idea3-document-automation.md
---

---
src: ./pages/ai-features.md
---

---
src: ./pages/risks-conclusion.md
---