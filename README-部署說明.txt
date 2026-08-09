童心毓樂網站｜Netlify 與自訂網址部署說明

建議方式：Netlify
原因：不需操作程式碼、可直接上傳網站檔案，也能連接自己的網域並自動提供 HTTPS。

一、第一次發布到 Netlify
1. 登入 https://app.netlify.com/
2. 開啟 https://app.netlify.com/drop
3. 將本 ZIP 拖曳到上傳區；若無法接受 ZIP，請先解壓縮，再拖曳解壓後的整個資料夾。
4. 發布完成後會先取得一個「隨機名稱.netlify.app」網址。
5. 點選網址旁的 Customize，可將前半段改成容易記住的名稱，例如：
   braintasty-camp.netlify.app

二、連接自己購買的網域
1. 先準備已購買的網域，例如 braintasty.tw。
2. 進入 Netlify 專案的 Domain management。
3. 選擇 Add a domain → Add a domain you already own。
4. 輸入自己的網域並完成驗證。
5. 選擇使用 Netlify DNS，或依原網域商提示設定 DNS。
6. DNS 生效後，Netlify 會自動申請 HTTPS 安全憑證。

三、以後更新網站
1. 取得新的網站 ZIP 並解壓縮。
2. 進入原本的 Netlify 專案。
3. 在 Production deploys 的拖放區上傳新的網站資料夾。
4. 原本的 netlify.app 網址與自訂網域都會保持不變。

四、若改用 GitHub Pages
1. 建立新的 GitHub repository。
2. 解壓縮本 ZIP。
3. 將 index.html、assets、testimonials 及其餘檔案全部上傳到 repository 根目錄。
4. 進入 Settings → Pages。
5. Source 選擇 Deploy from a branch，選擇 main 與 /root。
6. 若要使用自己的網域，請在 Settings → Pages → Custom domain 輸入網域，並依 GitHub 指示設定 DNS。

重要提醒
- index.html 必須位於網站最外層，不能多包一層資料夾。
- assets、testimonials、圖片及其他檔案必須完整保留。
- 報名資料會送往既有的 Google Apps Script；這次網站更新不需要再次修改 Apps Script。
- 若先前尚未完成「確認信費用明細」的 Apps Script 更新，仍需完成該次設定。
