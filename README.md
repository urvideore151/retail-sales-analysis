# Online Retail Data Analysis

This project was completed as part of the **Tata Data Visualisation: Empowering Business with Effective Insights** Virtual Experience on **Forage**.

Using Python, I analyzed an online retail dataset to identify revenue trends, customer behavior, and business opportunities by answering business-focused questions from the CEO's and CMO's perspectives.

---
## Project Overview

The objective of this project was to clean and analyze retail transaction data, create meaningful visualizations, and communicate insights that could support business decision-making.

The analysis focuses on understanding sales performance, identifying high-value customers, evaluating international markets, and exploring product demand across different countries.

---
## Dataset

- **Dataset:** Online Retail Dataset
- **Source:** UCI Machine Learning Repository
- **Records:** 541,909 retail transactions
- **Period:** December 2010 – December 2011

The dataset contains transaction details such as invoice numbers, products, quantities, prices, customer IDs, and countries.

---
## Tech Stack

- Python
- Pandas
- Matplotlib
- Plotly
- Google Colab

---
## Data Cleaning

Before starting the analysis, the dataset was cleaned to ensure accurate results.

The following preprocessing steps were performed:

- Removed returned or cancelled transactions (negative quantities)
- Removed records with zero unit price
- Created a new **Revenue** column using:

```python
Revenue = Quantity × UnitPrice
```

---
## Business Questions Answered

- How does monthly revenue change throughout the year?
- Which countries generate the highest revenue (excluding the UK)?
- Who are the top revenue-generating customers?
- Which countries show the highest product demand?

---
## Visualizations & Insights

### 📈 Monthly Revenue Trend
Revenue remained relatively stable for most of the year before increasing significantly in **November**, indicating strong seasonal demand during the festive period.

**Business Insight:** Businesses should prepare inventory and marketing campaigns ahead of peak sales periods.

---
### 🌍 Top Countries by Revenue & Quantity
After excluding the UK, countries such as **the Netherlands, EIRE, and Germany** generated the highest revenue.

**Business Insight:** These markets present strong opportunities for future business expansion.

---

### 👥 Top Customers by Revenue
A small group of customers contributes a significant portion of the company's revenue.

The **Top 10 customers contribute approximately 17.26% of the total revenue.**

**Business Insight:** Retaining these customers through loyalty programs and personalized offers could have a meaningful impact on long-term revenue.

---

### 🗺️ Demand by Country
Demand varies across different countries, with several regions showing consistently higher purchasing activity than others.

**Business Insight:** Understanding regional demand can help businesses plan marketing strategies and identify new growth opportunities.

---

## Repository Structure

```
Online-Retail-Data-Analysis/
│
├── Data_Analysis.ipynb
├── README.md
├── requirements.txt
│
├── data/
│   └── Online Retail Data Set.csv
│
└── images/
    ├── q1_monthly_revenue.png
    ├── q2_top_countries.png
    ├── q3_top_customers.png
    └── q4_map.png
```
## Acknowledgements

This project was completed as part of the **Tata Data Visualisation: Empowering Business with Effective Insights** Virtual Experience Program by **Forage**.

---

## Author

**Urvi Deore**

Artificial Intelligence Engineering Student | Aspiring Data Analyst
