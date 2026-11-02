# 拍照排行程

拍下回診單、繳費單、預約卡等，自動讀出日期，再一鍵加進 Google 日曆或 iPhone 日曆（附提醒）。

## 使用方式
1. 用手機打開網頁（GitHub Pages 網址）。
2. 第一次使用：展開「設定 API 金鑰」，貼上 Anthropic API 金鑰（到 console.anthropic.com 建立）。金鑰只存在這支手機的瀏覽器裡。
3. 按「拍照／選照片」，等 10–30 秒，確認或修改內容。
4. 按「加入 Google 日曆」或「加入 iPhone 日曆（.ics）」。

iPhone 可以在 Safari 按「分享 → 加入主畫面」，當成 App 使用。

## 檔案
- `index.html`：整個 App（純網頁，不需要伺服器）
- `manifest.json`：加入主畫面用
