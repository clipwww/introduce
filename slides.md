---
theme: seriph
title: 簡爾廷 - 前端工程師
info: 面試自我介紹簡報
transition: slide-left
mdc: true
---

<script setup>
import { ref, onMounted } from 'vue'

const companyName = ref('')
const jobTitle = ref('')

onMounted(() => {
  const params = new URLSearchParams(window.location.search)
  companyName.value = params.get('company') || ''
  jobTitle.value = params.get('job') || ''
})
</script>

# 簡爾廷 <span class="text-2xl text-gray-400">David, Jian</span>

<div v-if="companyName || jobTitle" class="mt-6 text-lg">
應徵 <span v-if="companyName" class="text-blue-500 font-bold">{{ companyName || '【公司名稱】' }}</span> <span v-if="jobTitle" class="text-green-500 font-bold">{{ jobTitle || '【職缺名稱】' }}</span>
</div>



<div class="abs-br m-6 flex gap-2 text-sm opacity-50">
  <a href="https://clipwww.github.io/personal/" target="_blank">Personal Site</a>
  <span>・</span>
  <a href="https://github.com/clipwww" target="_blank">GitHub</a>
</div>

<!--
大家/各位/兩位好，我是簡爾廷，英文名字是 David。
-->

---

# 關於我

<div class="flex items-center gap-12">
<div class="whitespace-nowrap">
<div class="text-xs text-gray-500 mt-2">
東海大學資訊管理研究所 (2013-2015)<br>
東海大學資訊工程學系 (2009-2013)
</div>

<div class="mt-2 text-base leading-relaxed">

  **9 年以上** Web 開發經驗，專精於 <span class="font-bold text-[#41B883]">Vue.js</span> 生態系<br/>

  具備 **Node.js / TypeScript** 後端服務開發經驗<br/>

  熟悉從零到一建置**管理系統、會員平台**等服務型網站<br/>

  擁有**金流**與**第三方點數平台**串接經驗<br/>

  重視使用者體驗與程式碼品質，但保有彈性，不會固執己見<br/>
  
  積極有責任感，樂於主動協助團隊成員<br/>

  能夠獨立作業、解決問題，並持續自主學習


</div>
</div>

<div>
<img src="/profile.jpeg" class="w-48 h-48 mx-auto rounded-2xl" />
<div class="flex flex-wrap justify-center gap-3 mt-4">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:javascript.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:pinia.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:element.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:zod.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:graphql.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:nodejs-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-20 bg-white px-1 rounded" />
  <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:redis.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:git-icon.svg" class="w-10" />
</div>
</div>
</div>


<!--
我有 9 年以上 Web 開發經驗，主軸是 Vue.js 生態系，也能支援 Node.js 與 TypeScript 後端服務。
職涯中做過從零到一的平台建置，也做過長期維運與重構。
我特別熟悉金流與第三方點數整合，能在產品時程與品質之間取得平衡。
-->



---

# 工作經歷 — 阿爾伊 <span class="text-base text-gray-400 font-normal">（近 8 年）</span>

<div class="flex items-center gap-4 mt-2">
  <img :src="`${$base}rex-app.png`" class="w-14 h-14 rounded-xl" />
  <div>
    <div class="text-base">核心產品「<strong>RE·X 點數魔術師</strong>」— 點數整合應用平台</div>
    <div class="text-xs text-gray-400 mt-1">消費者可在合作店家進行交易獲得高額回饋點數，點數又可在下次消費折抵，並且還能夠綁定全家、HAPPYGO 點數來累積與折抵。</div>
  </div>
</div>

<div class="grid grid-cols-2 gap-4 mt-3">

