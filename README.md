# Data Cleaning Task 1

This project is part of the Data Analyst Internship - Task 1: Data Cleaning and Preprocessing.

## Dataset
Mall Customers Dataset (50 rows sample used for practice).

## Cleaning Steps
1. Removed duplicate Customer IDs (kept first occurrence).
2. Standardized Gender values → Male, Female, Unknown.
3. Standardized Country values → India, USA, Unknown.
4. Standardized Membership values → Gold, Silver, Platinum, Unknown.
5. Converted JoinDate to consistent format (DD-MM-YYYY).
6. Filled missing Age with median = 36.
7. Filled missing Annual Income with median = 59.5.
8. Filled missing Spending Score with median = [your value].
9. Renamed column headers → customer_id, gender, age, annual_income_k, spending_score, country, join_date, membership.

## Final Output
- File: `mall_customers_cleaned.xlsx`
- The dataset is now free from duplicates, blanks, and inconsistent formats.
-
