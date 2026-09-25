# DataAnalytics-L1-CustomerSegmentation

**Track:** Data Analytics (Oasis Infobyte SIP)
**Task:** Level 1, Task 2 — Customer Segmentation Analysis
**Author:** Ngninmeu Fondjo Marius Loic

## Overview
Applies K-Means clustering on RFM (Recency, Frequency, Monetary) features to
segment the Superstore dataset's 795 unique customers into distinct behavioural
groups, enabling targeted marketing strategies.

## Dataset
- Source: Superstore Sales dataset (same dataset used in Task 1)
- 795 unique customers, ~8,400 order-line records, 2009–2013

## What's in this notebook
1. Data loading & inspection
2. Descriptive statistics (average order value, purchase frequency, customer
   lifetime value)
3. RFM feature engineering (Recency, Frequency, Monetary)
4. Standardisation (StandardScaler) before clustering
5. K-Means with the Elbow Method to determine optimal K (K=4)
6. Cluster visualisation (scatter plots)
7. Cluster profiling with descriptive segment labels (Champions, At-Risk High
   Spenders, Loyal Regulars, Dormant/Low-Value)
8. Customer count per segment
9. Targeted marketing recommendations per segment

## Files
- `Customer_Segmentation_OIBSIP.ipynb` — the executed notebook (all cells run,
  outputs included)
- `superstoreSales_utf8.csv` — the dataset
- `*.png` — exported chart images referenced in the notebook

## How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Customer_Segmentation_OIBSIP.ipynb
```
