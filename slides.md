---
theme: seriph
title: 簡爾廷 - 前端工程師
info: |
  面試自我介紹簡報
  擁有 9 年以上網站與 Web 應用程式開發經驗
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

<div class="text-xl mt-2">前端工程師 ・ 9 年以上開發經驗</div>

<div v-if="companyName || jobTitle" class="mt-6 text-lg">
應徵 <span class="text-blue-500 font-bold">{{ companyName || '【公司名稱】' }}</span> <span class="text-green-500 font-bold">{{ jobTitle || '【職缺名稱】' }}</span>
</div>



<div class="abs-br m-6 flex gap-2 text-sm opacity-50">
  <a href="https://clipwww.github.io/personal/" target="_blank">Personal Site</a>
  <span>・</span>
  <a href="https://github.com/clipwww" target="_blank">GitHub</a>
</div>

<!--
大家好，我是簡爾廷，是一位有 9 年以上經驗的前端工程師
今天來應徵貴公司的前端工程師職位
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
我是一位有 9 年以上經驗的前端工程師
專注於 Vue.js 和相關生態系的開發
重視使用者體驗與程式碼品質，樂於與團隊協作
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

### 阿爾伊 - 前端工程師 / 資深前端工程師（2017 - 2022, 2023 - 2026）
<div class="text-xs text-gray-400 mt-1">香港商阿爾伊股份有限公司台灣分公司 -> 阿爾伊股份有限公司</div>


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

---

### FunNow - Web Front-End Engineer（2022 - 2023）

**專案遷移與優化**
- 主導 vue/cli → Vite 遷移，**啟動速度從 30-60 秒降至 1-2 秒**
- 導入 TypeScript，提升程式碼可讀性、可維護性、減少執行時錯誤
- 配合團隊決定改寫 Composition API、遷移 Vuex 至 Pinia，提升邏輯重用性
- 使用 JIRA、Figma 協調設計與開發流程
- 與設計師協作重構 Date/Time/DateRange Picker 組件，提升使用體驗

--

### WhatsMedia - 前端工程師（2016 - 2017）

與設計、後端同事協作開發與維護各種類型的專案：形象網站、會員平台、活動網頁、APP 內嵌網頁、內部系統網站

<!--
這些是我職涯中最重要的成就亮點
阿爾伊是同一家公司，中間離開一年後回來
藍新金流整合展示了我的全端思維和對支付安全的理解
Vite 遷移展示了我的技術決策能力和對開發體驗的重視
-->


---

# 個人專案 - 生活數據視覺化

個人開發的數據視覺化專案，記錄和分析日常生活數據

<div class="grid grid-cols-2 gap-6 mt-4">
<div>

🎬 **電影院觀影紀錄**
- 場次統計、影城分佈、消費分析
- 貢獻度熱圖、時間熱力圖

<img src="https://hackmd.io/_uploads/HkOEeDmHbg.png" class="rounded shadow-lg mt-2" style="max-height: 180px; object-fit: contain;" />

</div>
<div>

⚾ **職棒入場紀錄**
- 觀賽統計、主場勝率
- 球場分佈圖

<img src="https://hackmd.io/_uploads/H1tW-vQBbl.png" class="rounded shadow-lg mt-2" style="max-height: 180px; object-fit: contain;" />

</div>
</div>

<div class="mt-4 flex items-center gap-4">
<span class="text-sm text-gray-500">技術棧：Vue 3 + TypeScript + Vite + TailwindCSS + Chart.js + D3.js</span>
<a href="https://clipwww.github.io/log/" class="text-blue-500" target="_blank">🔗 線上展示</a>
</div>

<!--
除了工作，我也在開發個人專案來練習新技術
Log 專案展示了我對資料視覺化的興趣和前端技術的應用
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
