# Grocery Sales Analysis & Customer Behaviour (FMCG)

An end-to-end **Data Analysis project** focused on understanding sales performance,
product dynamics, and customer behaviour in the FMCG (grocery retail) industry.
This project follows the **CRISP-DM framework**, combining large-scale transactional
analysis with **RFM customer segmentation** to deliver actionable, business-driven insights.

---

## 🔍 Business Problem

The company lacks clear visibility into:
- Which customers contribute the most to revenue
- How purchasing behaviour differs across customer segments
- Which products and categories act as true revenue drivers
- How sales fluctuate over time for effective operational planning

Without these insights, decisions related to **customer retention, inventory management,
and growth strategy** become inefficient and high-risk.

---

## 🎯 Project Objectives

- Analyze **sales patterns and revenue stability**
- Evaluate **product and category performance**
- Understand **customer behaviour using RFM analysis**
- Identify and profile **high-value customer segments**
- Provide **actionable recommendations** aligned with business goals

---

## 🗂 Dataset Overview

- **6.7M+ transaction records**
- **98.7K customers**
- **452 products across 11 categories**
- **96 cities | 206 countries**
- Time period: **January – May 2018**
- Multi-table relational structure:
  - Sales
  - Products
  - Customers
  - Categories
  - Geography

> Raw data is not included in this repository due to file size limitations.
> The dataset is publicly available on Kaggle and fully reproducible.

---

## 🛠 Data Preparation & Processing

Key preprocessing steps include:
- Integration of **7 relational tables** into a single analytical dataset
- Revenue correction using the formula:

  `Revenue = Price × Quantity × (1 − Discount)`

- Date and data type standardization
- Treatment of missing values (~1%) using mode imputation
- Outlier assessment, confirming skewed distributions as valid business behaviour
- Final analytical dataset: **6.7M rows and 14 key analytical features**

Detailed documentation is provided in the `data/` and `notebooks/` folders.

---

## 📊 Exploratory Data Analysis (EDA)

### Sales Patterns
- Business performance is driven by **high transaction frequency**, not large single purchases
- Revenue remains relatively stable with a mild **seasonal dip in February**
- Sales patterns indicate strong dependency on **customer retention**

### Product & Category Performance
- Revenue is dominated by **processed and sweet food categories**
- Fresh products exhibit:
  - Higher value per transaction
  - Lower purchase frequency
- No category shows independent decline, indicating **habitual consumption behaviour**

---

## 👥 Customer Behaviour – RFM Analysis

Customers are segmented based on:
- **Recency** (how recently customers purchased)
- **Frequency** (how often they purchased)
- **Monetary value** (how much they spent)

Key findings:
- **Champions, Big Spenders, and Loyal Customers** contribute the majority of revenue
- The **“Others” segment** represents the largest customer base but generates relatively low value
- **Customer quality outweighs customer quantity** in revenue contribution

The final customer-level RFM dataset is included in the repository for transparency.

---

## 💡 Key Insights

- Approximately **29% of customers generate around 50% of total revenue**
- Current sales patterns are **not secure without strong retention strategies**
- High-value customers are clearly identified and well-segmented
- Significant opportunity exists to **upgrade mid–low value customers** into higher-value segments

---

## 📈 Recommendations

- Prioritize **retention strategies** for high-value customer segments
- Increase **purchase frequency** within processed food categories
- Position fresh products as **high-value add-ons**, not volume drivers
- Shift focus from mass acquisition to **customer upgrading**
- Incorporate **seasonal effects** into inventory planning and promotions

---

## 📊 Interactive Dashboard

The insights from this project are visualized through an interactive Tableau dashboard.

🔗 **Tableau Public Dashboard:**  
https://public.tableau.com/app/profile/iftanul.ibnu.rochman/viz/FinalProjectDataAnalysis_17661336492120/Overview?publish=yes

---

## 🧠 Tools & Skills

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Exploratory Data Analysis (EDA)
- RFM Customer Segmentation
- SQL-style analytical thinking
- Data Visualization (Tableau)
- Business Insight & Storytelling
- CRISP-DM Framework

---

## 👤 Author

**Iftanul Ibnu Rochman**  
Data Analyst | Data Science
