# 💬 Sentiment Patterns in Social Media Data (Power BI)

This project explores sentiment trends in social media posts (e.g., tweets, comments, reviews) using Power BI. The goal is to visualize emotional reactions (positive, negative, neutral) over time, by region, by topic, and by platform. It helps identify how public sentiment shifts in response to events, brands, campaigns, or news.

---

## 🧠 Abstract

Social media platforms generate millions of posts every day reflecting real-time human emotions. This project uses processed sentiment data—classified using NLP techniques—and visualizes patterns across time, location, and topics in Power BI. The dashboard enables marketers, analysts, and decision-makers to track emotional responses and public opinion with clarity and speed.

---

## 🚀 Key Features

- 📊 **Sentiment Breakdown**: Positive / Negative / Neutral metrics
- 📈 **Time Series Analysis**: Sentiment over days, weeks, or months
- 🌍 **Regional Insights**: Sentiment by country or state (map view)
- 🔍 **Topic Filters**: Explore sentiment for specific hashtags, keywords, or brands
- ☁️ **Word Clouds**: Most frequent words in positive vs. negative posts
- 📌 **Slicers and Drill-Downs**: Custom filtering by platform, topic, or sentiment type

---

## 🧰 Technology Stack

| Component         | Tool/Tech                         |
|------------------|-----------------------------------|
| **Data Source**   | CSV or Excel (Twitter/Reddit output) |
| **Data Processing** | Python (for NLP: VADER/TextBlob) or preprocessed dataset |
| **Data Viz**      | Power BI Desktop                   |
| **Modeling**      | Power BI Data Model (DAX measures, calculated columns) |
| **Hosting**       | GitHub Repository                  |

---

## 🔄 Workflow

1. **Data Collection**  
   - Tweets/posts scraped via APIs or loaded from datasets (e.g., Kaggle Twitter Sentiment CSV)

2. **Sentiment Classification (Outside Power BI)**  
   - Sentiment labels generated using Python (TextBlob/VADER/BERT)
   - Output CSV includes: `text`, `timestamp`, `user_location`, `sentiment`, `platform`, `topic`

3. **Data Import & Modeling**  
   - Clean and load data in Power BI
   - Create DAX measures: sentiment count, sentiment %, most used words, etc.

4. **Visualization Design**  
   - Time-based line charts, bar plots by topic, maps, cards, slicers
   - Interactive page filters: by platform, region, date, and sentiment

---

## 📊 Dashboard Preview

<img width="1346" height="748" alt="Power BI Desktop 7_3_2025 3_42_38 PM" src="https://github.com/user-attachments/assets/f762c159-c8ea-4d89-a0df-f715ec424c5d" />


---

## 📂 Repository Structure

social-media-sentiment-powerbi/
  
  ├── data/
  
  │ └── twitter_sentiment.csv
 
  ├── report/
   
   └── Sentiment_Dashboard.pbix
 
  ├── images/
 
  │ └── sentiment_dashboard_preview.png
 
  ├── README.md
 
  └── LICENSE
