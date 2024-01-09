# Telecom Customer Churn Analysis

## Summary of Telecom Industry
**Problem Statement:**
"Understanding Telco Customer Churn" is a comprehensive exploration of the challenge of customer churn in the telecommunications industry. This analysis dives into the key factors driving customer attrition, such as pricing, customer service, competition, and technological advancements. It emphasizes the significance of customer retention and provides strategies and solutions for telecom companies to reduce churn rates and enhance customer satisfaction.

## Overview of Dataset
- **Source of Dataset:** [Telecom Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/manjit0801/telecom-customer-churn)

The dataset related to customer information is from a telecommunication service provider with columns such as `customerID`, `gender`, `SeniorCitizen`, `Partner`, `Dependents`, `tenure`, `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`, `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`, and `Churn`.

## Data Cleaning
- Checked for null values and empty strings in the dataset.
- Cleaned 'TotalCharges' column by converting it to numeric type and handling missing values.

## Exploratory Data Analysis (EDA)
- Analyzed the distribution of tenure, monthly charges, and total charges.
- Explored the gender distribution and relationships between tenure, monthly charges, and contract type.
- Derived actionable insights to reduce churn rates based on EDA results.

## Customer Churn Modeling
**Feature Engineering**
- Created a new feature 'TotalMonetaryValue' by multiplying tenure and monthly charges.
- Handled outliers in numerical columns using the Interquartile Range (IQR) method.

**Model Selection**
Three models were trained and evaluated: Logistic Regression, Random Forest Classifier, and Gradient Boosting Classifier.

- Logistic Regression demonstrated the highest accuracy among the three models.

## Conclusion
The Logistic Regression model is selected as the best-performing model for predicting customer churn. The notebook provides actionable insights for telecom companies to improve customer retention based on the analysis. The analysis was performed using Google Colab.
