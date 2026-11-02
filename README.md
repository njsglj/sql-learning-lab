# SQL LAB｜校園選課資料庫實作

互動式 SQL 練習網站，以校園選課管理系統為案例。網站採用 HTML、CSS、JavaScript 與 SQLite WASM（sql.js），不需要後端伺服器。

## 網站功能

1. **案例背景**：說明教務處、任課教師、系所助教與學生的資料需求。
2. **資料庫設計**：提供 DEPARTMENTS、STUDENTS、COURSES、ENROLLMENTS 四張資料表的 ERD、PK/FK 欄位說明與虛構樣本資料。
3. **查詢操作**：提供 6 道 SQL 練習，可修改 SQL、執行查詢並查看實際結果或 SQLite 錯誤訊息。
4. **結果比較**：比較 LEFT JOIN 與 INNER JOIN 查詢修課人數時，結果筆數與未選課課程的差異。

## 使用方式

- 開啟網站，選擇「SQL 練習」題目。
- 修改 SQL 後按「執行查詢」。
- 可查看預期結果，或將 SQL 改錯以觀察錯誤訊息。
- 資料庫在瀏覽器本機初始化，重新整理後會恢復初始樣本資料。

## 技術與部署

- SQLite WASM：透過 sql.js 在瀏覽器本機執行 SQL。
- GitHub Pages：由 `.github/workflows/pages.yml` 在推送至 `main` 時自動部署。
- 首次部署時，workflow 會透過 configure-pages 設定 Pages 的 GitHub Actions 部署來源。

## 專案網址

- Repository：https://github.com/njsglj/sql-learning-lab
- GitHub Pages：https://njsglj.github.io/sql-learning-lab/

> 學生、教師、系所與選課資料均為虛構教學資料。
