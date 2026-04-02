---
theme: seriph
title: 簡爾廷 - 前端工程師（詳細版）
info: 面試自我介紹簡報 - 詳細版
transition: slide-left
mdc: true
routerMode: hash
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
layout: image-right-third
image: ./profile.jpeg
backgroundSize: contain
---

# 關於我

<div class="text-xs text-gray-500 mt-4">
東海大學資訊管理研究所 (2013-2015)<br>
東海大學資訊工程學系 (2009-2013)
</div>

<div class="mt-4 text-base leading-relaxed">

擁有 **9 年以上**網站與網站應用程式開發經驗的經驗的前端工程師，專精於 <span class="font-bold text-[#41B883]">Vue.js</span> 及其生態系，並具備後端服務 Node.js, TypeScript 開發經驗。<br/>

熟悉從零到一建置後台管理系統、會員平台等面向終端使用者的服務型網站<br/>

具備金流、第三方點數平台串接實戰經驗，開發過程高度重視使用者體驗與整體品質<br/>

積極主動負責，樂於為共同目標與團隊協作，能在團隊協作中發揮正面影響力<br/>

同時具備獨立解決問題、有效完成分配任務與持續學習精進的能力。

</div>

<!--
首先先簡單地見紹一下我自己
我是一位有 9 年多經驗的前端工程師，
主要專精在 VueJS 與 VueJS 相關生態系
同時也具備基礎 NodeJS 後端開發能力
熟悉如何從零到一建置後台管理系統、會員平台等面向終端使用者的服務型網站
擁有金流整合、第三方平台串接實戰經驗，
我很重視使用者體驗、程式碼品質，但不會固執具有彈性，也習慣和設計與後端密切合作。
積極主動負責，樂於為共同目標與團隊協作，能在團隊協作中發揮正面影響力
同時我也具備獨立解決問題、能有效完成分配任務與持續學習精進。
-->


---

# 技術專長

<div class="grid grid-cols-2 gap-8">
<div>

### 前端技術

- **框架**：Vue.js / Nuxt.js
- **語言**：TypeScript / JavaScript
- **狀態管理**：Pinia / Vuex
- **樣式**：TailwindCSS / SASS
- **UI框架**: ElementUI / Vuetify / VantUI / NuxtUI
- **建構工具**：Vite / VueCli / Parcel.js
- **國際化**：VueI18n  
- **版本控制**：Git
- **其他**：GraphQL / LIFF

</div>
<div>

### 後端 & 工具

- **執行環境**：Node.js / Bun
- **框架**：Express.js / Koa.js
- **資料庫**：MySQL / Redis / MongoDB
- **ORM**：DrizzleORM

<div class="flex flex-wrap gap-3 mt-4">
  <img src="https://api.iconify.design/logos:vue.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:nuxt-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:typescript-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:javascript.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:git-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:vitejs.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:sass.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:graphql.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:nodejs-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:express.svg" class="w-10 bg-white p-1 rounded" />
  <img src="https://api.iconify.design/logos:bun.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:mysql-icon.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:redis.svg" class="w-10" />
  <img src="https://api.iconify.design/logos:mongodb-icon.svg" class="w-5" />
  <img src="https://api.iconify.design/logos:pinia.svg" class="w-10" />
</div>

</div>
</div>

<!--
接著是我的技術專長，都是我在工作中實際使用過的技術
前端方面，我主要使用 Vue.js 及相關生態系的框架、套件像是 Nuxt.js, 狀態管理 Pinia，搭配 TypeScript 開發
後端部分，除了 Node.js, Express.js 外，近年因為有協助後端開發 Service 而有使用 MySQL、Redis 以及 ORM 的經驗
-->


---

# 阿爾伊 — 概述

### 前端工程師 → 資深前端工程師（2017/08 - 2022/02, 2023/03 - 2026/01）
<div class="text-xs text-gray-400 mt-1">香港商阿爾伊股份有限公司台灣分公司, 阿爾伊股份有限公司</div>

<div class="flex gap-3">
  <div class="text-sm mt-3">核心產品「RE·X 點數魔術師」是一個點數整合應用平台<br/>可以到合作店家進行交易獲得高額回饋點數，點數又可在下次消費折抵<br/>並且還能夠綁定全家、HAPPYGO 點數來累積與折抵。<a href="https://clipwww.github.io/personal/projects/rex.html" target="_blank" class="text-blue-500 text-xs inline-block">🔗 專案列表</a></div>
  <img :src="`${$base}rex-app.png`" class="w-16 h-16 rounded" />
