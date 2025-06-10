# EDA
Expository Data Analysis 
# 📊 Netflix Movies and TV Shows – Exploratory Data Analysis (EDA)

Welcome to my Netflix EDA project! This notebook provides a deep dive into the Netflix catalog using Python, Pandas, Seaborn, and NLP techniques. The goal is to understand patterns in Netflix's content strategy, uncover hidden trends, and derive actionable business insights.

---

## 🧠 Objective

- Analyze Netflix’s publicly available dataset (`netflix_titles.csv`)
- Understand content trends over time, genres, audience ratings, and regions
- Perform sentiment analysis on content descriptions
- Provide business insights to improve strategy and user engagement

---

## 📁 Dataset

- 📦 Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- 📊 Rows: ~8800
- 🧾 Columns: `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🔧 Tools & Libraries Used

- **Python**
- **Pandas** & **NumPy** – Data handling
- **Matplotlib** & **Seaborn** – Visualization
- **NLTK (VADER)** – Sentiment Analysis
- **WordCloud** – Text Visualization

---

## 📌 Key Questions Explored

- What type of content dominates Netflix: movies or TV shows?
- Which countries contribute the most content?
- How has Netflix's content changed over time?
- What are the most common genres and audience ratings?
- What kind of sentiment is reflected in content descriptions?

---

## 🔍 Highlights of the Analysis

- **Movies make up ~70%** of Netflix’s catalog.
- **Most content is rated TV-MA**, indicating adult-oriented content.
- Content additions **peaked during 2018–2020**.
- **Drama, Comedy, and Documentaries** are top genres.
- **The US, India, and UK** dominate content production.
- **Sentiment analysis** reveals that most content descriptions are neutral or slightly positive.

---

## 📈 Sentiment Analysis Results

- Used **VADER** from `nltk.sentiment` to analyze `description` text.
- Classified content into **Positive**, **Neutral**, or **Negative**.
- Found correlations between sentiment and genres, content type, and audience focus.
- Derived business insights based on emotional tone distribution.

---

## 🧠 Business Insights Derived

- ✅ TV shows are underutilized; Netflix can boost engagement with more serial content.
- 🌍 Strong US content bias; opportunity in underrepresented regions (e.g., Africa, Southeast Asia).
- 🧒 Low volume of family/kids content — untapped demographic.
- 📈 Positive sentiment descriptions are linked with higher discoverability.
- 📝 Rewriting descriptions with more emotional pull can increase click-through and watch-start rates.



