# E-Commerce Customer Intelligence

An end-to-end **E-Commerce Data Analytics project** built using **Python, SQL, and Power BI** to analyze customer behavior, sales performance, product performance, discount usage, subscription behavior, and purchasing patterns.

The project follows a complete analytics workflow:

**Business Problem → Python EDA → SQL Analysis → Power BI Dashboard → Business Insights → Recommendations**

---

## Dashboard Preview

### Page 1 — Executive & Sales Overview

![Executive & Sales Overview](assets/dashboard-page-1.png)

### Page 2 — Customer & Purchase Insights

![Customer & Purchase Insights](assets/dashboard-page-2.png)

---

## Business Problem

E-commerce businesses generate a large amount of customer and transaction data. However, raw data does not directly explain where revenue comes from, which customers are most valuable, or which products and purchasing behaviors require attention.

This project aims to answer key business questions:

- Which product categories generate the most revenue?
- Which products are top revenue contributors?
- Which customer segments contribute most to revenue?
- Which age groups contribute more to sales?
- How does gender relate to revenue?
- How does subscription status affect revenue?
- How do discounts relate to purchase volume?
- Which seasons generate higher revenue?
- Which payment methods generate more revenue?
- What opportunities exist for customer retention and cross-selling?

### Business Objective

The main objective is to transform raw e-commerce data into actionable insights that can support:

- Sales performance analysis
- Customer segmentation
- Product performance analysis
- Customer retention
- Discount optimization
- Subscription analysis
- Cross-selling opportunities
- Data-driven decision making

---

# Project Workflow


Raw Dataset
     ↓
Data Understanding & Cleaning
     ↓
Python Exploratory Data Analysis
     ↓
SQL Business Analysis
     ↓
Power BI Data Modeling & DAX
     ↓
Interactive Dashboard
     ↓
Key Insights
     ↓
Business Recommendations
----

## Project workflow Structure in Detail

The project follows a structured end-to-end Data Analytics workflow, starting from raw customer data and ending with actionable business recommendations.

### 1. Raw Dataset
The e-commerce dataset contains customer demographics, products, purchases, discounts, ratings, subscriptions, payment methods, shipping details and seasonal information.

### 2. Data Understanding & Cleaning
The dataset was inspected for data types, missing values, duplicate records and inconsistent values. Relevant columns were reviewed and prepared for further analysis.

### 3. Python Exploratory Data Analysis
Python was used to explore customer behavior, purchase patterns, product performance and numerical/categorical distributions. Pandas, NumPy, Matplotlib and Seaborn were used for analysis and visualization.

### 4. SQL Business Analysis
SQL was used to answer key business questions and calculate metrics such as revenue, customer count, average purchase, category performance, customer segments, discount behavior, subscription performance and payment-method performance.

### 5. Power BI Data Modeling & DAX
The analyzed data was prepared in Power BI. Relationships, calculated measures and DAX formulas were used to create KPIs and support interactive business analysis.

### 6. Interactive Dashboard
A two-page Power BI dashboard was developed:
- **Executive & Sales Overview** — focuses on KPIs, revenue, customers, categories, demographics and subscription performance.
- **Customer & Purchase Insights** — focuses on products, customer segments, discounts, payment methods and purchasing behavior.

### 7. Key Insights
The dashboard was used to identify important business patterns, including high-performing products, customer loyalty behavior and differences between discounted and non-discounted purchases.

### 8. Business Recommendations
The identified insights were converted into actionable recommendations focused on product availability, cross-selling, customer retention and targeted discount strategies.

## My Project Overview

E-Commerce-Customer-Intelligence/
│
├── README.md
│
├── data/
│   └── ecommerce_customer_data.csv
│
├── python/
│   └── ecommerce_customer_eda.ipynb
│
├── sql/
│   └── E-Commerce Customer SQL Analysis.sql
│
├── powerbi/
│   └── E-Commerce Customer Intelligence.pbix
│
├── assets/
│   ├── dashboard-page-1.png
│   └── dashboard-page-2.png
│
└── documentation/
    └── business-insights.md
     
