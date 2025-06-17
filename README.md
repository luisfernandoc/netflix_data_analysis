# 📺 Netflix Content Analysis – Exploratory Data Analysis (EDA)

This project presents an exploratory analysis of the Netflix catalog using Python and pandas. The goal is to uncover trends in genres, content types, country distribution, and identify niche content areas.

---

## 📊 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Key Questions](#key-questions)
- [Visual Insights](#visual-insights)
- [Observations](#observations)
- [Skills Demonstrated](#skills-demonstrated)
- [Next Steps](#next-steps)

---

## 🔍 Overview
Netflix offers a diverse range of titles across genres, countries, and content types. This project explores:

- Distribution of movies vs. TV shows
- Top genres and their global presence
- Countries with the widest content variety
- Rare or niche genres appearing in few countries

---

## 📁 Dataset
- **Source**: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size**: ~8,800 titles
- **Fields**: title, type, country, date_added, genre, duration, etc.

---

## ❓ Key Questions
1. What are the most common genres?
2. Which countries have the most genre diversity?
3. Which genres appear in only a few countries?

---

## 📊 Visual Insights

### 🎬 Top 10 Most Common Genres
![Common Genres](images/common_genres.png)

---

### 🌍 Countries with Most Genre Variety
![Countries with Most Genres](images/genre_diversity_by_country.png)

---

### 🧭 Rare or Niche Genres (Appearing in ≤ 3 Countries)
![Rare Genres](images/rare_genres.png)

---

## 📌 Observations

- *"International Movies"*, *"Dramas"*, and *"Comedies"* dominate the Netflix catalog globally.
- The United States and the United Kingdom lead in content diversity, suggesting broader licensing and production.
- Genres like *"Anime Features"* are highly concentrated in a few regions, reflecting cultural or licensing constraints.

---

## 💼 Skills Demonstrated
- Data wrangling and cleaning with `pandas`
- String manipulation and data normalization
- Aggregation with `groupby` and `explode`
- Visual storytelling with `matplotlib` and `seaborn`
- Insight generation for business and product decisions

---

## 🚀 Next Steps
- Time-based analysis (release trends by year)
- Content rating distribution
- Dashboard or Streamlit app for interactive exploration