</div>


<div class="grid grid-cols-2 gap-6 mt-4">
<div>

**消費者/店家端**
- RE·X 官方網站（Nuxt2 SSR）
- RE·X BOSS 店家管理系統（Hybrid App）
- RE·X Web SDK
  - 提供第三方合作廠商串接交易流程
  - 實作 Apple Pay / Google Pay on Web
- RE·X LIFF（LINE@ 應用程式）
- HappyGO Portal Web (Hybrid App）
- 多個行銷活動小遊戲

</div>
<div>

**內部系統 & 其他**
- RE·X Admin 管理後台
- RE·X RD CMS 內容管理
- RE·X 市場開發系統
- 共用 Vue 組件（私有 npm）
- 後端服務（Fami / Check-In / POS / 藍新商家）
- 藍新金流交易查詢工具（Nuxt4 + AI Agent）

</div>
</div>

<!--
首先是我職涯中待最久的公司，阿爾伊，將近 8 年的時間
深度參與了公司產品與內部系統的開發
公司核心產品「RE·X 點數魔術師」是一個點數整合應用平台
可以到合作店家進行交易獲得高額回饋點數，點數又可在下次消費折抵
並且還能夠綁定全家、HAPPYGO 點數來累積與折抵
我處理過的專案數量不少，左邊是面向使用者的產品，右邊是內部系統與其他項目
接下來幾頁我會分別介紹這些專案的重點
-->

---

# 阿爾伊 — 消費者端

<div class="grid grid-cols-2 gap-6">
<div>

### RE·X 官方網站
<div class="text-xs text-gray-400">Nuxt.js@2 (SSR) · Express.js · Vue-i18n · TailwindCSS</div>

負責前端專案架構設計與開發

- 實作 **LRU Cache** 快取策略，提升回應速度
- **Bot 偵測**與差異化處理，優化 SSR 效能
- **Lazy Hydration**（延遲水合），提升首屏載入速度
- 設計與實作**多語系架構**
- 動態 **Sitemap** 生成、**Deep Link** 處理
- 動態 Meta Tags，優化 **SEO** 與社群分享

<div class="flex gap-1 mt-1">
<img src="https://hackmd.io/_uploads/BkFMflZV-g.png" class="rounded shadow-lg mt-2" style="max-height: 140px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/Hk7G7lbVWl.png" class="rounded shadow-lg mt-2" style="max-height: 140px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/HJgszxZEZl.png" class="rounded shadow-lg mt-2" style="max-height: 140px; object-fit: contain;" />
</div>

</div>

<div>

### LINE LIFF 應用程式
<div class="text-xs text-gray-400">Vue.js@3 · TypeScript · LIFF SDK · html5-qrcode</div>

負責前端專案架構設計與開發

- 使用 LINE LIFF SDK 實作會員登入綁定
- 使用 html5-qrcode 實作相機掃碼功能
- 實作 **Apple Pay on Web** 與 **Google Pay on Web**

<div class="flex gap-1 mt-1">
<img src="https://hackmd.io/_uploads/SJk8nhl4We.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/SJ3wBpgV-l.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/SyRvEpeE-g.png" class="rounded shadow-lg" style="max-height: 200px; object-fit: contain;" />
</div>

</div>

</div>

<!--
RE·X 官方網站是揭露公司資訊的形象官網
為了良好的 SEO，使用 Nuxt.js 實作 SSR
效能方面，實作了 LRU Cache 快取策略、Bot 偵測差異化處理、以及 Lazy Hydration 延遲水合來優化首屏載入速度
並且在公司將產品從台灣擴展到馬來西亞跟新加坡的過程中設計與實作了多語系架構

LINE LIFF 應用程式則是 RE·X 在 LINE 官方帳號上的入口
使用 LINE LIFF SDK 實作會員登入綁定
利用 html5-qrcode 實作相機掃碼功能，提供掃碼交易體驗
同時也整合了 Apple Pay on Web 與 Google Pay on Web
-->

---

# 阿爾伊 — 店家端

<div class="grid grid-cols-2 gap-6">


<div>

### RE·X BOSS 店家管理系統
<div class="text-xs text-gray-400">Vue.js@2.7 · Vite · Express.js · D3.js · TailwindCSS</div>

接手維護、負責新功能的架構設計與開發

- **Hybrid App** 處理 Web 與 Native App 溝通
- 設計與實作**多語系架構**
- 從 **Vue/cli 遷移至 Vite**，大幅提升啟動速度
- 用 **D3.js** 實作資料視覺化（交易/會員分析）
- 用 Sharp、pdfmake 實作圖片生成（結帳立牌）

<div class="flex gap-1 mt-1">
<img src="https://hackmd.io/_uploads/rybwPgbVbg.png" class="rounded shadow-lg mt-2" style="max-height: 160px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/BJtnveW4Wl.png" class="rounded shadow-lg mt-2" style="max-height: 160px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/ry51txbE-l.png" class="rounded shadow-lg mt-2" style="max-height: 160px; object-fit: contain;" />
<img src="https://hackmd.io/_uploads/rJK2vgbE-e.png" class="rounded shadow-lg mt-2" style="max-height: 160px; object-fit: contain;" />
</div>

</div>

<div>


<div class="flex flex-col items-center mt-4">
  <div class="flex gap-6 items-end">
    <div class="flex flex-col items-center">
      <img src="https://api.iconify.design/logos:apple-app-store.svg" class="w-10 h-10" />
      <span class="text-xs mt-1 text-gray-500">iOS</span>
    </div>
    <div class="flex flex-col items-center">
      <img src="https://api.iconify.design/logos:google-play-icon.svg" class="w-10 h-10" />
      <span class="text-xs mt-1 text-gray-500">Android</span>
    </div>
    <div class="flex flex-col items-center">
      <img src="https://api.iconify.design/logos:chrome.svg" class="w-10 h-10" />
      <span class="text-xs mt-1 text-gray-500">Web</span>
    </div>
  </div>
  <div class="flex gap-2 mt-3">
    <span class="text-xs px-2 py-0.5 bg-gray-100 rounded text-gray-600">Native 殼</span>
    <span class="text-xs px-2 py-0.5 bg-gray-100 rounded text-gray-600">Native 殼</span>
    <span class="text-xs px-2 py-0.5 bg-gray-100 rounded text-gray-600">瀏覽器</span>
  </div>
  <div class="text-lg mt-2">↓</div>
  <div class="border-2 border-[#41B883] rounded-lg px-6 py-3 mt-1 text-center">
    <div class="flex items-center justify-center gap-2">
      <img :src="`${$base}rex-boss-app.webp`" 
      class="inline-block w-12 h-12 rounded-xl mb-1 align-middle border border-solid border-white" />
      <span class="font-bold">RE·X BOSS</span>
    </div>
    <div class="flex gap-2 items-center justify-center mt-2">
      <img src="https://api.iconify.design/logos:vue.svg" class="w-5 h-5" />
      <img src="https://api.iconify.design/logos:vitejs.svg" class="w-5 h-5" />
      <img src="https://api.iconify.design/logos:tailwindcss-icon.svg" class="w-5 h-5" />
      <img src="https://api.iconify.design/logos:express.svg" class="w-12 p-1 rounded bg-white" />
    </div>
  </div>
</div>

<div class="text-sm  mt-4 text-center">一份程式碼同時運行於三個平台<br/>透過 Bridge 與 Native App 溝通</div>

</div>


</div>

<!--
RE·X BOSS 店家管理系統是 Hybrid App 的架構
讓店家端可以跨 Android、iOS 與 Web 三個平台使用
我用 D3.js 實作了交易分析、會員分析的資料視覺化功能
也將專案從 Vue/cli 遷移至 Vite 來提升開發體驗
另外也用 Sharp 跟 pdfmake 實作了結帳立牌的圖片生成功能

市場開發系統則是供業務使用的店家開發平台
我設計了表單流程來引導資料填寫，加速店家導入
串接 Google Maps API 自動補全地址
並將證件文件上傳到 Google Cloud Storage 同時加上浮水印
-->

---


# 阿爾伊 — 內部系統

<div class="grid grid-cols-2 gap-6">

<div>

### RE·X 市場開發系統
<div class="text-xs text-gray-400">Nuxt.js@2 · Koa.js · ElementUI · Stripe</div>

負責前端專案架構設計與開發

- 設計表單流程引導資料填寫，加速店家導入
- 串接 **Google Maps API** 抓取店家座標與英文地址自動補全
- 證件、文件檔案上傳 **Google Cloud Storage** 與浮水印處理
</div>

<div>

### RE·X Admin
<div class="text-xs text-gray-400">Vue.js@2.7 · Vite · ElementUI · GraphQL · TailwindCSS</div>

負責建構工具遷移與新功能開發

- Nuxt1 → Vue/cli → **Vite** 兩次建構工具遷移
- 使用 Apollo Client 串接 **GraphQL** API
- 建立共用組件庫（表單、表格、Modal）
- 依照需求設計實作 CRUD 表單功能 (前端部分)
</div>


</div>

<!--
Admin 後台是公司最大的內部系統，依權限控管提供多部門使用
這個專案經歷了從 Nuxt1 到 Vue/cli 再到 Vite 兩次建構工具的遷移
也有使用 Apollo Client 串接 GraphQL API 的經驗
我在這個專案中建立了共用組件庫，包含表單、表格、Modal 等
讓團隊可以快速應對不同部門的需求
-->

---

# 阿爾伊 — 金流串接

<div class="grid grid-cols-2 gap-6">
<div>

### 店家端支付功能
<div class="text-xs text-gray-400 mb-2">TapPay SDK· Stripe SDK</div>

- 串接 **TapPay** 支援台灣店家信用卡付款、綁卡自動扣款
- 封裝 TapPay Direct Pay 為 Vue 組件，提供給不同專案使用
- 串接 **Stripe** 支援新加坡店家付款、綁卡自動扣款

<div class="h-4"></div>

### 消費者端支付功能
<div class="text-xs text-gray-400 mb-2">Neweb SDK · Apple Pay JS · Google Pay JS</div>

- 串接藍新金流**平台商架構**實現消費者付款給店家
- 實作 **Apple Pay on Web** 與 **Google Pay on Web**
- 封裝藍新**嵌入式信用卡支付**為 Vue 組件

</div>
<div>

### 金流開通服務
<div class="text-xs text-gray-400 mb-2">Neweb Merchant Service · SFTP</div>

- 建立店家**金流開通**表單送件流程
- 實作證明檔案 **SFTP 補件**與排程拉取回覆檔

<div class="h-4"></div>

### 藍新金流內部工具
<div class="text-xs text-gray-400 mb-2">Nuxt.js@4 · NuxtUI · DrizzleORM · AI Agent</div>

- 快速查詢交易狀態、執行取消授權/退款
- 串接藍新 API 的核心邏輯手寫，**UI 與操作邏輯由 AI Agent 生成**

<!-- <img src="https://hackmd.io/_uploads/BkskDj1Ebx.png" class="rounded shadow-lg mt-2" style="max-height: 160px; object-fit: contain;" /> -->

</div>
</div>

<!--
金流串接是我在阿爾伊的重要工作內容之一
早期店家端平台有儲值功能，因此串接了 TapPay
隨著使用地區擴展到新加坡，又串接了 Stripe

2024 年 9 月上線了消費者支付功能，是透過串接藍新金流的平台商架構實現消費者付款給店家
當時除了 App 外，我們還有 LINE 官方帳號上的交易入口
因此有了 Apple Pay on Web 與 Google Pay on Web 的實作經驗

2025 年初因應 PCI DSS 安全標準，串接了藍新的嵌入式信用卡支付
我將這些金流相關的組件封裝為共用組件，並發佈到內部私有 npm 套件

後端部分也有協助開發 Neweb Merchant Service，處理 SFTP 補件與排程拉取回覆檔
以及 POS Service 的取消交易與帳務功能

另外還有一個有趣的專案是藍新金流內部工具
核心的藍新 API Service 是我手寫的
但 UI、API 路由與整體操作流程是由 AI Agent 生成的
-->

---

# 阿爾伊 — 第三方點數串接 & 後端服務

<div class="grid grid-cols-2 gap-6">
<div>

### Fami Service
<div class="text-xs text-gray-400 mb-2">Express.js · MySQL · Redis</div>



- 串接全家會員與點數平台 API
- API 請求/回應電文記錄
- 以 RESTful API 提供內部專案串接使用

<div class="h-4"></div>  

### HappyGO Portal WebView
<div class="text-xs text-gray-400 mb-2">Vue.js@3 · Express.js · TailwindCSS</div>

以 Vue3 重構舊的 Flutter Web

- 提供 HappyGO App 內「卡+」與「領紅包」入口
- 處理 **Hybrid App 與 WebView 溝通**
- 實作簡訊 OTP 驗證與會員綁定

</div>
<div>

### Check-In Service
<div class="text-xs text-gray-400 mb-2">Express.js · Bun · MySQL · Redis · DrizzleORM</div>

簽到活動服務
- 規劃 API 路由與資料庫結構
- 排程檢查連續簽到 & 發出提醒推播

<div class="h-4"></div> 

### POS Service
<div class="text-xs text-gray-400 mb-2">Express.js · Bun · MySQL · Redis · DrizzleORM</div>

協助後端同事開發部分功能

- 實作取消交易功能
- 排程日帳務紀錄生成、檢查帳務異常

</div>
</div>

<!--
我們的核心點數是可以與全家跟 HAPPYGO 的點數互相累積與折抵的

全家的部分，串接全家會員平台與點數交換平台的底層 Service 是由我開發的
這個 Fami Service 是以 RESTful API 的形式提供給內部其他專案串接使用

HappyGO 的部分，我負責開發提供給 HappyGO App 介接的 WebView
讓消費者可以在 HappyGO App 內綁定會員關係，並到合作店家進行交易領回饋
這個 WebView 原本是用 Flutter Web 開發的，因為無法維護，所以由我用 Vue 3 重構

後端服務方面，我擔任主要開發者設計了 Check-In Service 簽到活動服務
包含規劃 API 路由與資料庫結構，並實作排程檢查連續簽到與發出提醒推播
也協助後端同事開發 POS Service 的取消交易與帳務相關功能
-->


---

# FunNow Group

### Frontend Engineer（2022/03 - 2023/02）

<div class="text-sm mt-1">核心產品「FunNow App」是即時預訂享樂平台。</div>

<div class="grid grid-cols-2 gap-6 mt-4">
<div>

### FunNow Manager Web
<div class="text-xs text-gray-400 mt-1">Vue.js@2.7 · Vite · TypeScript · Pinia · Vuetify · WindiCSS · VueUse · Jest · Vue-i18n</div>
負責店家端平台的維護與新功能開發

- 建構工具遷移 **vue/cli → Vite**
  - 開發啟動速度從 **30-60 秒降至 1-2 秒**
- 導入 **TypeScript**
  - 強化程式碼可讀性與可維護性
- 配合團隊決定改寫 **Composition API**
- 使用 **JIRA、Figma** 協調設計與開發流程

</div>
<div>


與設計師協作重構日期時間選擇器組件<br/>

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

# 個人專案 - 生活數據視覺化
<div class="mt-4 flex items-center gap-4">
<span class="text-sm text-gray-500">技術棧：Vue 3 + TypeScript + Vite + TailwindCSS + Chart.js + D3.js</span>
<a href="https://clipwww.github.io/log/" class="text-blue-500" target="_blank">🔗 線上展示</a>
<a href="https://docs.google.com/spreadsheets/d/1wUt7W8p7c-tlaUCZOI6OwGJODfO-TE7VwPMaBvlv9pQ/edit?gid=1722240544#gid=1722240544" class="text-blue-500 text-xs" target="_blank">🔗 Google Sheets 資料</a>
</div>

利用 Google Sheets 作為資料庫 <a href="https://clipwww.github.io/blog/2021/08/25/google-sheets/" class="text-blue-500 text-xs" target="_blank">文章紀錄</a><br/>
練習使用剛正式發佈的 Vue 3 以及 TypeScript、VantUI、Chart.js 和 D3.js<br/>
最初使用 Vue/Cli 後遷移至 Vite

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
  <span class="text-gray-300">|</span>
  <a href="https://clipwww.github.io/blog/" target="_blank" class="text-blue-500 hover:underline">Blog</a>
</div>

</div>

<!--
以上是我的自我介紹
最後再次強調我的核心優勢
如果有任何問題，歡迎隨時提問，謝謝！
-->
