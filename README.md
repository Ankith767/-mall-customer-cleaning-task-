# -mall-customer-cleaning-task-
# 🛍️ Mall Customer Segmentation – Data Cleaning (Task 1)

## 🔍 Objective
Clean and preprocess the "Mall_Customers.csv" dataset by addressing:
- Missing values
- Duplicate rows
- Inconsistent formatting
- Unclear column naming

## 🛠 Tools Used
- Python
- Pandas
- Google Colab

## 📁 Dataset Source
- [Mall Customer Segmentation Data – Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 🧼 Cleaning Steps
1. Renamed columns to snake_case
2. Removed duplicate rows using `drop_duplicates()`
3. Filled missing values:
   - `gender` as "unknown"
   - `age` with mean
   - `annual_income_(k$)` and `spending_score_(1-100)` with median
4. Standardized text entries (lowercased gender)
5. Exported cleaned dataset to `cleaned_mall_customers.csv`

## ✅ Outcome
Final dataset is cleaned, formatted, and ready for clustering, visualization, or modeling.
