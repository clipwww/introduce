# RE·X 專案介紹

## 官方網站
Nuxt 2 · TypeScript · SCSS + Tailwind · Express · vue-i18n

### 專案背景
官方形象網站，提供平台介紹、合作店家列表、App 下載及聯絡客服等資訊，並支援多地區(台灣/新加坡)與多語系（繁中/簡中/英文）。
行銷活動以及 App 內的 WebView 頁面（如信用卡綁定、簽到、抵用券等）也由此專案提供內容。
Express 自訂路由處理行銷短網址與 App Deep Link。

### 系統架構總覽
[Nuxt 2 + Express] <--- 透過自訂 Proxy 串接 ---> [RE·X API]
  |
  |-- JS Bridge -- RE·X App WebView 頁面


### 角色與成就
擔任主要開發者，負責專案的架構設計與開發，將原本為靜態 Html 的官方網站重構為 Nuxt 2 專案
- 使用 Nuxt 2 實作官方網站與 App WebView 頁面
- 使用 Express 實作自訂路由，處理行銷短網址與 App Deep Link 的邏輯
- 使用 VueI18n 實作多語系功能
- 配合行銷活動需求，與設計師協作開發專屬的活動頁面
- 提升 Core Web Vitals 分數，將 LCP、FID、CLS 分數提升至良好 
  - 使用 Lazy Loading、Nuxt Image 處理圖片的延遲加載與壓縮
  - 使用 Lazy Hydration 提升首屏渲染速度，延後非必要互動的加載與執行
  - 使用 LRU Cache 緩存部分靜態資料，減少請求次數與加速回應
  - 設計 Skeleton Loading 提升使用者體驗


## BOSS 店家後台管理系統
Vue 2.7 · Vite · Express.js · D3.js · TailwindCSS

### 專案背景
店家端後台管理系統，提供合作店家查看訂單、交易分析、行銷廣宣物下載及請款等功能，並支援多語系（繁中/簡中/英文）。
為 Hybrid App 形式，同時支援 iOS、Android 與網頁瀏覽器。

### 系統架構總覽
[Vue 2.7 + Express] <--- 透過自訂 Proxy 串接 ---> [RE·X API]
  |
  |-- JS Bridge -- RE·X BOSS App WebView 頁面

### 角色與成就
原擔任特定功能負責人與協助開發的角色，後接手為主要維護、開發者
- **Hybrid App** 處理 Web 與 Native App 溝通
- 從 **Vue/cli 遷移至 Vite**，大幅提升開發啟動速度
- 與同事協作用 **D3.js** 實作交易資料視覺化呈現
- 串接 TapPay, Stripe 實作台灣/新加坡店家加值功能
  - 將 TapPay 無跳轉嵌入式信用卡付款功能封裝為私有 Vue 組件，提供不同專案使用
- 規劃設計與實作廣宣物下載功能 
  - 公司內部管理系統 CRUD 表單，提供同事管理廣宣物模板資料
  - 店家端使用 `Sharp` 帶入推薦碼與文案生成結帳立牌與行銷廣宣物


## 市場開發系統
Nuxt 2 · Koa.js · TypeScript · ElementUI · TailwindCSS

### 專案背景
市場開發業務系統，提供市場部業務與在地合作夥伴進行店家開發功能，並支援多語系（繁中/簡中/英文）。
支援線上填寫表單、上傳檔案以及線上付款，能夠快速導入店家資料與開通藍新金流收款。

### 系統架構總覽
[Nuxt 2(SPA Mode) + Koa.js] <--- 透過自訂 Proxy 串接 ---> [RE·X API]

### 角色與成就
擔任主要開發者，負責專案從零到一的架構設計與開發
- 使用 ElementUI 根據需求欄位設計表單
- 使用 Zod 實作各欄位之間連動的邏輯以及驗證
- 證件添加浮水印與文件上傳 Google Cloud Storage 並加密，確保資料安全
- 串接 Google Map API 根據地址抓取店家座標與英文地址自動補全，加速表單填寫


## 公司內部管理系統
Vue 2.7 · Vite · Express.js· TypeScript · ElementUI · TailwindCSS · GraphQL

### 專案背景
公司內部管理系統，依權限控管提供各個部門使用

### 系統架構總覽
[Vue 2.7 + Express] 
 |<-- 透過自訂 Proxy 串接 ---> [RE·X API]
 |<----> [RE·X GraphQL API]

### 角色與成就
原擔任特定功能負責人與協助開發的角色，後接手為主要維護、開發者
- 使用 ElementUI 建立共用組建庫（表單、表格、Modal等），減少重複開發，快速應對不同需求的操作
- 根據需求欄位設計 CRUD 表單
- 將專案從 Nuxt1 遷移至 Vue/cli，隨時間經過再遷移至 Vite，大幅提升專案開發啟動與熱重載速度

## 官方LINE@LIFF 應用程式
Vue 3 · Vite · Express.js · TypeScript · Pinia · WindiCSS

### 專案背景
LINE Front-end Framework（LIFF）可在 LINE App 內直接建立並執行網頁應用程式
提供會員可以直接透過官方LINE@的圖文選單進行帳號綁定、查看目前點數、抵用券以及掃碼交易

### 系統架構總覽
[Vue 3 + Express] <--- 透過自訂 Proxy 串接 ---> [RE·X OPEN API]

### 角色與成就
擔任主要開發者，負責專案的架構設計與開發
- 使用 LINE LIFF SDK 實作會員登入綁定
- 使用 `html5-qrcode` 實作掃碼功能，以應變當時 LIFF SDK 部分裝置不支援掃碼的問題
- 串接藍新金流實作 Apple Pay & Google Pay on Web，提供會員便捷的支付方式


## 後端服務與內部工具
- **全家會員與點數服務**
  - 負責串接全家會員與點數平台 API，紀錄每筆請求/回應，並以 RESTful API 提供給內部專案串接使用
  - 技術棧: Express.js, TypeScript, MySQL, Redis
- **簽到活動服務**
  - 負責規劃與設計簽到活動的資料結構與 API
  - 排程檢查連續簽到狀態 & 發出簽到提醒推播通知
  - 技術棧: Express.js, TypeScript, MySQL, Redis, Cron
- **藍新金流商家申請服務**
  - 負責開發 SFTP 補件上傳功能，將商家申請所需的檔案上傳至藍新金流指定 SFTP 伺服器，並排程定期拉取回覆檔案
  - 技術棧: Express.js, TypeScript, ssh2-sftp-client, Cron
- **藍新金流交易查詢工具**
  - 提供同事快速查詢藍新金流交易資訊，並可針對異常或爭議交易執行取消授權/退款
  - 使用 AI Agent 進行規劃與功能實作
  - 技術棧: Nuxt 4、Nuxt UI、TypeScript、MySQL、Drizzle ORM

## 個人專案 - 個人記錄視覺化

## 專案背景
紀錄自己進影廳看電影以及進球場看棒球的資料，並將其視覺化呈現

### 角色與成就
- 使用 Google Sheets 作為資料庫
- 使用 D3.js, Chart.js 實作資料視覺化呈現
- 使用 Leaflet 實作地圖呈現棒球場位置


  
