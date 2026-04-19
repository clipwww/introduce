---
theme: seriph
title: 簡爾廷 - 前端工程師（詳細版）
info: 面試自我介紹簡報 - 詳細版
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
各位好，我是簡爾廷，英文名字是 David。
這份是詳細版自我介紹，我會用幾個代表專案說明我的經驗與能貢獻的價值。
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
<!-- <img src="./profile.jpeg" class="w-48 h-48 mx-auto rounded-2xl" /> -->
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

<div class="grid grid-cols-2 gap-6 mt-4">

<div>
  <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">Web 專案</div>
  <div class="flex flex-col gap-2">
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-28">官方網站</div>
      <div class="text-xs text-gray-400">Nuxt 2 SSR</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-28">BOSS 店家管理</div>
      <div class="text-xs text-gray-400"> Hybrid App · Vue 2.7 · Vite</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-28">官方LINE@LIFF</div>
      <div class="text-xs text-gray-400">Vue 3 · LIFF SDK</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-28">市場開發系統</div>
      <div class="text-xs text-gray-400">Nuxt 2 · ElementUI</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-28">內部管理系統</div>
      <div class="text-xs text-gray-400">Vue 2.7 · Vite · ElementUI · GraphQL</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-28">Vue 共用組件</div>
      <div class="text-xs text-gray-400">Vue 2 / 3 · 私有 npm</div>
    </div>
  </div>
</div>

<div>
  <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">後端服務 / 內部工具</div>
  <div class="flex flex-col gap-2">
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-32">全家會員與點數服務</div>
      <div class="text-xs text-gray-400">TypeScript · Express · MySQL · Redis</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-32">簽到活動服務</div>
      <div class="text-xs text-gray-400">TypeScript · Express · MySQL · Redis · Cron</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-32">藍新商家申請服務</div>
      <div class="text-xs text-gray-400">TypeScript · Express · MySQL · SFTP · Cron</div>
    </div>
    <div class="border border-gray-200 rounded-lg px-3 py-2 flex items-center gap-3">
      <div class="font-bold text-sm w-32">藍新交易查詢工具</div>
      <div class="text-xs text-gray-400">Nuxt4 · NuxtUI</div>
    </div>
  </div>
</div>

</div>

<div class="flex items-center gap-6 mt-3 text-sm justify-center">
  <span>金流串接：TapPay / Stripe / 藍新</span>
  <span>第三方點數串接：全家 / HAPPYGO</span>
</div>

<!--
這是我待最久的一段經歷，在阿爾伊接近 8 年。
核心產品是 RE·X 點數魔術師，場景涵蓋交易、點數累積折抵與跨平台整合。
我在這裡從前端工程師一路做到資深前端工程師，參與前後台與後端服務的完整開發。
-->

---

# RE·X 官方網站

<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:sass.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-14 bg-white px-1 rounded" />
</div>

<div class="text-sm text-gray-500 mb-3">官方形象網站，提供平台介紹、合作店家列表、App 下載及聯絡客服等資訊，並支援多地區與多語系。<br/>行銷活動以及 App 內的 WebView 頁面也由此專案提供。</div>

擔任主要開發者，負責專案的架構設計與開發<br/>
將第一版靜態 Html 的官網重構為 Nuxt 2 架構

- 提升 **Core Web Vitals**（LCP / FID / CLS）至良好等級
  - Lazy Loading、Nuxt Image 延遲圖片載入與圖片壓縮
  - LRU Cache 緩存靜態資料
  - Lazy Hydration 延遲非必要互動水合
  - 設計 Skeleton Loading 減少畫面偏移提升使用者體驗
- **多地區多語系** — 設計並實作 vue-i18n 架構，支援台灣 / 新加坡地區與繁中 / 簡中 / 英文語系
- **SEO** — 動態 Sitemap、Meta Tags、社群分享 OG Tags
- **Express 自訂路由** — 行銷短網址、App Deep Link 處理

<!--
RE·X 官方網站是公司對外的主要入口，我擔任主要開發者。
為了 SEO 與首屏體驗，我把第一版靜態網站重構成 Nuxt 2 SSR。
並導入快取、延遲載入與延遲水合，讓 Core Web Vitals 穩定在良好區間。
另外也負責多地區多語系、行銷短網址與 App Deep Link 的路由設計。
-->

