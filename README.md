# Taipei Nightlife Sentiment Analysis 🇹🇼🍸

**A data engineering and analysis pipeline extracting 5,000+ Google Reviews to uncover market trends in the Taipei nightlife industry.**

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Power BI](https://img.shields.io/badge/Visualization-Power%20BI-f2c811)

## 📌 Project Overview
The Taipei nightlife scene is competitive, with major players like **OMNI, KOR, AI, Wave, Ruff, and Frank** vying for dominance. This project utilizes Python to scrape and clean over **5,000 public Google Reviews**, creating a structured dataset for dashboarding in Power BI.

**Current Stage:** Data Engineering & Cleaning (Completed). Visualization (In Progress).

The goal is to answer:
* Which clubs have the highest customer satisfaction vs. volume?
* What are the most common complaints (e.g., queues, pricing, service)?
* How has sentiment trended over the last 12 months?

## 🛠️ Tech Stack
* **Data Collection:** Python (`playwright`) for dynamic web scraping of infinite-scroll Google Review pages.
* **Data Processing:** `pandas` for cleaning, normalization, and exploding nested datasets.
* **Sentiment Analysis:** (In Progress) Using Python NLTK/TextBlob to score review sentiment.
* **Visualization:** Microsoft Power BI (Dashboarding & Reporting).

## 📂 Dataset & Structure
The Python pipeline exports cleaned CSV files ready for Power BI ingestion:
* `OMNI_reviews_clean_exploded.csv`
* `KOR_reviews_clean_exploded_final.csv`
* `Frank_reviews_clean_exploded_final.csv`
* `AI_reviews_clean_exploded.csv`
* `Ruff - Exploded Dataset Final.csv`
* `wave_reviews_clean_exploded.csv`

## 📊 Dashboard (Coming Soon)
*This section will feature screenshots of the Power BI dashboard visualizing key metrics such as Average Rating by Club, Sentiment Distribution, and Keyword Analysis.*
1. Clone the repository:
   ```bash
   git clone [https://github.com/robimengote/Data-Analysis-of-Taipei-Nightlife.git](https://github.com/robimengote/Data-Analysis-of-Taipei-Nightlife.git)
