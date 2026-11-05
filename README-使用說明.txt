# 順益租賃股份有限公司網站

## 檔案
- `index.html`：首頁
- `about.html`：公司介紹
- `contact.html`：聯絡我們
- `success.html`：表單送出後的感謝頁
- `style.css`：共用樣式

## 發布到 GitHub Pages
1. 在 GitHub 建立一個新的 Public repository，例如 `shungye-leasing`。
2. 將本資料夾內所有檔案（不是外層資料夾本身）上傳到 repository 根目錄。
3. 到 repository 的 Settings → Pages。
4. 在 Build and deployment 選擇 Deploy from a branch；Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
5. 等待 GitHub Pages 發布完成，網址通常是 `https://你的GitHub帳號.github.io/shungye-leasing/`。

## 啟用聯絡表單（非 Google 表單）
表單使用 FormSubmit，收件地址已設定為 `toro200040@gmail.com`。
1. 發布網站後，編輯 `contact.html`。
2. 找到 `_next` 這一行：
   `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/success.html`
3. 將它改成你的實際 GitHub Pages 感謝頁網址，例如：
   `https://你的GitHub帳號.github.io/shungye-leasing/success.html`
4. 儲存並重新上傳 `contact.html`。
5. 開啟網站的聯絡我們頁，填寫測試資料並送出。
6. FormSubmit 第一次使用時，會寄一封啟用確認信到 `toro200040@gmail.com`。請先到收件匣（也檢查垃圾郵件）按下啟用連結。
7. 再從網站送出一次測試表單，確認信箱實際收到客戶資料，才算完成老師的驗收。

注意：這是靜態網站，表單郵件由 FormSubmit 處理。不要把私人密碼或 API 金鑰放進 HTML。正式使用前請先完成收件信箱驗證。
