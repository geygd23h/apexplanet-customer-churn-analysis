# Customer Churn Analysis - IBM Telco Dataset

## Project Overview

This project analyzes customer churn behavior using the IBM Telco Customer Churn dataset. The objective is to identify factors influencing customer attrition and generate actionable business insights.

## Dataset Information

- Total Records: 7043
- Total Features: 50
- Target Variable: Churn Label

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning

The following cleaning steps were performed:

- Missing values in Offer replaced with "No Offer"
- Missing values in Internet Type replaced with "No Internet"
- Missing values in Churn Category replaced with "Not Churned"
- Missing values in Churn Reason replaced with "Not Churned"
- Duplicate records checked and none found
- Customer IDs verified as unique

## Key Insights

1. Customer churn rate is 26.54%.
2. Month-to-Month customers show the highest churn rate (45.84%).
3. Two-Year contract customers have the lowest churn rate (2.55%).
4. Customers who churn pay higher average monthly charges.
5. Customer satisfaction score is the strongest churn indicator.
6. Customers with longer tenure are less likely to churn.

## Visualizations

- Churn Distribution
- Contract Type vs Churn
- Monthly Charge Distribution
- Correlation Heatmap

## Business Recommendations

- Encourage long-term contracts.
- Improve customer satisfaction programs.
- Focus retention efforts on new customers.
- Review pricing strategies for high-charge customers.
- Develop referral-based loyalty programs.
