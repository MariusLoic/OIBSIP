# DataAnalytics-L1-DataCleaning

**Track:** Data Analytics (Oasis Infobyte SIP)
**Task:** Level 1, Task 3 — Cleaning Data
**Author:** Ngninmeu Fondjo Marius Loic

## Overview
Demonstrates a professional, end-to-end data cleaning workflow on a
deliberately messified version of the Titanic passenger dataset — taking it
from raw/dirty to analysis-ready, with every decision documented and
justified.

## Dataset
- Base: the classic Titanic passenger dataset (891 rows)
- Deliberately "messified" for this exercise on top of its genuine missing
  values (Age, Cabin, Embarked): 15 duplicate rows added, inconsistent
  casing introduced in `Sex` and `Embarked`, a handful of invalid negative
  `Age` values inserted, and some `Fare` values converted to `$`-prefixed
  strings to force a mixed dtype column
- `titanic_messy.csv` — the dirty input
- `titanic_cleaned.csv` — the cleaned output

## What's in this notebook
1. Data quality report (nulls, duplicates, dtype issues, unique values)
2. Missing data handling — grouped median imputation for Age, binary flag
   for Cabin, mode imputation for Embarked (each justified)
3. Duplicate row detection & removal
4. Standardisation of inconsistent categorical casing (Sex, Embarked) and
   mixed-format Fare strings
5. Outlier detection — IQR method for Fare, sign-correction for invalid
   negative Age values, with reasoning for what to keep vs. fix
6. Data type correction (bool, category, numeric)
7. Before vs. after summary table
8. Cleaned dataset saved to CSV

## Files
- `Data_Cleaning_OIBSIP.ipynb` — the executed notebook (all cells run,
  outputs included)
- `titanic_messy.csv` — dirty input dataset
- `titanic_cleaned.csv` — cleaned output dataset

## How to run
```bash
pip install pandas numpy jupyter
jupyter notebook Data_Cleaning_OIBSIP.ipynb
```