---
layout: two-cols
---

# BOSS 店家管理系統

<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-14 bg-white px-1 rounded" />
  <img src="https://api.iconify.design/logos:d3.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-7" />
</div>

<div class="text-sm text-gray-500 mb-3">店家端後台管理系統，Hybrid App 形式同時支援 iOS、Android 與網頁，提供店家訂單查詢、交易分析、請款等功能。</div>

- **Hybrid App** — 處理 Web 與 Native App 溝通
- **Vue/cli → Vite** — 大幅提升開發啟動速度
- 與同事協作用 **D3.js** 實作交易資料視覺化（訂單分析、會員分析）
- 規劃設計與實作廣宣物下載功能
  - 內部管理系統 CRUD 表單，提供同事管理廣宣物資料
  - 店家端使用 `Sharp` 帶入推薦碼與文案生成結帳立牌與行銷廣宣物
- 串接 TapPay, Stripe 實作台灣/新加坡店家加值功能

::right::

<div class="pl-4 pt-10 text-center">

```mermaid {scale: 0.8}
graph TD
    subgraph BOSS 店家管理系統
      iOS[iOS<br/>Native 殼]
      Android[Android<br/>Native 殼]
      Web[瀏覽器]
      APP
    end
  
    iOS <-->|JS Bridge| APP[Web<br/>Vue 2.7 + Vite + Express]
    Android <-->|JS Bridge| APP
    Web <--> APP

    APP <-->|Proxy| API[RE·X API]

    style APP fill:#41B883,color:#fff
    style API fill:#3B82F6,color:#fff
```



</div>

<!--
這個專案是一份程式碼同時支援 iOS、Android 與 Web 的 Hybrid App。
我負責 Web 與 Native 之間的橋接整合，也主導 Vue/cli 遷移到 Vite。
功能面包含 D3 交易視覺化、廣宣物產生，以及 TapPay、Stripe 的金流整合。
其中 TapPay 也被我封裝成共用組件，供其他專案重用。
-->

---
layout: two-cols
---

# 內部系統

<div>

### 市場開發系統
<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:element.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:zod.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:google-maps.svg" class="w-4" />
</div>

<div class="text-xs text-gray-500 mb-2">市場開發業務系統，提供市場部業務與在地合作夥伴進行店家開發功能，支援線上填寫表單、上傳檔案以及線上付款，能夠快速導入店家資料與開通藍新金流收款。</div>

擔任主要開發者，負責專案從零到一的架構設計與開發

- 使用 ElementUI 根據需求欄位設計表單
- Zod 實作欄位之間連動的邏輯以及驗證
- **Google Maps API** 座標抓取與英文地址自動補全
- 證件**浮水印**處理 + **GCS** 加密上傳，確保資料安全
- 串接藍新金流**商家開通**流程

</div>

::right::

<div class="pl-4 pt-12">

### Admin 內部管理系統
<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:element.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:graphql.svg" class="w-6" />
</div>

<div class="text-xs text-gray-500 mb-2">依權限控管提供各部門使用的內部管理系統</div>

接手為主要維護、開發者

- **Nuxt1 → Vue/cli → Vite** 兩次建構程式遷移，大幅提升啟動與熱重載速度
- Apollo Client 串接 **GraphQL** API
- 依需求設計實作 **CRUD** 表單功能
- 建立共用組件庫（表單、表格、Modal），快速應對需求

</div>

<!--
左邊的市場開發系統是我從零到一建置的專案。
重點在複雜表單、地圖地址補全、文件安全上傳與藍新商家開通流程串接。

右邊是多部門共用的 Admin 系統，我是主要維護與開發者。
這個專案做過兩次建構遷移，也同步整理共用組件與 GraphQL 串接流程。
最終目標是提高團隊交付速度與維護效率。
-->

---

# LINE LIFF 應用程式

<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-14 bg-white px-1 rounded" />
</div>

