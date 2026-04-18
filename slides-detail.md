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
大家/各位/兩位好，我是簡爾廷，英文名字是 David。
-->

---

# 關於我

<div class="flex items-center gap-8">
<div>
<div class="text-xs text-gray-500 mt-2">
東海大學資訊管理研究所 (2013-2015)<br>
東海大學資訊工程學系 (2009-2013)
</div>

<div class="mt-2 text-base leading-relaxed">

  擁有 **9 年以上**網站與網站應用程式開發經驗的經驗的前端工程師，專精於 <span class="font-bold text-[#41B883]">Vue.js</span> 及其生態系，並具備後端服務 Node.js, TypeScript 開發經驗。<br/>

  熟悉從零到一建置後台管理系統、會員平台等面向終端使用者的服務型網站，<br/>並擁有金流以及第三方點數平台串接實戰經驗<br/>

  開發過程高度重視使用者體驗與整體品質，<br/>但不會固執於己見，能靈活應對不同需求。<br/>

  積極有責任感，樂於主動協助團隊，為共同目標努力。<br/>

  具備獨立解決問題、有效完成分配任務與持續學習精進的能力。

</div>
</div>

  <img src="./profile.jpeg" class="w-48 h-48 rounded-2xl" />
</div>

<div class="flex flex-wrap gap-3 mt-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:javascript.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:pinia.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:element.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:graphql.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:nodejs-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-20 bg-white px-1 rounded" />
  <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:redis.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:git-icon.svg" class="w-10" />
</div>

<!--
大家好，我是簡爾廷，英文名字是 David。
我是一位有 9 年多經驗的前端工程師，主要專精在 Vue.js 與相關生態系，同時也具備 Node.js 後端開發能力。
熟悉從零到一建置後台管理系統、會員平台等服務型網站，擁有金流串接與第三方點數平台整合的實戰經驗。
我重視使用者體驗與程式碼品質，積極主動負責，樂於團隊協作。
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
      <div class="text-xs text-gray-400">TypeScript · Express · SFTP · Cron</div>
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
  <span>第三方點數：全家 / HAPPYGO</span>
</div>

<!--
首先是我職涯中待最久的公司，阿爾伊，將近 8 年的時間。
公司核心產品「RE·X 點數魔術師」是一個點數整合應用平台，消費者可在合作店家進行交易獲得高額回饋點數，點數又可在下次消費折抵。
我在這家公司從前端工程師做到資深前端工程師，負責了非常多的專案，接下來幾頁會分別介紹。
-->

---

# RE·X 官方網站

<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-14 bg-white px-1 rounded" />
  <img src="https://api.iconify.design/logos:sass.svg" class="w-7" />
</div>

<div class="text-sm text-gray-500 mb-3">官方形象網站，提供平台介紹、合作店家列表、App 下載及聯絡客服等資訊，並支援多地區與多語系。<br/>行銷活動以及 App 內的 WebView 頁面也由此專案提供。</div>

- **SSR 效能優化** — 提升 Core Web Vitals（LCP / FID / CLS）至良好等級
  - LRU Cache 緩存靜態資料、Lazy Hydration 延遲非必要水合、Nuxt Image 圖片壓縮
- **多地區多語系** — 設計並實作 vue-i18n 架構，支援台灣 / 新加坡 / 馬來西亞
- **SEO** — 動態 Sitemap、Meta Tags、社群分享 OG Tags
- **Express 自訂路由** — 行銷短網址、App Deep Link 處理

<img src="https://hackmd.io/_uploads/BkFMflZV-g.png" class="rounded shadow-lg mt-3" style="max-height: 160px; object-fit: contain;" />

<!--
RE·X 官方網站是揭露公司資訊的形象官網。
為了良好的 SEO，使用 Nuxt.js 實作 SSR。
效能方面，實作了 LRU Cache 快取策略、Bot 偵測差異化處理、以及 Lazy Hydration 延遲水合來優化首屏載入速度。
在公司將產品從台灣擴展到馬來西亞跟新加坡的過程中，由我設計與實作多語系架構。
Express 自訂路由處理行銷短網址與 App Deep Link 的邏輯。
行銷活動以及 App 內的 WebView 頁面也由此專案提供。
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
  - 公司內部管理系統 CRUD 表單，提供同事管理廣宣物資料
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
RE·X BOSS 店家管理系統是 Hybrid App 的架構，一份程式碼同時運行於 iOS、Android 與 Web 三個平台，透過 JS Bridge 與 Native App 溝通。
我將專案從 Vue/cli 遷移至 Vite 來提升開發體驗，也用 D3.js 實作了交易分析、會員分析的資料視覺化功能。
另外也用 Sharp 跟 pdfmake 實作了結帳立牌的圖片生成功能。
金流方面，串接了 TapPay 支援台灣店家、Stripe 支援新加坡店家的付款與綁卡自動扣款，並將 TapPay 封裝為 Vue 組件提供不同專案使用。
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
  <img src="https://api.iconify.design/logos:google-maps.svg" class="w-6" />
