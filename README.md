## 📌 Scrape Most Reviewed News and Tweet
## 📖 Overview
This project automates the process of identifying trending cryptocurrency news based on review counts and tweeting the most impactful articles daily. News articles are scraped, ranked, stored in MongoDB, and the top 3 reviewed news items are tweeted automatically using the Twitter API.

---

## 🚀 Features
- Scrapes trending cryptocurrency news articles.
- Sorts news based on reviewer count.
- Stores news data in MongoDB.
- Shortens article URLs using Bitly.
- Automatically tweets top 3 news items daily.
- Maintains audit logs of tweeted content.

---

## 🧰 Technologies Used
- Python
- Tweepy (Twitter API)
- MongoDB (PyMongo)
- PyShorteners (Bitly API)
- HTMLParser
- Regular Expressions

---

## 📰 How the Script Works
- Fetches daily news data from MongoDB.
- Sorts news based on review count.
- Extracts top 3 reviewed articles.
- Shortens article URLs using Bitly.
- Formats tweet within Twitter’s 280-character limit.
- Tweets the news automatically.
- Stores tweeted data for audit and future reference.

---

## 📸 Output
![Application Screenshot]()

---

## ⚠️ Important Notes
- Do NOT commit API keys to GitHub.
- Use environment variables for production.
- Twitter API rate limits apply.
