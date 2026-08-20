# 業務情報看板群 — Business Intelligence Dashboard Suite

三個互動式看板，全自動爬取、AI 逐則分類、GitHub Pages 自動發布：**總體商業環境熱搜監測**、**競品負面新聞監控**、**法規商機訊號偵測**。

## 🔍 專案概述

業務與行銷團隊需要掌握市場脈動、競爭對手動態、法規商機訊號，但這些資料分散、變動快，逐一人工追蹤不切實際。本系列系統以 Selenium／Google News RSS 自動爬取資料，Gemini AI 逐則判斷相關性與分類，生成互動式 HTML 儀表板並自動發布至 GitHub Pages，全程無人值守。

## 📊 三個看板

### 一、總體商業環境監測儀表板
每週自動爬取 Google Trends 台灣商業熱搜，白名單過濾雜訊、4 種趨勢方向分類（新興/上升/持平/下降）、10 大商業主題聚合。

### 二、競品情報看板
每日監控 ERP/CRM 競爭對手的 Google News 負面新聞，Gemini AI 逐則判斷「是否真的與該公司相關」與「是否為負面事件」，避免短公司名（如「正航」「凌越」）誤命中同名不同產業的無關新聞；並依 ERP専屬／ERP同類（BPM/MES/系統整合）分類呈現。

### 三、法規商機看板
每日監控 ESG、資安、碳費等法規動態，用 Gemini 萃取「法規名稱／生效時間／適用對象」；並設計「廣泛偵測」機制，用不綁定特定法規名稱的通用查詢語句，讓 LLM 自動發現清單以外沒預先想到的新興法規主題。

## 🛠 技術棧

Python · Gemini AI · Selenium · Google News RSS · Chart.js 4.4 · Papermill · GitHub Pages · Windows Task Scheduler

## 🌐 作品集頁面

詳細說明請見：**[https://yujuigato.github.io/google-trends-dashboard/](https://yujuigato.github.io/google-trends-dashboard/)**

---

> 爬蟲原始碼不公開，此 repo 僅含作品集說明頁。
