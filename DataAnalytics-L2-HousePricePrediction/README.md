# DataAnalytics-L2-HousePricePrediction

**Track:** Data Analytics (Oasis Infobyte SIP)
**Task:** Level 2, Task 1 — Predicting House Prices with Linear Regression
**Author:** Ngninmeu Fondjo Marius Loic

## Overview
Builds and evaluates a Linear Regression model to predict house sale prices
from area-level economic and property features, with a Ridge/Lasso
comparison as a bonus.

## Dataset
- `USA_Housing.csv` — 5,000 records with Avg. Area Income, Avg. Area House
  Age, Avg. Area Number of Rooms, Avg. Area Number of Bedrooms, Area
  Population, Price, and Address

## What's in this notebook
1. Data loading & EDA (null check, target distribution)
2. Feature selection discussion (why `Address` is dropped)
3. Missing values & encoding check
4. Correlation heatmap
5. Train/test split (80/20)
6. Linear Regression training
7. Evaluation — MSE, RMSE, R² score
8. Actual vs. predicted price scatter plot
9. Residual plot
10. Coefficient analysis — feature impact on price
11. Bonus: comparison against Ridge and Lasso regularised regression

## Files
- `House_Price_Prediction_OIBSIP.ipynb` — the executed notebook (all cells
  run, outputs included)
- `USA_Housing.csv` — the dataset
- `*.png` — exported chart images referenced in the notebook

## How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook House_Price_Prediction_OIBSIP.ipynb
```
