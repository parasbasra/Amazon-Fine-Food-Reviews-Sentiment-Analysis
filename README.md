
# 📦 Amazon Fine Food Reviews — Sentiment Analysis Project

This is an end-to-end **Sentiment Analysis project** built on the Amazon Fine Food Reviews dataset. It combines **data cleaning**, **exploratory analysis**, **machine learning modeling**, and **Power BI dashboarding** to deliver clear insights into customer reviews.

---

## 🧠 Objective

To identify whether a review is **positive** or **negative** based solely on its text.  
This project simulates a real-world NLP pipeline using Python and Power BI.

---

## 🔍 Dataset Overview

- **Source**: [Amazon Fine Food Reviews dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- **Total records after cleaning**: ~390,000
- **Key columns used**:
  - `Score`: Original numerical rating (used to define sentiment)
  - `Text`: Actual review content

---

## 🧹 Step 1–5: Data Preparation

- Removed irrelevant or duplicate columns
- Dropped null values
- Created a new **binary Sentiment column**:
  - Positive (`Score` ≥ 4) → 1
  - Negative (`Score` ≤ 2) → 0
  - Neutral scores (3) were excluded
- Resulting dataset was filtered to around **390,000 clean reviews**

---

## 🧼 Step 6: Text Preprocessing

Applied NLP techniques:
- Lowercasing
- Punctuation and number removal
- Stopword removal (using NLTK)
- Lemmatization

This ensured the model receives clean, minimal, and meaningful text data.

---

## 📊 Step 7: Model Training & Evaluation

### TF-IDF Vectorization
- Converted text to numeric form using **TF-IDF vectorizer**
- Used top 5000 features for model input

### Models Tried
- **Logistic Regression**
- **Multinomial Naive Bayes**
- **Random Forest**
- **Gradient Boosting**
- **SVC**

### Observations:
- All models achieved ~85% accuracy
- Reason: Class imbalance (85% of reviews are positive)
- Upsampling or full dataset training could improve performance

---

## 📈 Step 8: Power BI Dashboard

- Cleaned CSV exported to Power BI
- Dashboard includes:
  - Review volume trends
  - Sentiment distribution
  - Top reviewers & products
  - Word cloud of common review terms

🔗 *Power BI file included in this repo*

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `Amazon Fine Food Reviews Sentiment Analysis.ipynb` | Full Python notebook for cleaning, modeling |
| `Cleaned_Amazon_Reviews.csv` | Final cleaned data used in Power BI |
| `Amazon_Food_Review_Dashboard.pbix` | Power BI dashboard file |
| `BI_Screenshots.pdf` | Power BI dashboard file |
| `README.md` | Project summary and documentation |

---

## 📌 Summary

This project showcases:
- Text classification pipeline for sentiment analysis
- Preprocessing steps using NLP
- Use of traditional ML models
- Business insights visualized in Power BI

It simulates a real-world case where a company wants to monitor and analyze **customer satisfaction** based on review text.

---

> 📬 For any queries or feedback, feel free to reach out!
