# Kabuto 美國現貨直送｜一頁式銷售頁

## 檔案
- `index.html`：完整頁面，可直接用 GitHub Pages 預覽
- `embed-cyberbiz.html`：貼進 Cyberbiz 自訂 HTML 區塊用的片段
- `assets/`：主視覺、夜景圖、首屏影片

## 上線步驟
1. 建立 repo（建議命名 `kabuto-us`），把整個資料夾內容上傳，branch 用 `main`
2. Settings → Pages → Source 選 `main` / `(root)`，等 1–2 分鐘後可用
   `https://<帳號>.github.io/kabuto-us/` 預覽
3. 打開 `embed-cyberbiz.html`，全選複製，貼進 Cyberbiz 的自訂 HTML 區塊
4. 把 `href="#buy"` 換成商品頁網址
5. 素材更新時，重新上傳 `assets/` 內同名檔案即可；jsDelivr 快取更新較慢，
   可暫時把網址的 `@main` 改成 `@<commit 前七碼>` 強制取得新版

## 素材網址規則
`https://cdn.jsdelivr.net/gh/<帳號>/<repo>@main/assets/<檔名>`
repo 需為公開。若改用 GitHub Pages 直接提供素材，網址則是
`https://<帳號>.github.io/<repo>/assets/<檔名>`
