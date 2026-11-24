# HR Analytics｜課前預習手冊

以原課程 83 頁簡報順序編排的繁體中文學習網站，提供 12 章導讀、專業參考來源、章末練習、自我檢核與學習筆記。

網站：https://SteveMarauder.github.io/HR_Analytics_mainpage/

## 使用方式

直接開啟 `index.html`，或在本目錄執行 `python -m http.server 8765` 後開啟 http://localhost:8765 。不需要安裝 npm 套件或執行建置。

## 檔案

- `index.html`：網站入口。
- `style.css`：響應式版面、深淺色主題與列印樣式。
- `app.js`：章節路由、互動示例、筆記與進度。
- `content.js`：12 章內容、17 個外部來源及練習設計。
- `slides.js`：原簡報 83 頁逐頁對照。
- `materials/`：僅在本機保留的原課程 PDF 與 7 個 Excel 教材副本，未改寫，不推送 GitHub。
- `.nojekyll`：讓 GitHub Pages 直接發布靜態檔案。

## 預習章節與簡報頁碼

1. HR Analytics 與分析四階段：1–11
2. HR 指標與招募衡量：12–17
3. KPI 與資料敘事：18–20
4. 人力預測與規劃：21–23
5. 績效考核與接班指標：24–27
6. 薪酬管理指標：28–29
7. 薪資分析與線性迴歸：30–35
8. 人才管理與九宮格：36–47
9. 人才流失與離職指標：48
10. 留任預測與邏輯斯迴歸：49–54
11. 訓練與發展衡量：55–57
12. 分群與 K-means：58–83

## 來源與資料

課程架構、原指標與案例來自使用者提供的 `HR People Analytics Presentations.pdf`。網站中文為整理轉述；外部來源可在網站「參考來源與編輯說明」查閱。補充來源包括 CIPD、NIST、ASA、BLS、scikit-learn 官方文件、Kirkpatrick Partners 及 OTexts 專業著作，查核日期 2026-11-24。教材的疑義在相應章節就地說明。

教學數字及互動示例不代表真實員工或原 Excel 資料的分析結果。練習檔保持原貌，網站未宣稱已完成活頁簿建模。

筆記與進度只保存在目前瀏覽器的 localStorage，無後端資料庫、不跨裝置同步，可匯出 Markdown 筆記。Google Fonts 與外部來源需要網路；離線會採系統字型。

## 發布與更新

GitHub Pages 設為 `main` 分支的根目錄 `/`。更新上述網站檔案後，提交並推送 main，GitHub Pages 會重新發布。原教材目錄、ZIP 及 `materials/` 均透過 `.gitignore` 排除，不公開上傳。

公開網站保留教材檔名與83頁對照，沒有原始 PDF／Excel 下載連結。在本機開啟 `index.html`，或透過 localhost／127.0.0.1 預覽時，網站會顯示教材存取按鈕。學習內容、專業來源、練習、互動示例、筆記及進度在公開版均可使用。

本儲存庫不對原課程教材或外部來源重新授權；其權利歸各權利人。
