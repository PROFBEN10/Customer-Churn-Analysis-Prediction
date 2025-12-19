# Customer-Churn-Analysis-Prediction
Customer churn prediction using machine learning to identify at-risk customers and support data-driven retention strategies. Compared multiple models and selected Random Forest for optimal business performance.

## Business-Focused Machine Learning Project

#### Project Overview

Customer churn is a critical business problem that directly impacts revenue, customer lifetime value, and growth sustainability.
This project focuses on identifying customers at risk of churning and building a predictive model to help businesses take proactive retention actions.

Using historical customer data, I performed exploratory analysis and built multiple machine learning models to predict churn and recommend data-driven retention strategies.

#### Business Problem

Businesses lose a significant portion of revenue due to customer churn, often without clear early warning signals.

#### Objective:

Identify key drivers of customer churn

Predict which customers are likely to churn

Enable targeted retention strategies to reduce churn and improve profitability

### Dataset Description

The dataset contains customer-level information including:

Demographic attributes

Service usage patterns

Contract and billing information

Churn status (target variable)

The target variable is Churn, indicating whether a customer discontinued service.

### Exploratory Data Analysis (EDA)

Key business insights from EDA include:

Certain customer segments show higher churn likelihood

Service usage and contract type play a significant role in churn behavior

Some features exhibit stronger predictive signals for churn than others

EDA helped guide feature relevance and model selection, ensuring the analysis stayed aligned with business goals.

### Methodology & Approach

Data Preparation

### Data inspection and cleaning

Feature-target separation

Train-test split to ensure unbiased evaluation

## Model Development
Multiple classification models were trained and compared to identify the best-performing approach:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

### Model Evaluation
Models were evaluated using:

Accuracy

Confusion Matrix

Precision, Recall, and F1-Score

### Model Selection & Results

After comparing all models:

Random Forest Classifier emerged as the best-performing model

Achieved the highest accuracy (~86%)

Demonstrated balanced performance across churn and non-churn classes

Captured non-linear relationships common in real customer behavior

This makes Random Forest the most suitable model for business decision-making and churn prediction.

### Key Business Insights

Not all customers contribute equally to churn risk

Predictive modeling enables early identification of at-risk customers

Businesses can prioritize high-risk, high-value customers for retention efforts

Data-driven churn prediction reduces guesswork in customer retention strategies

## Business Recommendations

Based on the analysis and model results:

Implement targeted retention campaigns for customers flagged as high churn risk

Improve service offerings and customer experience for churn-prone segments

Use churn predictions to support marketing, pricing, and customer success strategies

Continuously retrain the model with new data to maintain accuracy

### Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

### Business Impact

This project demonstrates how machine learning can be applied to:

Reduce customer churn

Improve revenue retention

Support strategic, data-driven business decisions

It highlights my ability to translate data into actionable business insights, not just build models.

### Future Improvements

Incorporate additional customer behavior features

Perform hyperparameter tuning for model optimization

Deploy the model as an API or dashboard for real-time churn monitoring
