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

<div class="text-xl mt-2">前端工程師・9 年以上開發經驗</div>

<div v-if="companyName || jobTitle" class="mt-6 text-lg">
應徵 <span v-if="companyName" class="text-blue-500 font-bold">{{ companyName || '【公司名稱】' }}</span> <span v-if="jobTitle" class="text-green-500 font-bold">{{ jobTitle || '【職缺名稱】' }}</span>
</div>



<div class="abs-br m-6 flex gap-2 text-sm opacity-50">
  <a href="https://clipwww.github.io/personal/" target="_blank">Personal Site</a>
  <span>・</span>
  <a href="https://github.com/clipwww" target="_blank">GitHub</a>
</div>

<!--
大家好，我是簡爾廷，可以叫我 David。
今天來應徵貴公司的前端工程師職位
會用大概 5 分鐘，快速介紹我的背景、關鍵經驗，以及一個 side project。
-->

---

# 關於我

<div class="text-xs text-gray-500 mt-4">
東海大學資訊管理研究所 (2013-2015)<br>
東海大學資訊工程學系 (2009-2013)
</div>

<div class="mt-4 text-base leading-relaxed">

**9 年以上經驗** 的前端工程師，專精於 Vue.js 及其生態系，具備基礎後端開發能力<br/>

熟悉從零到一建置後台管理系統、會員平台等面向終端使用者的服務型網站<br/>

擁有金流整合、第三方平台串接實戰經驗，開發過程高度重視使用者體驗與整體品質<br/>

積極主動負責，樂於為共同目標與團隊協作，能在團隊協作中發揮正面影響力<br/>

同時具備獨立解決問題、有效完成分配任務與持續學習精進的能力。

</div>

<!--
我是一位近 10 年經驗的前端工程師，
主要專精在 Vue 與相關生態系。
我的背景主要是中大型 Web 專案，
從零到一建置後台、會員平台，以及實際商業化的產品。
我很重視使用者體驗、程式碼品質，也習慣和設計與後端密切合作。
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
- **其他**：GraphQL / LIFF

</div>
<div>

### 後端 & 工具

- **執行環境**：Node.js / Bun
- **框架**：Express.js / Koa.js
- **資料庫**：MySQL / Redis / MongoDB
- **ORM**：DrizzleORM

</div>
</div>

<!--
前端方面，我主要使用 Vue.js 和 Nuxt.js 框架，搭配 TypeScript 開發
後端部分，我也具備基礎的 Node.js 開發能力，熟悉資料庫操作和金流串接
-->


---

# 工作經歷與專案成就

### 阿爾伊 - 前端工程師, 資深前端工程師（2017/08 - 2022/02, 2023/03 - 2026/01）
<div class="text-xs text-gray-400 mt-1">香港商阿爾伊股份有限公司台灣分公司, 阿爾伊股份有限公司</div>


<div class="grid grid-cols-2 gap-6">
<div>

**金流整合**
- 串接 TapPay / Stripe / 藍新金流
- 實作 Apple Pay / Google Pay on Web
- 串接嵌入式信用卡支付
- 建立店家藍新金流開通流程與 SFTP 補件機制

**第三方點數平台串接**
- 串接全家會員平台 / 點數交換平台
- 紀錄請求回應電文
- 開發 HAPPYGO App 介接入口 WebView 


</div>
<div>

**專案開發與維護**
- 開發官方網站 (Nuxt)、店家平台（Hybrid App）
- 多語系架構設計與實作
- 內部系統、行銷活動網頁
- 處理跨平台／瀏覽器相容性問題
- 開發維護前端共用組件

</div>
</div>

<!--
這些是我職涯中最重要的成就亮點
阿爾伊是同一家公司，中間離開一年後回來
在阿爾伊，我主要負責金流與第三方平台整合，
包含 TapPay、Stripe、藍新，以及 Apple Pay、Google Pay。
這段經驗讓我對穩定性、例外處理與跨團隊溝通非常熟悉。
-->

---

### FunNow - Frontend Engineer（2022/03 - 2023/02）

**專案遷移與優化**
- 主導 vue/cli → Vite 遷移，**啟動速度從 30-60 秒降至 1-2 秒**
- 導入 TypeScript，提升程式碼可讀性、可維護性、減少執行時錯誤
- 配合團隊決定改寫 Composition API、遷移 Vuex 至 Pinia，提升邏輯重用性
- 使用 JIRA、Figma 協調設計與開發流程
- 與設計師協作重構 Date/Time/DateRange Picker 組件，提升使用體驗

--

### WhatsMedia - 前端工程師（2016/03 - 2017/07）

與設計、後端同事協作開發與維護各種類型的專案：形象網站、會員平台、活動網頁、APP 內嵌網頁、內部系統網站

<!--
在 FunNow，我主導了一次前端架構遷移，
從 vue/cli 換到 Vite，啟動速度從原本 30 到 60 秒，
降到大約 1 到 2 秒。
同時導入 TypeScript、Composition API 與 Pinia，
主要目標是提升可維護性與團隊開發體驗。
-->


---

# 個人專案 - 生活數據視覺化
<div class="mt-4 flex items-center gap-4">
<span class="text-sm text-gray-500">技術棧：Vue 3 + TypeScript + Vite + TailwindCSS + Chart.js + D3.js</span>
<a href="https://clipwww.github.io/log/" class="text-blue-500" target="_blank">🔗 線上展示</a>
</div>

利用 Google Sheets 作為資料庫 <a href="https://clipwww.github.io/blog/2021/08/25/google-sheets/" class="text-blue-500 text-xs" target="_blank">文章紀錄</a><br/>
練習使用剛正式發佈的 Vue 3 以及 TypeScript、VantUI、Chart.js 和 D3.js<br/>
後隨時間再從 Vue/Cli 遷移至 Vite

<div class="grid grid-cols-2 gap-6 mt-4">
<div>

🎬 **電影院觀影紀錄**
- 場次/消費統計、影片版本/影城分佈
- 觀影時間熱力圖

<img src="https://hackmd.io/_uploads/HkOEeDmHbg.png" class="rounded shadow-lg mt-2" style="max-height: 180px; object-fit: contain;" />

</div>
<div>

⚾ **職棒入場紀錄**
- 觀賽統計、主場勝率
- 球場分佈圖

<img src="https://hackmd.io/_uploads/H1tW-vQBbl.png" class="rounded shadow-lg mt-2" style="max-height: 180px; object-fit: contain;" />

</div>
</div>



<!--
除了工作，我也在開發個人專案來練習新技術
這個專案是我用來練習 Vue 3、TypeScript、Vite 的一個生活數據視覺化專案
同時也是做一個嘗試，在年底時不少 App 都會做年度回顧
我在做的時候就也邊思考公司的專案是不是也可以做類似的功能，來增加使用者的黏著度和活躍度
-->


---
layout: two-cols
---

# 我相信自己可以勝任的原因

<div class="mt-6">

### 核心優勢

- **9 年以上** 網站與 Web 應用程式開發經驗
- **專精 Vue.js 與生態系**
- **基礎後端開發經驗**
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
