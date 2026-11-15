# Customer Segmentation using RFM Analysis and K-Means

**Track:** Data Analytics | **Level:** 1 | **Internship:** Oasis Infobyte (AICTE)

## Objective
Group e-commerce customers into segments based on purchasing behaviour, so each group can be targeted with a suitable marketing action.

## Tools
Python, pandas, NumPy, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn, Google Colab

## Dataset
"Online Retail" dataset (Kaggle / UCI): 541,909 transactions from a UK online retailer, Dec 2010 to Dec 2011. The file is 47 MB, so it is not included here; download it from Kaggle by searching "Online Retail dataset".

## What I did
- Cleaned the data: removed rows with no CustomerID, cancelled orders and invalid quantities or prices (541,909 rows reduced to 397,884 rows, 4,338 customers)
- Built an RFM table (Recency, Frequency, Monetary) with one row per customer
- Applied a log transform and StandardScaler
- Used the Elbow Method to choose K = 4
- Ran K-Means clustering
- Visualised the clusters (scatter plots) and the number of customers per cluster
- Profiled each cluster and wrote marketing recommendations

## Key findings
- Champions (716 customers): bought recently, order often and spend the most. Reward them with a loyalty programme.
- Loyal regulars (1,173): moderate frequency and spend. Nudge them with bundles and reminders.
- Recent newcomers (837): recent but only about 2 orders. Offer a second-purchase incentive.
- Lapsed customers (1,612, the largest group): last bought about 6 months ago. Run win-back campaigns.

## Files
- Task2_Customer_Segmentation.ipynb
