# PRODIGY_DS_04
sentiment-analysis twitter nlp python data-science internship prodigy-infotech wordcloud matplotlib pandas
# 🐦 PRODIGY_DS_04 — Twitter Sentiment Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%20|%20Matplotlib%20|%20Seaborn%20|%20WordCloud-green)
![Internship](https://img.shields.io/badge/Prodigy%20InfoTech-Data%20Science%20Internship-purple)
![Task](https://img.shields.io/badge/Task-04-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Task Objective

> Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

---

## 📂 Dataset

- **Source:** [Twitter Entity Sentiment Analysis — Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- **File Used:** `twitter_training.csv`
- **Columns:** `TweetID`, `Entity`, `Sentiment`, `Tweet`
- **Sentiment Labels:** Positive, Negative, Neutral, Irrelevant

---

## 🛠️ Libraries Used

| Library | Purpose |
|--------|---------|
| `pandas` | Data loading & manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Plotting & visualization |
| `seaborn` | Advanced visualizations |
| `wordcloud` | Word cloud generation |
| `nltk` | Text preprocessing & stopwords |
| `re` | Regular expressions for text cleaning |

---

## 🔄 Workflow

1. **Data Loading** — Loaded `twitter_training.csv` with custom column names
2. **Data Cleaning** — Handled null values, converted types
3. **Text Preprocessing** — Removed URLs, mentions, punctuation, stopwords
4. **Visualization** — Created 6 insightful plots
5. **Insights** — Summarized sentiment distribution and brand-level patterns

---

## 📊 Visualizations

| # | Chart | Description |
|---|-------|-------------|
| 1 | Bar Chart | Overall sentiment distribution |
| 2 | Pie Chart | Sentiment percentage share |
| 3 | Grouped Bar | Sentiment breakdown by brand/entity |
| 4 | Word Cloud (Green) | Most frequent words in Positive tweets |
| 5 | Word Cloud (Red) | Most frequent words in Negative tweets |
| 6 | Heatmap | Sentiment intensity across entities |

---

## 💡 Key Insights

- The dataset contains tweets across multiple brands and topics
- Sentiment distribution reveals which brands receive the most positive/negative attention
- Word clouds highlight common language used in positive vs negative tweets
- Heatmap clearly shows which entities are most polarizing

---

## 🗂️ File Structure
