# Google Trends 商業環境監測儀表板 — Market Intelligence Dashboard

每週**全自動爬取** Google Trends 台灣商業熱搜，白名單過濾、趨勢分類、10 大主題聚合，以互動式儀表板呈現總體商業環境動向。

## 🔍 專案概述

業務與行銷團隊需要掌握市場脈動，但 Google Trends 原始介面難以跨週比較，熱搜也混雜大量娛樂新聞。本系統以 Selenium 自動爬取，商業白名單過濾雜訊，自動分類趨勢方向，生成互動式 HTML 儀表板並發布至 GitHub Pages。

## 📈 功能特色

- 每週自動更新（Windows Task Scheduler + Selenium headless Chrome）
- 10 大商業主題聚合（AI 科技 / 半導體 / 地緣政治 / 製造轉型 等）
- 4 種趨勢方向：★ 新興 / ↑ 上升 / → 持平 / ↓ 下降
- Sparkline 微折線圖、URL 狀態記憶、CSV 匯出

## 🛠 技術棧

Python · Selenium · Chart.js 4.4 · Papermill · GitHub Pages · Windows Task Scheduler

## 🌐 作品集頁面

詳細說明請見：**[https://yujuigato.github.io/google-trends-dashboard/](https://yujuigato.github.io/google-trends-dashboard/)**

## 📊 即時儀表板

**[https://yujuigato.github.io/google-trends-dashboard/dashboard/](https://yujuigato.github.io/google-trends-dashboard/dashboard/)**（每週自動更新）

---

> 爬蟲原始碼不公開，此 repo 僅含作品集說明頁。
