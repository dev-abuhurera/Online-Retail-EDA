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

<img width="915" height="574" alt="image" src="https://github.com/user-attachments/assets/a172337c-e226-453d-b4a2-57a68f41b329" />

## What the Notebook Covers
1. Dataset load (both sheets combined), shape, columns, dtypes
2. Missing values and duplicate rows report (observation only, nothing removed)
3. Top 10 products by quantity and by revenue
4. Sales performance by country (with and without UK)
5. Monthly revenue trend
6. Correlation heatmap of numeric features
7. Outlier detection via box plots (Quantity, Price)
8. Six business insights

<img width="927" height="621" alt="image" src="https://github.com/user-attachments/assets/0ecb22a6-5a63-402e-9276-870d6f5a46df" />


<img width="935" height="562" alt="image" src="https://github.com/user-attachments/assets/992cf504-8477-4a93-a351-a423950bc512" />


<img width="924" height="676" alt="image" src="https://github.com/user-attachments/assets/9892aa84-915c-4581-a1a5-579ba4ae37db" />


<img width="924" height="676" alt="image" src="https://github.com/user-attachments/assets/372bc22b-93f2-42ae-b83c-9922ab119efa" />


## Key Findings
- UK generates the large majority of revenue
- Clear seasonal peak in Sep-Nov
- Negative quantities are cancellations (invoices starting with C)
- Many rows lack Customer ID, a blocker for personalization
- Quantity leaders and revenue leaders are different product sets

## Tools
Python, pandas, matplotlib, seaborn, Jupyter
