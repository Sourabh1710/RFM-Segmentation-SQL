# 🧮 E-commerce RFM Segmentation (SQLite + Python)

A complete RFM (Recency, Frequency, Monetary) analysis project using Python, SQLite, and Jupyter Notebook on a real-world e-commerce dataset.

---

## 📌 Project Overview

This project simulates a real-world marketing analytics use case for customer segmentation using RFM scores. It helps identify high-value customers (Champions, Loyal, At Risk) based on their purchase behavior.

We used a cleaned online retail dataset and applied SQL queries within Jupyter to derive customer insights.

---

## 🎯 Objectives

- Segment customers based on Recency, Frequency, and Monetary scores
- Build a reusable SQL workflow to calculate RFM metrics
- Interpret and label customer segments for marketing strategies
- Prepare a job-ready project that can be explained in interviews using the STAR method

---

## 🛠 Tools & Libraries

- **Python** (Jupyter Notebook)
- **SQLite** (via `sqlite3`)
- **Pandas** for data manipulation
- **Real e-commerce dataset** from Kaggle

---

## 📊 RFM Logic

| Metric     | Description                                 |
|------------|---------------------------------------------|
| **Recency**    | Days since last purchase                    |
| **Frequency**  | Number of unique transactions per customer  |
| **Monetary**   | Total revenue contributed by each customer  |

We used quantile binning to assign scores from 1 (lowest) to 5 (highest), and combined these into a single RFM Score (e.g., 555 = Champion).


---

## 📁 Project Files

| File                            | Description                              |
|---------------------------------|------------------------------------------|
| `Online Retail.csv`             | Cleaned dataset used for analysis        |
| `Ecommerce_RFM_Segmentation.ipynb` | Jupyter Notebook with full SQL + logic |
| `README.md`                     | This project summary file                |
| - **Source**                    | Kaggle — [UK RRetail Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data) |

---

## 📘 Learning Outcome

- Applied SQL inside a Jupyter notebook using SQLite
- Practiced end-to-end data analysis using real customer transactions
- Gained confidence in creating job-ready, segment-focused analytics projects

---

## 👤 Author

**Sourabh Sonker**  
Aspiring Data Scientist

---
