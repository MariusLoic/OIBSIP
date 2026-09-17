# DataAnalytics-L1-EDARetailSales

**Track:** Data Analytics (Oasis Infobyte SIP)
**Task:** Level 1, Task 1 — EDA on Retail Sales Data
**Author:** Ngninmeu Fondjo Marius Loic

## Overview
Exploratory Data Analysis on the Superstore Sales dataset (~8,400 order-line
records, Canada, 2009–2012) to uncover sales trends, customer segment
behaviour, product performance, and profitability patterns, with actionable
business recommendations.

## Dataset
- Source: Superstore Sales dataset (public Kaggle/GitHub mirrors of the
  classic "Superstore" retail dataset)
- Rows: 8,399 order-line records
- Columns: 21 (order/ship dates, quantities, sales, discount, profit, unit
  price, shipping cost, customer segment, product category/sub-category,
  region, etc.)

## What's in this notebook
1. Data loading & initial inspection (shape, dtypes, nulls)
2. Descriptive statistics
3. Time series analysis — monthly & quarterly sales trends
4. Customer segment analysis (Consumer / Corporate / Home Office / Small
   Business — used in place of individual demographics, which this dataset
   does not contain)
5. Product analysis — top 10 products by revenue, revenue by category
6. Correlation heatmap of numerical variables
7. Additional insight — discount level vs. average profit
8. Shipping mode breakdown
9. Conclusion with 3 specific, actionable business recommendations

## Files
- `EDA_Retail_Sales_OIBSIP.ipynb` — the executed notebook (all cells run,
  outputs included)
- `superstoreSales_utf8.csv` — the dataset (UTF-8 encoded)
- `*.png` — exported chart images referenced in the notebook

## How to run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook EDA_Retail_Sales_OIBSIP.ipynb
```
