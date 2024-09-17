# Customer Churn Analysis (TL;DR)

## Overview
This project analyzes customer churn data from a telecom company to understand **why customers leave** and **how to reduce churn**. The analysis focuses on key customer demographics, service usage, and billing methods to uncover patterns associated with customer churn. Actionable insights are provided based on exploratory data analysis (EDA), and future enhancements include the use of predictive modeling.

You can view the **full analysis** in the Jupyter Notebook:  
[Customer_Churn_Analysis.ipynb](./Customer_Churn_Analysis.ipynb)

The **dataset** used for the analysis can be found here:  
[customer_churn_data.csv](./Telco-Customer-Churn.csv)

## Key Findings
- **Tenure**: Longer-tenured customers are less likely to churn (negative correlation of -0.35).
- **Contract Type**: Month-to-month contract holders are more likely to churn than those with longer contracts (1-2 years).
- **Payment Method**: Customers paying via **electronic checks** have a higher churn rate.
- **Monthly Charges**: Higher monthly charges increase the likelihood of churn.

## Recommendations
- **Incentivize long-term contracts**: Offer discounts or rewards to convert month-to-month customers to 1- or 2-year contracts.
- **Target high-churn segments**: Provide personalized offers or discounts for customers with high monthly charges or those using electronic checks.
- **Improve Fiber Optic Service**: Address customer satisfaction issues for fiber optic users, who exhibit higher churn rates.

## Next Steps
- **Add Machine Learning**: Incorporate models like **Logistic Regression** or **Random Forests** to predict which customers are likely to churn.
- **Feature Engineering**: Create more detailed features to improve predictive accuracy.
- **Segmentation**: Implement customer segmentation for targeted retention strategies.
