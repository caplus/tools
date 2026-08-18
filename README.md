# 🌟 AI 專案作品集 (AI Projects Portfolio)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/zh-TW/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/zh-TW/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)](https://leafletjs.com/)

精選多領域智慧互動工具與獨立應用的前端專案作品集。全站採純前端技術開發，支援 100% 離線即時運行，具備現代化 RWD 響應式佈局、深淺色主題切換與沉浸式互動體驗。

---

## 📑 目錄

- [專案簡介](#-專案簡介)
- [作品卡片與應用清單](#-作品卡片與應用清單)
- [首頁特色功能](#-首頁特色功能)
- [專案目錄結構](#-專案目錄結構)
- [快速開始](#-快速開始)
- [技術棧一覽](#-技術棧一覽)

---

## 💡 專案簡介

本專案整合了 6 款涵蓋生活健康、資訊安全、地理地圖、即時氣象與平台媒合等領域的現代化 Web 應用程式。使用者可透過中央首頁 [`index.html`](index.html) 快速瀏覽各應用特點、進行即時搜尋篩選，或一鍵直接開啟與彈窗預覽。

---

## 🚀 作品卡片與應用清單

### 1. 💧 每日喝水追蹤與紀錄 (`daily_water_tracker.html`)
* **分類**：健康習慣 / 生活工具
* **主要特點**：
  - 根據體重與運動量客製化每日建議飲水量目標。
  - 擬真動態注水波浪水位視覺動畫（Wave Fill Animation）。
  - 提供水、茶、咖啡等多種飲品快速記錄與 LocalStorage 本地歷史數據圖表。

### 2. 🛡️ 個資假名化工具 (`data_pseudonymization.html`)
* **分類**：實用工具 / 資訊安全
* **主要特點**：
  - 企業與研究必備的純前端離線個資脫敏工具，資料絕不上傳伺服器。
  - 支援 CSV 與 Excel (`.xlsx`) 表格檔案上傳與即時解析。
  - 提供姓名、身分證字號、電話、Email 等多種欄位假名化規則與雜湊對應，支援一鍵批次匯出。

### 3. 🏛️ 歐洲旅遊景點互動地圖 (`european_tourist_attractions_map.html`)
* **分類**：地圖導覽 / 旅遊地理
* **主要特點**：
  - 整合 Leaflet.js 與 OpenStreetMap 互動圖資，流暢縮放與標記定位。
  - 側邊欄精選景點分類（歷史古蹟、博物館、自然景觀等）與地圖聯動。
  - 支援景點詳細圖文介紹、評分星級、開放時間與自訂 Marker 彈窗。

### 4. 🧘‍♀️ 瑜珈教練代課系統 (`sub_teacher.html`)
* **分類**：媒合系統 / 平台管理
* **主要特點**：
  - 以 React 18 與 Babel 打造的單頁應用 (SPA) 完整媒合工作流。
  - 涵蓋代課發案、教練應徵、排班日曆管理與狀態流轉。
  - 內建模擬即時私訊對話與教練評星機制。

### 5. ⛅ 台北即時天氣 Dashboard (`taipei_weather_dashboard.html`)
* **分類**：實用工具 / 即時資訊
* **主要特點**：
  - 現代極簡玻璃擬態（Glassmorphism）設計風格。
  - 台北市各行政區氣候切換、即時氣溫、濕度、紫外線與降雨機率監測。
  - 整合 Phosphor Icons 動態天氣圖示與未來一週天氣趨勢預報。

### 6. 🍵 台灣抹茶推薦名店互動地圖 (`taiwan_matcha_map.html`)
* **分類**：地圖導覽 / 美食指南
* **主要特點**：
  - 專為抹茶愛好者設計的台灣名店地圖，搭配特調抹茶綠色系主題。
  - 支援北中南地區與甜點/飲品雙維度分類過濾。
  - 收錄店家營業資訊、評分、招牌必點推薦品項與一鍵 Google Maps 導航。

---

## ✨ 首頁特色功能

中央入口頁面 [`index.html`](index.html) 具備以下亮點：

- **🎨 視覺美學與動態效果**：炫彩漸層文字、氛圍動態光暈、立體卡片懸浮投影。
- **🌓 深淺色主題切換**：深色模式 (Dark Mode) 與淺色模式 (Light Mode) 自由切換，並自動記憶設定。
- **🔍 即時關鍵字搜尋**：支援對工具名稱、功能特點與技術標籤的即時模糊搜尋。
- **🏷️ 分類快速過濾**：提供「全部、地圖導覽、健康習慣、實用工具、媒合系統」標籤切換。
- **👁️ 內建快速預覽彈窗 (Iframe Modal)**：無需離開首頁即可直接在彈窗內測試與體驗各項工具。
- **📱 100% 全響應式設計 (RWD)**：在手機、平板、筆電與寬螢幕皆能完美呈現。

---

## 📂 專案目錄結構

```text
tools-main/
├── README.md                              # 專案詳細說明文件
├── index.html                             # 🌟 AI 專案作品集整合入口首頁
├── daily_water_tracker.html               # 💧 每日喝水追蹤與紀錄
├── data_pseudonymization.html             # 🛡️ 個資假名化工具
├── european_tourist_attractions_map.html  # 🏛️ 歐洲旅遊景點互動地圖
├── sub_teacher.html                       # 🧘‍♀️ 瑜珈教練代課系統
├── taipei_weather_dashboard.html          # ⛅ 台北即時天氣 Dashboard
└── taiwan_matcha_map.html                 # 🍵 台灣抹茶推薦名店互動地圖
```

---

## 🏃 快速開始

本專案所有應用均為純前端靜態頁面，**不需要安裝任何後端環境或構建步驟**：

### 方法 1：直接開啟
在檔案總管中雙擊 [`index.html`](index.html) 或任意工具檔案，即可在瀏覽器中直接執行。

### 方法 2：使用本機靜態伺服器 (推薦)
使用 VS Code 的 **Live Server** 擴充套件，或透過 Python 啟動本機伺服器：

```bash
# Python 3
python -m http.server 8000

# 或使用 npx serve
npx serve .
```

開啟瀏覽器並造訪 `http://localhost:8000` 即可暢快體驗。

---

## 🛠️ 技術棧一覽

- **核心**：HTML5, CSS3, ES6+ JavaScript
- **前端框架 / 庫**：React 18, Babel Standalone
- **CSS / 樣式庫**：Tailwind CSS (CDN), Custom CSS Variables, Glassmorphism
- **地圖套件**：Leaflet.js, OpenStreetMap
- **資料處理**：PapaParse (CSV), SheetJS / XLSX (Excel)
- **圖示庫**：Font Awesome 6, Phosphor Icons
- **字體**：Google Fonts (Plus Jakarta Sans, Noto Sans TC, Inter)

---

## 📄 授權說明

本專案供學習、展示與個人使用。
