# 📊 YouTube Trending Video Analytics (India)

**Elevate Labs - Data Analyst Internship Project | July 2025**

## 📌 Project Overview

This project analyzes trending YouTube videos in India to uncover patterns in content performance, engagement, and virality. A dynamic Power BI dashboard was developed to present insights into categories, trends over time, and key viewer interactions.

---

## 🧠 Objectives

- Identify which content categories trend the most.
- Determine the average duration a video remains trending.
- Analyze engagement rates and performance metrics.
- Create a dashboard for interactive exploration of the data.

---

## 🛠️ Tools & Technologies

- **Python (pandas)**: Data preprocessing and cleaning
- **Power BI**: Interactive data visualizations and dashboard
- **Excel**: Basic sanity checks and formatting

---

## 🧾 Dataset

- **Source**: YouTube Trending Videos Dataset (India-specific `INvideos.csv`)
- **Attributes Used**: `title`, `views`, `likes`, `dislikes`, `comment_count`, `category_id`, `publish_time`, `trending_date`

---

## 🔄 Steps Followed

1. **Data Collection & Cleaning**:
   - Parsed datetime columns
   - Removed duplicates
   - Standardized column formats

2. **Metric Engineering**:
   - Trending duration
   - Engagement rate = Likes / Views
   - Like-to-Dislike ratio
   - Extracted month & year from publish date

3. **Visualization & Dashboard** (Power BI):
   - 📈 Bar Chart: Avg. Views by Category
   - 📅 Line Chart: Views Over Time
   - 🧮 KPI Cards: Total Views, Likes, Comments
   - 📋 Table: Top 10 Trending Videos
   - 📊 Histogram: Video Trending Duration
   - 🍩 Donut Chart: Like vs Dislike Ratio
   - 🔍 Slicers/Filters: Month, Category ID

---

## 📍 Key Insights

- 📆 Average trending duration: **3–4 days**
- 🎵 Music & Entertainment are the top trending categories
- 📈 High engagement in regional and music content
- 🕒 Mid-week (Wed–Fri) uploads tend to trend more
- 👍 Likes & comments positively influence trending duration

---

## ✅ Conclusion

This analysis helps content creators and marketers understand viewer behavior on YouTube. Data-driven decisions around content type, publishing time, and engagement strategies can be enhanced using these insights.

---

## 🚀 Future Scope

- Multi-country YouTube dataset integration
- Sentiment analysis on titles and tags
- NLP on comments for emotion & feedback insights

---

## 📁 Project Structure

