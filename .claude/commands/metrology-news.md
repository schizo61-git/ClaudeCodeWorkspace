Fetch today's latest news from https://metrology.news/ and present a summary in Japanese.

Steps:
1. Use WebFetch on https://metrology.news/ with the prompt: "List all article titles, publication dates, URLs, and any available summaries or descriptions. Focus especially on articles published today or most recently."
2. Identify the most recent articles (today's date or the latest available).
3. For each article (up to 10), fetch the individual article page using WebFetch with the prompt: "Summarize this article in 2-3 sentences. Include the main topic, key findings or announcements, and significance."
4. Present the results entirely in Japanese with this format:

---
# 計測・品質ニュース 最新情報
**取得日時:** [今日の日付]

## 記事一覧

### 1. [日本語タイトル]
**日付:** YYYY年MM月DD日
**カテゴリ:** [カテゴリ名]
**概要:** [2〜3文の日本語要約]
**元記事:** [URL]

### 2. ...
---

Important:
- Translate all titles and summaries into natural Japanese
- Use technical Japanese terminology appropriate for manufacturing/metrology (e.g., 三次元測定機, 光学測定, ロボット計測, 品質保証)
- If fetching individual articles takes too long, use the homepage summaries directly
- Prioritize articles from today, then fall back to the most recent ones available
