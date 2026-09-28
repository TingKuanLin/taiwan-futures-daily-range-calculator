# 日均振幅計算器

這是一個可直接部署到 Vercel 的靜態 HTML 網頁，入口檔案為 `index.html`。

## 內容

- 大台 TX、小台 MTX、微台 TMF
- 60 個日盤交易日的日均振幅
- 母體／樣本標準差切換
- 每 N 個月、每 N 個交易日、每次查詢重算
- 逐日明細與 CSV 匯出
- 可匯入新版 FinMind 日盤 CSV

## Vercel 部署

1. 將此資料夾推送到 GitHub repository。
2. 在 Vercel 匯入該 GitHub repository。
3. Framework Preset 選 `Other`。
4. Build Command 留空或使用 `npm run vercel-build`。
5. Output Directory 留空。

此專案沒有後端與外部 API，相行情資料已內嵌在 `index.html` 中。
