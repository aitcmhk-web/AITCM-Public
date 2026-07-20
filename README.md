# 🍃 AITCM · 智慧中醫 惠及全球

> AITCM（Artificial Intelligence Traditional Chinese Medicine）— 基於大數據與名醫智慧的 AI 中醫辨證論治系統前端。

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
2. 修改 `index_public.html` 開頭的 `API_BASE` 指向你自己的後端伺服器：
   ```js
   const API_BASE = 'https://你的域名';
   ```
3. 部署到你的網頁伺服器（GitHub Pages、Vercel、Nginx 等皆可）

> 💡 如需後端原始碼或部署協助，請聯絡作者。

---

## 🛠️ 功能特色

| 功能 | 說明 |
|------|------|
| 🗣️ AI 中醫辨證對話 | 輸入症狀，AI 提供辨證論治建議 |
| 📧 郵箱驗證登入 | 發送驗證碼至郵箱，5 分鐘內驗證 |
| 📝 留言板 | 匿名留言，交流心得 |
| 🌐 中英雙語支援 | 系統介面支援中英文 |
| 📱 移動端適配 | 完整支援手機與平板 |

---

## 🎨 客製化設定

`index_public.html` 開頭有可自訂設定區，修改以下變數即可：

```js
const CUSTOM = {
    BRAND_CN: '智慧中医',         // 品牌中文名
    BRAND_EN: 'AITCM',            // 品牌英文名
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
