# Online Retail II - Exploratory Data Analysis

<img width="952" height="845" alt="image" src="https://github.com/user-attachments/assets/0de711e2-f429-46bd-86b4-06622dcf59d7" />

Week 1 internship task: EDA on real transaction data from a UK based online retailer (2009-2011) to understand customers, top products, and country revenue before building a recommendation system.

## Dataset
- Online Retail II Dataset, UCI Machine Learning Repository
- https://archive.ics.uci.edu/ml/datasets/Online+Retail+II
- Download `online_retail_II.xlsx` and place it in the project root

## Setup
```bash
pip install pandas matplotlib seaborn openpyxl jupyter
jupyter notebook Online_Retail_EDA.ipynb
```

## What the Notebook Covers
1. Dataset load (both sheets combined), shape, columns, dtypes
2. Missing values and duplicate rows report (observation only, nothing removed)
3. Top 10 products by quantity and by revenue
4. Sales performance by country (with and without UK)
5. Monthly revenue trend
6. Correlation heatmap of numeric features
7. Outlier detection via box plots (Quantity, Price)
8. Six business insights

## Key Findings
- UK generates the large majority of revenue
- Clear seasonal peak in Sep-Nov
- Negative quantities are cancellations (invoices starting with C)
- Many rows lack Customer ID, a blocker for personalization
- Quantity leaders and revenue leaders are different product sets

## Tools
Python, pandas, matplotlib, seaborn, Jupyter
