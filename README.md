# 📚 Lapage — E-commerce Sales & Customer Analysis

Welcome to the **Lapage Data Analysis Project**, a comprehensive exploration of **sales performance and customer behavior** for an online bookstore.

This project was conducted in a **consulting-oriented mindset**, with a strong focus on **clarity, reproducibility, and business decision-making**, and is designed to support **strategic discussions at the executive (CODIR) level**.

---

## 🚀 Live Access

📘 **Interactive Notebook (GitHub Pages)**  
➡️ [Open the live HTML version](https://stephane-oc.github.io/lapage/)  

💻 **Original Jupyter Notebook**  
➡️ [View the notebook file](https://github.com/Stephane-OC/analyse_lapage.ipynb)  

---

## 🚀 Project Access

📘 **Jupyter Notebook**  
➡️ Explore the full analysis, visualizations, and statistical tests directly in the notebook.

📊 **Presentation Deck (CODIR)**  
➡️ A concise executive summary designed for a **15-minute strategic presentation** to non-technical stakeholders.

---

## 📊 Project Overview

Lapage is a bookstore that recently expanded its activity through an **e-commerce platform**.  
After two years of online operations, management now wants to better understand:

- the **evolution of online sales**,  
- the **performance of products and categories**,  
- and the **behavior of online customers**.

This analysis is based on three datasets:

- **Customers**: gender and year of birth  
- **Products**: prices and product categories  
- **Transactions**: purchase dates, products, and customers  

---

## 🎯 Project Objectives

The analysis is structured around **two main axes**.

### 1️⃣ Sales Performance Analysis

- Analyze the **evolution of revenue over time**
- Apply **moving averages** to identify trends
- Measure:
  - number of customers
  - number of transactions
  - number of products sold
- Identify **top-performing and underperforming products**
- Analyze **sales distribution by category**

---

### 2️⃣ Customer Behavior & Statistical Analysis

- Analyze **revenue distribution across customers**
- Visualize inequality using a **Lorenz curve**
- Study correlations between:
  - age and total purchase amount
  - age and purchase frequency
  - age and average basket size
  - gender and purchased categories
  - age and purchased categories
- Apply and justify **statistical tests**, including:
  - Chi-square (χ²) test
  - ANOVA or Student’s t-test
  - Pearson or Spearman correlation
- Identify and handle **atypical B2B customers** to ensure analytical relevance

---

## 🧩 Key Features

- 📈 Time series analysis with moving averages  
- 📊 Clear and interpretable data visualizations  
- 🧠 Statistically justified insights  
- ⚠️ Explicit handling of outliers and atypical customers  
- 🧭 Structured notebook aligned with business objectives  
- 🎯 Results tailored for executive decision-making  

---

## 🧠 Technical Stack

| Category | Tools & Libraries |
|--------|------------------|
| **Language** | Python |
| **Data Analysis** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Statistics** | scipy, statsmodels |
| **Environment** | Jupyter Notebook |

---

## 🗂️ Notebook Structure

### Step 1 — Data Import & Preparation
- Importing required libraries
- Loading CSV files (customers, products, transactions)
- Data quality checks, typing, and cleaning

### Step 2 — Exploratory Data Analysis (EDA)
- Customers dataset analysis
- Products dataset analysis
- Transactions dataset analysis

### Step 3 — Analytical Dataset Construction
- Merging transactions with products
- Merging with customer data
- Final dataset validation and consistency checks

### Step 4 — Time Series Sales Analysis
- Revenue evolution over time
- Moving averages
- Customers, transactions, and products sold per period

### Step 5 — Product Performance Analysis
- Top-performing products
- Underperforming products
- Revenue distribution by product category

### Step 6 — Customer Analysis
- Customer profiles and demographic analysis
- Revenue concentration and Lorenz curve

### Step 7 — Correlations & Statistical Testing
- Exploratory correlation analysis
- Statistical tests:
  - Chi-square (χ²)
  - ANOVA or Student’s t-test
  - Pearson or Spearman correlation
- Interpretation of statistical results

### Step 8 — Atypical Customers (B2B)
- Identification of atypical (B2B) customers
- Justification for exclusion from statistical analysis
- Creation of a cleaned dataset without B2B customers

### Conclusion & Business Recommendations


---

## 💡 Author

**👨‍💻 Stephane-OC**  
Data Analyst & Web Developer  
Focused on data clarity, business insights, and decision-oriented analytics.

---

## 🧾 License

This project is shared under the **MIT License**.  
You are free to use, modify, and adapt the content with appropriate credit.

---

> _“Data analysis is not about numbers — it’s about decisions.”_  
> **Stephane-OC**
