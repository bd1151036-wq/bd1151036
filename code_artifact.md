# 🌟 梁氏明芳 (Liang Minh Phuong) - 個人數位名片

這是一個採用**微透光玻璃質感 (Glassmorphism)** 設計的極簡個人數位名片，專為手機與現代網頁瀏覽體驗所打造。畫面採用亮麗的漸層色彩，並將所有個人資訊集中於單一卡片上，非常適合做為社群媒體的主頁連結 (Link in Bio) 或個人作品集的入口網頁。

## ✨ 專案特色 (Features)

*   **極簡單頁設計 (Single-Page Design)：** 捨棄繁雜的滾動與選單，將核心資訊濃縮於一張卡片。
*   **現代化視覺風格 (Modern UI)：** 採用亮麗的粉、紫、橘漸層背景，搭配毛玻璃效果 (Backdrop Blur) 的卡片主體。
*   **響應式排版 (Responsive Layout)：** 完美適配手機與電腦螢幕，按鈕大小適合手指點擊。
*   **直覺的聯絡介面 (Intuitive Contacts)：** 將 Email、Line 與 Instagram 轉化為直覺的操作按鈕。

## 🛠️ 使用技術 (Tech Stack)

*   **HTML5:** 網頁基礎架構
*   **Tailwind CSS:** 透過 CDN 引入，用於快速構建排版、漸層色彩與毛玻璃等視覺效果
*   **FontAwesome (v6.4):** 提供電影、睡覺、寫程式等高質感的向量圖示 (Icons)
*   **Google Fonts (Noto Sans TC):** 使用清晰易讀的繁體中文字體

## 🚀 如何使用與自訂 (How to Use & Customize)

1. **下載檔案：** 將 `portfolio.html` 下載到您的電腦中。
2. **替換個人照片：**
   使用任何文字編輯器 (如 VS Code 或記事本) 打開 `portfolio.html`。
   找到以下程式碼：
   ```html
   <img src="https://placehold.co/400x400/ffffff/ec4899?text=Photo" ...>
   ```
   將 `src` 屬性內的網址，替換成您自己的真實照片網址 (例如上傳到 Imgur 或 GitHub 上的圖片連結)。
3. **修改社群連結：**
   您可以為 Line 或 Instagram 的區塊加上 `<a>` 標籤，讓訪客點擊後直接跳轉到您的社群主頁。

## 🌐 部署建議 (Deployment)

這個網頁僅包含純前端的 HTML/CSS，非常容易免費部署上線。推薦使用以下平台：

*   **GitHub Pages:** 將檔案上傳至 GitHub 儲存庫，並在設定中開啟 GitHub Pages 即可獲得免費網址。
*   **Vercel / Netlify:** 直接拖曳檔案上傳，幾秒鐘內就能取得專屬的對外連結。

---
*「喜歡簡單生活，也喜歡認真對待每一件事。」*