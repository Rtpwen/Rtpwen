# Rtpwen 個人網站

這是一個可直接部署到 GitHub Pages 的靜態網站，使用 HTML、CSS、JavaScript，不需要建置工具。

## 本機預覽
1. 解壓縮資料夾。
2. 雙擊 `index.html`，使用 Chrome、Edge 或 Firefox 開啟。

## 發布到 GitHub Pages
1. 到 https://github.com/signup 註冊 GitHub 帳號並驗證電子郵件。
2. 登入後，點右上角 `+` → `New repository`。
3. Repository name 輸入 `你的GitHub使用者名稱.github.io`，例如帳號是 `rtpwen`，就輸入 `rtpwen.github.io`。
4. 選擇 `Public`，按 `Create repository`。
5. 在新 Repository 頁面選 `Add file` → `Upload files`。
6. 把 `index.html` 拖進上傳區，按 `Commit changes`。
7. 到 Repository 的 `Settings` → `Pages`。在 `Build and deployment` 中，Source 選 `Deploy from a branch`；Branch 選 `main`，資料夾選 `/(root)`，按 `Save`。
8. 等待幾分鐘，再開啟 `https://你的GitHub使用者名稱.github.io/`。

## 修改網站
在 GitHub 上點 `index.html`，按鉛筆圖示即可編輯；修改後按 `Commit changes`。網站通常會在短時間內更新。

## 重要說明
- 網站的音樂播放器會播放你自行選擇的本機音訊檔，沒有內建歌曲。
- 目前留言板使用瀏覽器 `localStorage`，留言只保存在該訪客自己的瀏覽器，不會跨裝置或讓所有訪客共同看到。若要公開共享留言，需要另外接入後端或資料庫服務。
- 作品卡片、介紹文字目前是示範內容，請改成自己的資料。
- GitHub Pages 適合發布靜態網站；不要把密碼、API 金鑰或私人資料放進公開程式碼。
