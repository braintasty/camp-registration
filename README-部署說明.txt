童心毓樂靜態網站部署說明

Netlify
1. 登入 Netlify。
2. 選擇 Add new site → Deploy manually。
3. 直接拖曳整份 tongxin-static-site.zip，或先解壓縮再拖曳資料夾。

GitHub Pages
1. 建立新的 GitHub repository。
2. 解壓縮 tongxin-static-site.zip。
3. 將 index.html、assets、testimonials 與其他檔案全部放在 repository 根目錄。
4. 進入 Settings → Pages。
5. Source 選擇 Deploy from a branch，並選擇 main / root。

注意
- index.html 必須位於網站根目錄，不能只上傳 ZIP 而不解壓縮。
- 請勿只移動 index.html；圖片與 assets 資料夾必須一起保留。
- 報名表單會透過網路送往既有的 Google Apps Script，因此使用者需保持網路連線。
