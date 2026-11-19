# Tableau Desktop Specialist 題庫

為準備 **Salesforce Certified Tableau Desktop Foundations**（舊名 Tableau Desktop Specialist）整理的中英對照練習題庫，附計時模擬考與弱點分析。單一 HTML 檔案，不需安裝任何東西。

👉 **線上版：** https://sherr89112-glitch.github.io/tableau-exam-bank/

## 功能

| 模式 | 說明 |
|---|---|
| 模擬考 | 45 題 / 60 分鐘，依官方領域權重（25 / 35 / 25 / 15）抽題，交卷後才顯示對錯與解析 |
| 主題練習 | 依 30 個主題分類練習，送出答案後立即顯示解析 |
| 紀錄與弱點 | 作答歷史、分數趨勢、各領域與各主題的正確率 |
| 題庫總覽 | 305 題全文搜尋，可依領域篩選 |
| 名詞對照 | 91 個常見中英名詞與解釋 |
| 設定 | 字體大小（5 段）、配色（淺色／深色／跟隨系統） |

作答時題目與選項**全部是英文**（跟真實考場一致），中文題意會在看解析時出現。作答紀錄存在瀏覽器的 localStorage，不會上傳到任何地方。

## 內容

- **305 題**，逐題整理自 YouTube 上的 Tableau 考題講解影片（36 支）
- 每題含英文原題、中文題意、正確答案、中文解析（說明為什麼對、以及陷阱選項錯在哪）
- 答案以官方文件（help.tableau.com）核對過；少數影片答案有爭議之處，已在解析中註明

## 檔案

```
index.html                         練習頁（打開就能用，也可直接存到手機）
data/questions.json                題庫原始資料
data/tableau-question-bank.md      依領域／主題分組的閱讀版
data/tableau-question-bank.csv     匯入 Anki / Quizlet 用（含 UTF-8 BOM，Excel 可直接開）
data/glossary.json                 中英名詞對照
pdf/tableau-handbook.pdf           考前重點＋名詞小抄（橫式 A4，列印用）
pdf/tableau-keypoints.pdf          一頁式考前重點
pdf/tableau-cheatsheet.pdf         名詞小抄（直式／橫式）
```

## 考試資訊

45 題（40 題計分 + 5 題不計分的研究題）／ 60 分鐘 ／ 750 分通過（100–1000 級距，約 70%，需答對 32 題）。單選與複選，無實作題。考試費用 US$75，第一次重考免費。

## 來源與聲明

題目整理自 YouTube 上公開的考題講解影片（[Big Tech Mindset](https://www.youtube.com/@bigtechmindset) 與 AllAboutDATA 兩個系列），中文題意與解析為自行整理註記。

這是**非官方的個人讀書筆記**，與 Salesforce、Tableau 沒有任何關係，也不保證題目會出現在真實考試中。請以 [Tableau 官方文件](https://help.tableau.com/) 與 [Salesforce 認證頁面](https://trailhead.salesforce.com/credentials/) 為準。

## 授權

程式碼與頁面：MIT。題目內容來自第三方教學影片，僅供個人學習使用。
