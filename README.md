# Task 2: Exploratory Data Analysis – Supermarket Sales Data

## 📌 Overview

This project performs Exploratory Data Analysis (EDA) on a supermarket sales dataset to uncover business insights using Python (Pandas, Matplotlib, Seaborn).  
It is part of my Data Analytics Internship at **Skillytixs**.

## 📂 Dataset

- **Name**: Supermarket Sales Dataset (Kaggle)  
- **Rows**: 1000 | **Columns**: 18  
- **Description**: Transaction-level data including branch, city, product line, unit price, quantity, total, gross income, customer demographics, payment type, and customer rating.  

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- PDF report (exported from notebook)

## 🔎 EDA Workflow

1. Data structure inspection (`.info()`, `.describe()`, `.isnull()`)
2. Missing values heatmap
3. Univariate analysis (histograms, boxplots, countplots)
4. Bivariate/multivariate analysis (correlation heatmap, scatter plots)
5. Grouped analysis (sales and gross income by branch/product line)
6. Outlier detection & skewness (log-transform applied)
7. Key business insights documented

## 📊 Key Insights

- Branch **C** recorded the highest total gross income.  
- **Food and beverages** & **Health and beauty** are top-selling product lines.  
- **E-wallet** emerged as the most preferred payment method.  
- Customer ratings are mostly high (median ~8.5).  
- Peak sales occur in evenings and weekends.  

## 📁 Deliverables

- [`task2_EDA_supermarket_sales.ipynb`](./task2_EDA_supermarket_sales.ipynb) – Full notebook with code & visuals  
- [`task2_EDA_supermarket_sales_report.pdf`](./task2_EDA_supermarket_sales_report.pdf) – Concise PDF report  
- [`supermarket_sales.csv`](./supermarket_sales.csv) – Source dataset  

---