<div>
  <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">Web 專案（主導 / 接手）</div>
  <div class="flex flex-col gap-1.5">
    <div class="border border-gray-200 rounded-lg px-2.5 py-1.5">
      <div class="flex items-center justify-between">
        <div class="font-bold text-[12px]">官方網站</div>
        <div class="flex items-center gap-1">
          <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-3.5" />
          <span class="text-[10px] text-gray-400">Express / vue-i18n</span>
        </div>
      </div>
      <div class="text-[10px] text-gray-500">將靜態網站以 Nuxt2 重構、Core Web Vitals 優化、多語系與 Deep Link。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-2.5 py-1.5">
      <div class="flex items-center justify-between">
        <div class="font-bold text-[12px]">BOSS 店家管理（Hybrid App）</div>
        <div class="flex items-center gap-1">
          <img src="https://api.iconify.design/logos:vue.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:vitejs.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:d3.svg" class="w-3.5" />
          <span class="text-[10px] text-gray-400">Sharp</span>
        </div>
      </div>
      <div class="text-[10px] text-gray-500">WebView 橋接、Vite 遷移、交易視覺化與廣宣物生成。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-2.5 py-1.5">
      <div class="flex items-center justify-between">
        <div class="font-bold text-[12px]">官方LINE@LIFF</div>
        <div class="flex items-center gap-1">
          <img src="https://api.iconify.design/logos:vue.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-3.5" />
          <span class="text-[10px] text-gray-400">LIFF SDK / html5-qrcode</span>
        </div>
      </div>
      <div class="text-[10px] text-gray-500">從零建置會員綁定、掃碼交易與行動支付整合。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-2.5 py-1.5">
      <div class="flex items-center justify-between">
        <div class="font-bold text-[12px]">市場開發系統</div>
        <div class="flex items-center gap-1">
          <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:element.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-4" />
          <span class="text-[10px] text-gray-400">Zod / Google Maps</span>
        </div>
      </div>
      <div class="text-[10px] text-gray-500">從零到一建置，處理表單驗證、地圖與藍新商家開通流程。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-2.5 py-1.5">
      <div class="flex items-center justify-between">
        <div class="font-bold text-[12px]">內部管理系統</div>
        <div class="flex items-center gap-1">
          <img src="https://api.iconify.design/logos:vue.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:vitejs.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-4" />
          <img src="https://api.iconify.design/logos:graphql.svg" class="w-3.5" />
        </div>
      </div>
      <div class="text-[10px] text-gray-500">接手維護並完成 Nuxt1→Vue/cli→Vite 建構遷移。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-2.5 py-1.5">
      <div class="flex items-center justify-between">
        <div class="font-bold text-[12px]">私有 Vue 共用組件</div>
        <div class="flex items-center gap-1">
          <img src="https://api.iconify.design/logos:vue.svg" class="w-3.5" />
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-4" />
        </div>
      </div>
      <div class="text-[10px] text-gray-500">封裝表單與金流元件，供多專案複用並降低導入成本。</div>
    </div>
  </div>
</div>

<div>
  <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">後端服務 / 內部工具</div>
  <div class="flex flex-col gap-2">
    <div class="border border-gray-200 rounded-lg px-3 py-2">
      <div class="flex items-center justify-between">
        <div class="font-bold text-sm">全家會員與點數服務</div>
        <div class="flex gap-1">
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-4" />
          <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-4" />
          <img src="https://api.iconify.design/logos:redis.svg" class="w-4" />
          <span class="text-[10px] text-gray-400">Express</span>
        </div>
      </div>
      <div class="text-[11px] text-gray-500 mt-1">串接全家平台 API，紀錄請求/回應，提供內部 RESTful API 服務。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2">
      <div class="flex items-center justify-between">
        <div class="font-bold text-sm">簽到活動服務 / 藍新商家申請</div>
        <div class="flex gap-1 items-center">
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-4" />
          <span class="text-[10px] text-gray-400">Express / Cron / SFTP</span>
        </div>
      </div>
      <div class="text-[11px] text-gray-500 mt-1">規劃簽到資料結構與排程推播；開發藍新補件上傳與回覆檔案定期拉取流程。</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2">
      <div class="flex items-center justify-between">
        <div class="font-bold text-sm">藍新交易查詢工具</div>
        <div class="flex gap-1 items-center">
          <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-4" />
          <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-4" />
          <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-4" />
          <span class="text-[10px] text-gray-400">Nuxt UI / Drizzle ORM</span>
        </div>
      </div>
      <div class="text-[11px] text-gray-500 mt-1">提供同事快速查詢交易狀態，並支援取消授權/退款等操作。</div>
    </div>
  </div>
</div>

</div>

<div class="flex items-center gap-4 mt-3 text-xs justify-center">
  <span>金流：TapPay / Stripe / 藍新</span>
  <span>第三方點數：全家 / HAPPYGO</span>
  <span>跨平台：Web / iOS / Android（WebView + JS Bridge）</span>
</div>

<!--
這是我待最久的一段經歷，在阿爾伊接近 8 年。
核心產品是 RE·X 點數魔術師，場景涵蓋交易、點數累積折抵與跨平台整合。
我在這裡從前端工程師一路做到資深前端工程師，參與前後台與後端服務的完整開發。
-->

---

# FunNow Group

<div class="text-sm text-gray-500 mt-1">核心產品「FunNow App」— 即時預訂享樂平台</div>

<div class="grid grid-cols-2 gap-6 mt-4">
<div>

### FunNow Manager Web

<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:pinia.svg" class="w-6" />
</div>

<div class="text-xs text-gray-500 mb-3">負責店家端平台的維護與新功能開發</div>

- **vue/cli → Vite** — 啟動速度 **30-60s → 1-2s**
- 導入 **TypeScript** — 強化可讀性與可維護性
- 新功能改寫 **Composition API** & Vuex → **Pinia**
- 與設計師協作重構**日期時間選擇器**組件

</div>
<div>

<div class="text-sm font-bold mt-2 mb-2">日期時間選擇器組件 Demo</div>

