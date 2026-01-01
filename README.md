# 📦 Amazon Fine Food Reviews — Customer Sentiment Analysis

Analysis of large-scale Amazon Fine Food customer reviews to understand sentiment patterns, review behavior, and customer satisfaction trends.  
This project focuses on **data preparation, exploratory analysis, and insight generation**, with sentiment analysis used as a supporting technique and results visualized in Power BI.

---

## 🧠 Project Objective

To analyze customer review text and ratings in order to:
- Understand overall customer sentiment
- Identify patterns in positive and negative feedback
- Support business and product insights using large volumes of unstructured data

The goal of the project is **analysis and interpretation**, not model optimization.

---

## 🔍 Dataset Overview

- **Source**: Amazon Fine Food Reviews dataset (Kaggle)
- **Records analyzed**: ~390,000 cleaned reviews
- **Key fields**:
  - `Score`: Star rating provided by customers
  - `Text`: Review content
  - Derived sentiment labels used for analysis

---

## 🧹 Data Preparation & Exploration

- Removed irrelevant and duplicate columns
- Handled missing values
- Defined sentiment categories based on review scores:
  - Positive (Score ≥ 4)
  - Negative (Score ≤ 2)
  - Neutral reviews excluded to reduce ambiguity
- Performed initial exploration of rating distribution and review characteristics

---

## 🧼 Text Processing (Supporting Analysis)

- Basic text cleaning and normalization
- Removal of noise such as punctuation and stopwords
- Lemmatization to standardize review text

These steps enabled consistent analysis of customer feedback at scale.

---

## 📊 Exploratory & Sentiment Analysis

- Examined distribution of positive vs negative reviews
- Analyzed review volume and sentiment trends
- Used standard, off-the-shelf sentiment techniques to support observed patterns
- Focused on understanding **what customers are saying**, not on maximizing predictive performance

---

## 📈 Power BI Dashboard

- Exported prepared data into Power BI for visualization
- Dashboard highlights:
  - Review volume and sentiment distribution
  - Trends over time
  - Frequently occurring review terms
- Designed for business users to explore customer feedback interactively

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Amazon Fine Food Reviews Sentiment Analysis.ipynb` | Python notebook for data preparation and analysis |
| `Cleaned_Amazon_Reviews.csv` | Processed dataset used for BI |
| `Amazon_Food_Review_Dashboard.pbix` | Power BI dashboard |
| `BI_Screenshots.pdf` | Dashboard screenshots |
| `README.md` | Project documentation |

---

## 💡 Business Value

This analysis demonstrates how large volumes of unstructured customer feedback can be transformed into:
- Actionable insights on customer satisfaction
- High-level sentiment trends
- Supporting evidence for product, quality, and CX discussions

---

## 👤 Author

Paras Basra
