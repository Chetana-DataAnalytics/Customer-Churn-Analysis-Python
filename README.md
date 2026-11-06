# Customer Churn Analysis Using Python

## Project Overview
This project analyzes customer churn in a telecommunications company using Python. The goal is to identify customer behavior patterns, understand factors associated with churn, and recommend strategies to improve customer retention.

## Dataset
- Dataset: IBM Telco Customer Churn
- Total customers: 7,043
- Original columns: 21
- Final cleaned columns: 23

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning
- Converted `TotalCharges` into a numeric column.
- Investigated 11 missing `TotalCharges` values.
- Replaced missing values with 0 for customers with zero tenure.
- Checked for duplicate records.
- Created customer tenure groups.
- Encoded churn values for correlation analysis.

## Exploratory Data Analysis
- Overall customer churn distribution
- Churn by contract type and payment method
- Customer tenure and monthly charges
- Internet service and additional support services
- Paperless billing and senior citizen status
- Gender and total charges
- Churn rate by tenure group
- Correlation analysis

## Key Findings
- Overall churn rate: 26.54%.
- Customers with 0–12 months of tenure have the highest churn rate at 47.44%.
- Fiber optic customers have a churn rate of 41.89%.
- Customers without online security have a churn rate of 41.77%.
- Customers without tech support have a churn rate of 41.64%.
- Customers who churn have higher average monthly charges (74.44) than customers who stay (61.27).
- Senior citizens have a higher churn rate (41.68%) than non-senior customers (23.61%).

## Business Recommendations
- Improve onboarding and engagement for new customers.
- Review pricing plans and customer value.
- Encourage long-term contracts.
- Promote online security and technical support services.
- Investigate service quality and customer feedback among fiber optic users.
- Develop targeted customer retention strategies.

## Project Structure
- `Customer_Churn_Analysis_Python_Final.ipynb` – Python analysis notebook.
- `data/` – Cleaned dataset.
- `charts/` – Data visualizations.
- `screenshots/` – Project screenshots.

## Conclusion
This project demonstrates data cleaning, exploratory data analysis, data visualization, and business insight generation using Python. The findings help identify customer groups with higher churn rates and suggest potential retention strategies.

## Dataset Source
[IBM Telco Customer Churn Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)
