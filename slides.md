---
theme: seriph
title: 簡爾廷 - 前端工程師
info: 面試自我介紹簡報
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

# 工作經歷與專案成就

### 阿爾伊 - 前端工程師, 資深前端工程師（2017/08 - 2022/02, 2023/03 - 2026/01）
<div class="text-xs text-gray-400 mt-1">香港商阿爾伊股份有限公司台灣分公司, 阿爾伊股份有限公司</div>

<div class="text-xs mt-2">核心產品「RE·X 點數魔術師」是一個點數整合應用平台，可以到合作店家進行交易獲得高額回饋點數，點數又可在下次消費折抵，並且還能夠綁定全家、HAPPYGO 點數來累積與折抵。<a href="https://clipwww.github.io/personal/projects/rex.html" target="_blank" class="text-blue-500 text-xs inline-block">🔗 專案列表</a></div>

<div class="grid grid-cols-2 gap-6">

<div>

**專案開發**
- 官方網站 (Nuxt SSR)、店家平台（Hybrid App）
  - 多語系架構設計與實作
  - 最佳化 SEO 與網站效能
- 內部 Admin、CMS 系統
  - 應需求設計與實作各種類型的表單
- 行銷活動網頁、互動小遊戲
- 處理跨平台／瀏覽器相容性問題
- 開發維護前端共用組件


</div>

<div>

**金流串接**
- 串接 TapPay / Stripe 實現店家端加值功能
- 串接 藍新金流 平台商架構實現消費者端支付功能
  - 實作 Apple Pay / Google Pay on Web
  - 串接嵌入式信用卡支付，符合 PCI DSS 安全標準
  - 建立店家金流開通支付收款與 SFTP 補件流程

**第三方點數平台串接**
- 串接全家會員平台 / 點數交換平台
- 開發 HAPPYGO App 介接入口 WebView 


</div>

</div>

<!--
接著是我的工作經歷，首先是我職涯中待最久的公司，阿爾伊，將近 8 年的時間
深度參與了公司產品與內部系統的開發
公司核心產品「RE·X 點數魔術師」是一個點數整合應用平台，可以到合作店家進行交易獲得高額回饋點數，點數又可在下次消費折抵，並且還能夠綁定全家、HAPPYGO 點數來累積與折抵。
我處理過的專案數量不少，這裡不依依列出
最主要是揭露公司資訊的形象官網，為了良好的 SEO，使用 Nuxt.js 實作 SSR，並且針對 Lighthouse 的建議進行優化
店家端則是採用 Hybrid App 的架構，讓店家端的系統可以有 Android、iOS 與 Web 3平台
並且在公司將產品從台灣擴展到馬來西亞/新加坡的過程中設計與實作了多語系架構
在金流串接方面，
早期店家端平台有儲值功能因此串接 TapPay，在使用地區擴展到新加坡因此串接 Stripe
在 2024 年 9 月時上線了消費者支付的功能，是藉由串接藍新金流的平台商家架構實現消費者付款給店家
當時除了 App 外我們還有一個產品是可以在 REX 的 LINE 官方帳號上進行交易
因此有了 Google Pay on Web 與 Apple Pay on Web 的實作經驗

並且我們的核心點數，是可以使用全家、HAPPYGO 點數來累積與折抵的
串接全家會員平台 / 點數交換平台的底層 Service 是由我協助開發
HappyGO 則是負責開發要提供給 HappyGO App 介接入口的 WebView，讓消費者可以使用 HappyGO 的 App 到我們的合作店家進行交易領回饋
-->

---

### FunNow - Frontend Engineer（2022/03 - 2023/02）

<div class="text-xs mt-2">核心產品「FunNow App」是一個即時預訂享樂的平台，能夠輕鬆預訂 15 分鐘後的餐飲、酒吧、按摩、飯店、KTV 等跨產業休閒娛樂，省去查找、排隊、溝通空位的麻煩。</div>
<div class="text-xs mt-2">我負責的是店家端使用的平台，提供店家管理訂單、設定商品價格與優惠時段等功能</div> 

**專案遷移與優化**
- 主導 vue/cli → Vite 遷移，**啟動速度從 30-60 秒降至 1-2 秒**
- 導入 TypeScript，提升程式碼可讀性、可維護性、減少執行時錯誤
- 配合團隊決定改寫 Composition API、遷移 Vuex 至 Pinia，提升邏輯重用性
- 使用 JIRA、Figma 協調設計與開發流程
- 與設計師協作重構日期時間選擇器組件，提升使用體驗


--

### WhatsMedia - 前端工程師（2016/03 - 2017/07）

與設計、後端同事協作開發與維護各種類型的專案：形象網站、會員平台、活動網頁、APP 內嵌網頁、內部系統網站

<!--
在 FunNow，我負責的是店家端使用的平台
這個專案較為陳舊，在主管指示下我主導了建構工具的遷移，
從 vue/cli 換到 Vite，啟動速度從原本 30 到 60 秒，
降到大約 1 到 2 秒。
同時配合前端團隊的決定導入 TypeScript、Composition API 與 Pinia，
主要目標是提升可維護性與團隊開發體驗。
在 FunNow 的工作流程中，有使用 JIRA 以及 Figma 來協調設計與開發的經驗

WhatsMedia 是我職涯的第一家公司，這是接案類型的公司
因此有接觸各種類型的專案與客戶
這段時期讓我累積不少前端開發的基礎經驗以及些許 .NET MVC 的開發經驗
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
後隨時間再從 Vue/Cli 遷移至 Vite

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