</div>

<div class="text-xs text-gray-500 mb-2">供市場部業務與合作夥伴使用的店家開發平台，由我從零到一設計開發。</div>

- Zod 實作各欄位**連動驗證**，引導表單填寫
- **Google Maps API** 地址自動補全與座標抓取
- 證件**浮水印**處理 + **GCS** 加密上傳，確保資料安全
- 串接藍新金流**商家開通**流程

</div>

::right::

<div class="pl-4">

### RE·X Admin
<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:element.svg" class="w-6" />
  <img src="https://api.iconify.design/logos:graphql.svg" class="w-6" />
</div>

<div class="text-xs text-gray-500 mb-2">依權限控管提供各部門使用的內部管理系統，接手為主要維護、開發者。</div>

- **Nuxt1 → Vue/cli → Vite** 兩次建構遷移，大幅提升啟動與熱重載速度
- Apollo Client 串接 **GraphQL** API
- 建立 ElementUI 共用組件庫（表單、表格、Modal），快速應對各部門需求
- 依需求設計實作 **CRUD** 表單功能

</div>

<!--
市場開發系統是供業務使用的店家開發平台，由我從零到一設計與開發。
用 Zod 做表單驗證、串接 Google Maps API 自動補全地址、證件文件上傳 Google Cloud Storage 同時加上浮水印。
並且串接藍新金流的商家開通流程，包括 SFTP 補件與排程拉取回覆檔。

Admin 後台是公司最大的內部系統，依權限控管提供多部門使用。
經歷了從 Nuxt1 到 Vue/cli 再到 Vite 兩次建構工具的遷移。
我在這個專案中建立了共用組件庫，讓團隊可以快速應對不同部門的需求。
也有使用 Apollo Client 串接 GraphQL API 的經驗。
-->

---

# LINE LIFF 應用程式

<div class="flex gap-2 mt-1 mb-2">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-7" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-14 bg-white px-1 rounded" />
</div>

<div class="text-sm text-gray-500 mb-3">LINE Front-end Framework（LIFF）應用，讓會員可透過官方 LINE@ 進行帳號綁定、查看點數、掃碼交易與行動支付。由我從零到一設計與開發。</div>

<div class="grid grid-cols-2 gap-8">
<div>

- **LINE LIFF SDK** 實作會員登入綁定
- **html5-qrcode** 實作相機掃碼交易（應對 LIFF SDK 部分裝置不支援掃碼）
- 串接藍新金流實作 **Apple Pay on Web** 與 **Google Pay on Web**
- 串接藍新**嵌入式信用卡支付** — 符合 PCI DSS 安全標準
- 封裝金流相關功能為公司私有 **Vue** 共用組件 npm 套件


</div>
<div>

<div class="flex gap-2 justify-center">
<img src="https://hackmd.io/_uploads/SJk8nhl4We.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/SyRvEpeE-g.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
</div>

</div>
</div>

<!--
LINE LIFF 應用程式是 RE·X 在 LINE 官方帳號上的入口，由我從零到一設計與開發。
使用 LINE LIFF SDK 實作會員登入綁定，利用 html5-qrcode 實作相機掃碼功能，提供掃碼交易體驗。
2024 年 9 月上線了消費者支付功能，透過串接藍新金流的平台商架構實現消費者付款給店家。
當時除了 App 外，LINE 也是交易入口，因此實作了 Apple Pay on Web 與 Google Pay on Web。
2025 年初因應 PCI DSS 安全標準，串接了藍新的嵌入式信用卡支付。
我將這些金流相關的組件封裝為共用組件，並發佈到內部私有 npm 套件。
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
  <div class="text-xs text-gray-600">串接全家會員與點數平台 API，紀錄每筆請求/回應<br/>以 RESTful API 提供內部專案串接使用</div>
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
  <div class="text-xs text-gray-600">規劃 API 路由與資料庫結構<br/>排程檢查連續簽到狀態 & 發出提醒推播通知</div>
