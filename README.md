# Customer Churn Prediction with Machine Learning & Business Insights

This project focuses on building a machine learning model to predict customer churn in a subscription-based business context, with a strong emphasis on interpretability and business value.

Using customer-level data that includes demographics, subscribed services, billing, and contract information, the project follows a complete data science workflow:
exploratory **data analysis, feature engineering, model training, evaluation, and explainability**.

**The objective is not only to achieve strong predictive performance, but also to identify the key drivers of churn and translate model outputs into actionable business recommendations that can help companies reduce customer attrition.**

The project is designed as a real-world use case, closely aligned with industry expectations, and demonstrates practical skills in applied machine learning, data analysis, model interpretability, and data-driven decision making.

## 1. Problem Statement
Customer churn is a major challenge for subscription-based businesses. Acquiring new customers is significantly more expensive than retaining existing ones, making churn prediction a critical business problem.

The goal of this project is to build a **machine learning model that predicts customer churn** and, more importantly, to **extract actionable business insights** that can help reduce churn.

## 2. Dataset Overview
The dataset contains customer-level information including:
- Demographics
- Subscription details
- Service usage
- Billing and payment information
- Churn label (Yes / No)

Each row represents one customer, and the target variable indicates whether the customer has churned.

## 3. Project Approach
This project follows a complete, production-oriented machine learning workflow:

1. Exploratory Data Analysis (EDA)
2. Data cleaning and feature engineering
3. Model training and evaluation
4. Model explainability and interpretation
5. Business insights and recommendations

The emphasis is not only on predictive performance, but also on **interpretability and business value**.

## 4. Models Used
The following models were trained and compared:
- Logistic Regression (baseline)
- Random Forest
- Gradient Boosting (XGBoost / LightGBM)

Model evaluation focused on:
- ROC-AUC
- Recall for churned customers
- Precision
- Confusion Matrix

Recall was prioritized due to the higher business cost of missing a churned customer.

## 5. Results
The final model achieved strong predictive performance with a balanced trade-off between recall and precision.

Key performance metrics:
- ROC-AUC: ~0.80+
- Improved recall for high-risk churn customers
- Interpretable feature importance using SHAP values

## 6. Key Business Insights
Key drivers of customer churn include:
- Short customer tenure
- Month-to-month contracts
- High monthly charges
- Lack of additional services such as tech support

These insights were translated into concrete, actionable recommendations for churn reduction.

## 7. Business Recommendations
Based on the analysis, the following strategies are recommended:
- Incentivize long-term contracts for high-risk customers
- Offer targeted discounts during the first 6 months
- Bundle additional services to increase customer stickiness
- Proactively engage customers identified as high churn risk

---

## 8. Repository Structure