<div class="flex gap-1 mt-2">
<img src="https://hackmd.io/_uploads/HJrtQ2k4We.png" class="rounded shadow-lg" style="max-height: 140px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/S1Qs73JVbe.png" class="rounded shadow-lg" style="max-height: 140px; object-fit: contain;" />
</div>
<div class="flex gap-1 mt-1">
<img src="https://hackmd.io/_uploads/rJ1Tmh1NWx.png" class="rounded shadow-lg" style="max-height: 140px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/BJ9TX31Vbe.png" class="rounded shadow-lg" style="max-height: 140px; object-fit: contain;" />
</div>

</div>
</div>

<!--
在 FunNow，我主要負責店家端 Manager Web 的維護與新功能。
我主導 vue/cli 遷移到 Vite，把啟動速度從 30-60 秒降到 1-2 秒。
同時導入 TypeScript、Composition API 與 Pinia，改善長期維護性。
也與設計師協作重構日期時間選擇器，提升實際操作體驗。
-->


---

# 個人專案 - 個人記錄視覺化

<!-- <a href="https://clipwww.github.io/blog/2021/08/25/google-sheets/" class="text-blue-500 text-xs" target="_blank">文章紀錄</a> -->
紀錄自己進影廳看電影以及進球場看棒球的資料，並將其視覺化呈現

<div class="flex gap-2 mt-1 mb-2">
<img src="https://api.iconify.design/logos:vue.svg" class="w-6" />
<img src="https://api.iconify.design/logos:vitejs.svg" class="w-6" />
<img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-6" />
<img src="https://api.iconify.design/logos:d3.svg" class="w-6" />
<img src="https://api.iconify.design/logos:chartjs.svg" class="w-6" />
<img src="https://api.iconify.design/logos:leaflet.svg" class="w-18" />
</div>

- Google Sheets 作為資料庫
- D3.js, Chart.js 實作資料視覺化呈現
- Leaflet 實作地圖呈現球場位置

<div class="grid grid-cols-2 gap-6">
<div>

🎬 **電影院觀影紀錄**
- 場次/消費統計、影片版本/影城分佈
- 觀影時間熱力圖

<img src="https://hackmd.io/_uploads/HkOEeDmHbg.png" class="inline-block rounded shadow-lg mt-2 mr-1" style="max-height: 180px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/S1EdgwmS-e.png" class="inline-block rounded shadow-lg mt-2 mr-1" style="max-height: 180px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/S1FPgDXB-e.png" class="inline-block rounded shadow-lg mt-2" style="max-height: 180px; object-fit: contain;" />

</div>
<div>

⚾ **職棒入場紀錄**
- 觀賽統計、主場勝率
- 球場分佈圖

<img src="https://hackmd.io/_uploads/Bkutibx9-g.png" class="inline-block rounded shadow-lg mt-2 mr-1" style="max-height: 180px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/rystiWlqbl.png" class="inline-block rounded shadow-lg mt-2 mr-1" style="max-height: 180px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/H1RKiZeqWx.png" class="inline-block rounded shadow-lg mt-2 mr-1" style="max-height: 180px; object-fit: contain;" />

</div>
</div>



<!--
這是我持續維護的個人專案，用來記錄生活資料並做視覺化。
資料來源是 Google Sheets，前端用 Vue、D3、Chart.js 呈現。
專案主題是觀影與職棒進場紀錄，可以看到統計、熱點與地圖分佈。
它反映我在工作之外仍持續迭代產品與學習新技術。
-->


---
layout: two-cols
---

<div class="flex flex-col items-center justify-center h-full">


- **9 年以上** Web 開發經驗
- **專精 <span class="font-bold text-[#41B883]">Vue.js</span> 生態系**
- **後端服務開發經驗** - Node.js / TypeScript
- **從零到一設計並實作前端專案的經驗**
- **金流/第三方點數串接經驗**
- **團隊協作** - 積極主動負責，樂於溝通協調
- **獨立作業能力** - 自主學習，持續成長

</div>

::right::

<div class="flex flex-col items-center justify-center h-full">

<div class="text-6xl mb-6">🙇</div>

<h2 class="text-2xl font-bold">感謝聆聽</h2>

<div class="mt-6 text-gray-500 text-center">
📍 新北市, 台灣<br>
✉️ clipwww@gmail.com
</div>

<div class="mt-6 flex gap-3 text-sm">
  <a href="https://clipwww.github.io/personal/" target="_blank" class="text-blue-500 hover:underline">Personal Site</a>
  <span class="text-gray-300">|</span>
  <a href="https://github.com/clipwww" target="_blank" class="text-blue-500 hover:underline">GitHub</a>
  <!-- <span class="text-gray-300">|</span>
  <a href="https://clipwww.github.io/blog/" target="_blank" class="text-blue-500 hover:underline">Blog</a> -->
</div>

</div>

<!--
以上是我的詳細版自我介紹。
如果您想深入了解任一段經驗，我可以補充實作細節、踩坑與成果。
謝謝。
-->