<div class="text-sm text-gray-500 mb-3">LINE Front-end Framework（LIFF）應用，提供會員可透過官方 LINE@ 的圖文選單開啟應用<br/>進行帳號綁定、查看點數、掃碼交易與行動支付。由我從零到一設計與開發</div>

<div class="grid grid-cols-2 gap-8">
<div>

- **LINE LIFF SDK** 實作會員LINE帳號綁定
- **html5-qrcode** 實作相機掃碼交易
  <div class="text-xs text-gray-400">應對當時 LIFF SDK 部分裝置不支援掃碼</div>
- 串接金流藍新**嵌入式信用卡支付** 
  - 符合 PCI DSS 安全標準，只會取得 Token 不會接觸到卡片敏感資訊
- 實作 **Apple Pay on Web** 與 **Google Pay on Web**


</div>
<div>

<div class="flex gap-2 justify-center">
<img src="https://hackmd.io/_uploads/SJk8nhl4We.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/SJ3wBpgV-l.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/SkE6t6JN-l.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/SyRvEpeE-g.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
</div>

</div>
</div>

<!--
這個 LIFF 應用是 RE·X 在 LINE 生態中的核心交易入口，由我從零到一設計與開發。
我負責會員綁定、掃碼交易、與藍新支付流程的整合。
在支付場景上，陸續落地 Apple Pay on Web、Google Pay on Web 與嵌入式信用卡支付。
同時把可重用的金流邏輯封裝成共用組件，降低後續專案接入成本。
-->

---

# 後端服務與內部工具

<div class="text-sm text-gray-500 mb-3">除了前端專案，也負責以下後端服務的開發</div>

<div class="grid grid-cols-2 gap-4">

<div class="border border-gray-200 rounded-lg p-4">
  <div class="font-bold mb-1">全家會員與點數服務</div>
  <div class="flex gap-1 mb-2">
    <img src="https://api.iconify.design/logos:express.svg" class="w-10 bg-white px-1 rounded" />
    <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:redis.svg" class="w-5" />
  </div>
  <div class="text-sm mt-3">串接全家會員與點數平台 API，紀錄每筆請求/回應<br/>以 RESTful API 提供內部專案串接使用</div>
</div>

<div class="border border-gray-200 rounded-lg p-4">
  <div class="font-bold mb-1">簽到活動服務</div>
  <div class="flex gap-1 mb-2">
    <img src="https://api.iconify.design/logos:express.svg" class="w-10 bg-white px-1 rounded" />
    <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:redis.svg" class="w-5" />
    <span class="text-xs text-gray-400 self-center">Cron</span>
  </div>
  <div class="text-sm mt-3">規劃 API 路由與資料庫結構<br/>排程檢查連續簽到狀態 & 發出提醒推播通知</div>
</div>

<div class="border border-gray-200 rounded-lg p-4">
  <div class="font-bold mb-1">藍新金流商家申請服務</div>
  <div class="flex gap-1 mb-2">
    <img src="https://api.iconify.design/logos:express.svg" class="w-10 bg-white px-1 rounded" />
    <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-5" />
    <span class="text-xs text-gray-400 self-center">ssh2-sftp-client · Cron</span>
  </div>
  <div class="text-sm mt-3">負責開發 SFTP 補件上傳功能，將商家申請所需的檔案上傳至藍新金流指定 SFTP 伺服器，並排程定期拉取回覆檔案</div>
</div>

<div class="border border-gray-200 rounded-lg p-4">
  <div class="font-bold mb-1">藍新金流交易查詢工具</div>
  <div class="flex gap-1 mb-2">
    <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-5" />
    <span class="text-xs text-gray-400 self-center">Nuxt UI · Drizzle ORM</span>
  </div>
  <div class="text-sm mt-3">查詢交易狀態、取消授權/退款<br/>核心 API Service 手寫，UI 與操作流程使用 <strong>AI Agent</strong> 規劃生成</div>
</div>

</div>

<!--
除了前端，我也實際負責多個後端服務。
像是全家會員與點數串接、簽到活動排程、藍新商家申請 SFTP 流程，都是我主導開發。
另外藍新交易查詢工具則是核心 API 由我手寫，前台流程用 AI Agent 快速生成。
這段經驗讓我在前後端協作時更能快速定位與解決問題。
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
