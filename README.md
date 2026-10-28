# 知識迷宮｜GitHub Pages 預覽版

這是使用國小社會課本第一單元做的靜態互動預覽。此版本使用預先整理的教材資料，不會呼叫 OpenAI API，也不包含原始 PDF。

## 發布到 GitHub Pages

1. 在 GitHub 建立一個新的 **Public** repository，例如 `zhishi-mihang-preview`。
2. 將本資料夾裡的 `index.html`、`.nojekyll` 與 `README.md` 上傳到 repository 根目錄（不要把 ZIP 本身當作網站檔案上傳）。
3. 開啟 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 下，將 Source 選成 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/(root)`，按 **Save**。
6. 等待 GitHub Pages 部署完成後，在 Settings → Pages 頁面開啟顯示的網站網址。Project site 的網址通常是 `https://你的GitHub帳號.github.io/zhishi-mihang-preview/`。

## 注意事項

- GitHub Pages 是靜態網站主機；此版本的示範互動可在瀏覽器執行，但 API 依賴的 PDF 分析、即時 AI 教學、生成題目與自動提示尚未連接。
- 若使用 GitHub Free，GitHub Pages 需要 Public repository；發布的網站會公開給網路使用者。請勿上傳 API Key、密碼或敏感資料。
- 此專案不包含上傳者提供的原始 PDF 檔案。