</div>

<div class="border border-gray-200 rounded-lg p-4">
  <div class="font-bold mb-1">藍新金流商家申請服務</div>
  <div class="flex gap-1 mb-2">
    <img src="https://api.iconify.design/logos:express.svg" class="w-10 bg-white px-1 rounded" />
    <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-5" />
    <span class="text-xs text-gray-400 self-center">ssh2-sftp-client · Cron</span>
  </div>
  <div class="text-xs text-gray-600">SFTP 補件上傳至藍新指定伺服器<br/>排程定期拉取回覆檔案</div>
</div>

<div class="border border-gray-200 rounded-lg p-4">
  <div class="font-bold mb-1">藍新金流交易查詢工具</div>
  <div class="flex gap-1 mb-2">
    <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-5" />
    <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-5" />
    <span class="text-xs text-gray-400 self-center">Nuxt UI · Drizzle ORM</span>
  </div>
  <div class="text-xs text-gray-600">查詢交易資訊、取消授權/退款<br/>核心 API Service 手寫，UI 與操作流程使用 <strong>AI Agent</strong> 生成</div>
</div>

</div>

<!--
除了前端專案，我也負責了幾個後端服務的開發。
全家的部分，串接全家會員平台與點數交換平台的底層 Service 是由我開發的，以 RESTful API 的形式提供給內部其他專案串接使用。
簽到活動服務是我擔任主要開發者，規劃 API 路由與資料庫結構，並實作排程檢查連續簽到與發出提醒推播。
藍新金流商家申請服務負責 SFTP 補件上傳與排程拉取回覆檔。
另外還有一個有趣的專案是藍新金流交易查詢工具，核心的藍新 API Service 是我手寫的，但 UI 與整體操作流程是使用 AI Agent 生成的。
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
- 改寫 **Composition API** + Vuex → **Pinia**
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
在 FunNow，我負責的是店家端的後台管理系統
這個專案較為陳舊，在主管指示下我主導了建構工具的遷移
從 vue/cli 換到 Vite，啟動速度從原本 30 到 60 秒降到大約 1 到 2 秒
同時配合前端團隊的決定導入 TypeScript、Composition API 與 Pinia
主要目標是提升可維護性與團隊開發體驗

組件開發方面，我與設計師協作重構了日期、時間、日期範圍選擇器
提升了整體的使用體驗，這個 DEMO 是我自己另外做的展示頁面
-->

---

# 個人專案 - 個人記錄視覺化

<!-- <a href="https://clipwww.github.io/blog/2021/08/25/google-sheets/" class="text-blue-500 text-xs" target="_blank">文章紀錄</a> -->
利用 Google Sheets 作為資料庫 <br/>
紀錄自己進影廳看電影以及進球場看棒球的資料，並將其視覺化呈現

- 利用 Google Sheets 作為資料庫
- 使用 D3.js, Chart.js 實作資料視覺化呈現
- 使用 Leaflet 實作地圖呈現棒球場位置

<div class="grid grid-cols-2 gap-6 mt-4">
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
再來說說我的 Side Project
這個是我主要還有在使用跟維護的個人專案
起初是用來練習當時剛正式發佈的 Vue 3 以及因公司專案接觸到的資料視覺化這塊
利用 Google Sheets 作為資料庫，記錄下自己進電影院看電影跟進場看棒球的資料後
將這些資料視覺化呈現出來
就是可以看到消費統計、每個月的次數、觀影時間熱點
棒球的話就是勝率跟球場次數以及分布
-->


---
layout: two-cols
---

# 最後

<div class="mt-6">

### 核心優勢

- **9 年以上** 網站與網站應用程式開發經驗
- **專精 Vue.js 與生態系**
- **擁有後端開發經驗** - Node.js / TypeScript
- **金流串接經驗** - TapPay / Stripe / 藍新
- **第三方點數串接經驗** - HAPPYGO / 全家點數
- **重視 UX 與品質** - 確保功能穩定性與可用性
- **團隊協作** - 積極主動負責，樂於溝通協調

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
以上是我的自我介紹
最後再次強調我的核心優勢
如果有任何問題，歡迎隨時提問，謝謝！
-->
