# 🍃 AITCM · 智慧中醫 惠及全球

> AITCM（Artificial Intelligence Traditional Chinese Medicine）— 基於大數據與名醫智慧的 AI 中醫辨證論治系統。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📋 專案說明

本 Repo 為 AITCM 系統的 **全球公開版前端**，任何人都可以：

- ✅ 直接訪問 [https://aitcm.cpolar.io](https://aitcm.cpolar.io) 使用
- ✅ Fork 後修改前端樣式或品牌名稱
- ✅ 部署自己的版本

> ⚠️ 本 Repo **僅包含前端原始碼**（HTML + CSS + JavaScript），後端服務未公開。

---

## 🚀 快速開始

### 直接使用

無需安裝任何東西，打開瀏覽器即可：

```
https://aitcm.cpolar.io
```

### 自行部署

1. **Fork 本 Repo**
2. 修改 `index_public.html` 開頭的 `API_BASE` 指向你自己的後端伺服器
3. 部署到你的網頁伺服器（GitHub Pages、Vercel、Nginx 等皆可）

---

## 🛠️ 功能與特色

### ⚡️ AITCM 智慧中醫

> **大數據經典 × 名醫智慧集成**

- 🗣️ **AI 中醫辨證對話** — 輸入症狀，AI 即時提供辨證論治建議
- 📧 **郵箱驗證登入** — 發送驗證碼至郵箱，5 分鐘內快速驗證
- 📝 **留言交流** — 匿名留言板，使用者交流養生心得
- 🌐 **中英雙語支援** — 介面完整支援中英文切換
- 📱 **全面移動端適配** — 手機、平板、桌面皆可流暢使用
- 🧠 **具有自我學習能力** — 越用越聰明，持續優化辨證準確度
- 🔄 **智能復診系統** — 自動調取歷史紀錄，追蹤健康變化軌跡
- 🥗 **食材處方化** — 依辨證結果提供對應食材調理建議
- 🌿 **健康生活化** — 將中醫養生融入日常生活
- 👤 **個體生態管家** — 追蹤個人健康狀態，打造專屬養生方案

---

## 🎨 客製化設定

`index_public.html` 開頭有可自訂設定區，修改以下變數即可：

```js
const CUSTOM = {
    BRAND_CN: '智慧中医',
    BRAND_EN: 'AITCM',
    BRAND_TAGLINE: 'for the World',
    BRAND_SUBTITLE: '惠及全球',
    LOGO_COLOR_PRIMARY: '#4A6B5A',
    LOGO_COLOR_ACCENT: '#7FCDCD',
    WELCOME_MESSAGE: '您好，我是智慧中醫...'
};
```

---

## 📄 免責聲明

使用本系統前，請務必閱讀並同意 [免責聲明](https://aitcm.cpolar.io/disclaimer_public.html)。

---

## 🧑‍💻 作者與授權

- **品牌**：AITCM
- **授權**：MIT License

---

## 🌟 貢獻

歡迎 Issue 與 Pull Request！如有任何問題，請透過 [Telegram](https://t.me/aitcm_com) 聯絡。
