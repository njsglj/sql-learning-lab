# SQL LAB｜資料庫查詢實驗室

互動式 SQL 練習網站，以虛構 COMPANY 公司人員與專案管理資料庫為案例。網站採用 HTML、CSS、JavaScript 與 SQLite WASM（sql.js），不需要後端伺服器。

## 網站功能

1. **案例背景**：說明人資人員、部門主管與專案協調人員的資料需求。
2. **資料庫設計**：提供 6 張資料表的 ERD、PK/FK 欄位說明與 45 筆樣本資料。
3. **查詢操作**：提供 8 道 SQL 練習，可修改 SQL、執行查詢並查看結果或 SQLite 錯誤訊息。
4. **結果比較**：比較未加 WHERE 與加入薪資條件後的查詢結果，說明資料筆數變化原因。

## 使用方式

- 開啟網站後，點選「查詢練習」。
- 從左側選擇題目，修改 SQL 後按「執行 SQL」。
- 也可使用 Ctrl+Enter 快速執行。
- 為避免破壞示範資料，查詢區僅允許 SELECT、WITH、EXPLAIN。

## 技術與部署

- SQLite WASM：透過 sql.js 在瀏覽器本機執行 SQL。
- GitHub Pages：由 `.github/workflows/pages.yml` 在推送至 `main` 時自動部署。
- 若首次啟用 Pages，請至 Repository → Settings → Pages，確認 Build and deployment 的 Source 設為 **GitHub Actions**。

## 專案網址

https://github.com/njsglj/sql-learning-lab

GitHub Pages 預定網址：https://njsglj.github.io/sql-learning-lab/

> 樣本公司、員工與專案資料均為虛構教學資料。
