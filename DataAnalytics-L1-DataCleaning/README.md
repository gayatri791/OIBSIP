# Data Cleaning – Cafe Sales Dataset

**Track:** Data Analytics | **Level:** 1 | **Internship:** Oasis Infobyte (AICTE)

## Objective
Clean a deliberately messy cafe sales dataset and make it analysis-ready.

## Tools
Python, pandas, NumPy, Google Colab

## Dataset
"Cafe Sales – Dirty Data for Cleaning Training" (Kaggle), 10,000 rows, 8 columns.

## What I did
- Built a data quality report (nulls, duplicates, data types)
- Converted ERROR/UNKNOWN entries to missing values
- Fixed data types (numbers and dates)
- Filled missing values using menu prices and Total = Quantity × Price
- Labelled unrecoverable categories "Unknown"; dropped rows missing a date
- Checked outliers (IQR) and standardised text
- Saved the cleaned data as cleaned_cafe_sales.csv

## Result
10,000 rows → 9,514 clean rows; missing values 10,082 → 0; correct data types 4/8 → 8/8.

## Files
- Task3_Data_Cleaning.ipynb
- cleaned_cafe_sales.csv
