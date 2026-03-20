# Customer Churn Analysis (EDA)
**Overview**

This project explores customer churn behavior to identify why customers leave a service and what factors contribute most to retention.

The analysis focuses on uncovering patterns in customer behavior, demographics, and service usage that influence churn.

# Objectives
- Understand the key drivers of customer churn
- Identify high-risk customer segments
- Analyze relationships between customer features and churn
- Generate insights that can inform retention strategies

# Dataset Summary

The dataset contains customer-level information, including:
- Demographics (gender,Age)
- Account details (tenure, contract type)
- Billing information (Total spend)
- Churn status

 # Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn


# Analysis Approach

The analysis was conducted in three main stages:
**1. Univariate Analysis**
- Churn rate by subscription type
- Churn rate by Gender
- Churn rate by Age
- Subscription Type distribution
  
**2. Bivariate Analysis**
- Payment delays vs churn(Boxplot)
- Customer tenure vs Total spend(Scatterplot) 

# Key Insights
1. The company is losing more customers than it retains
2. Female customers exhibit a much higher churn rate (67%) compared to male customers (49%).
3. Older customers appear more likely to churn
4. Payment delays are a strong signal of churn risk
5. Low-spend customers represent an extremely high churn-risk group
