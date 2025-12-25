# 💼 Salary Prediction Using Machine Learning

<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/bab5dc0c-e9c7-4ae5-8668-c3bf36f0eae1" />

## 📌 Project Overview:-

In today’s competitive tech job market, understanding salary trends is critical for job seekers, recruiters, and employers. This project builds an end-to-end machine learning pipeline to predict tech job salaries using job attributes such as role, skills, company characteristics, and location.

Using Glassdoor job postings (2017–2018), the project transforms raw salary data, performs meaningful feature engineering, evaluates multiple regression models, and selects a robust final model that generalizes well to unseen data.

## 🎯 Business Objectives:-

Estimate realistic salary expectations for job seekers

Help employers and recruiters benchmark compensation

Understand how job role, skills, company size, age, and location impact salary

Build a reliable regression model for salary prediction

## 📊 Dataset Description:-

Source: Glassdoor job postings (2017–2018)

#### Size: 950 job listings

#### Key Features:

Job Title

Salary Estimate

Job Description

Company Rating

Company Size & Age

Location & Headquarters

Industry, Sector, Ownership Type

Competitors

## 🛠️ Data Preparation & Feature Engineering:-

Cleaned and parsed salary ranges into minimum, maximum, and average salary

Applied log transformation to salary to reduce skewness

Extracted key skills (Python, SQL, Excel, Machine Learning) from job descriptions

Created company-level features (company size, company age)

Engineered location features (job state, same-state HQ indicator)

Reduced categorical cardinality and applied one-hot encoding

Removed high-cardinality identifiers (e.g., company name) to avoid overfitting

## 🤖 Modeling Approach:-

#### --> Multiple regression models were trained and evaluated:
---
Model	Purpose
Linear Regression	Baseline model
Decision Tree Regressor	Capture non-linear relationships
Random Forest Regressor	Final selected model 
---
✅ Final Model: Random Forest Regressor

Chosen for its stability, strong generalization, and superior performance compared to simpler models.

## 📈 Model Performance (Test Set):-

#### R² Score: 0.80

#### Mean Absolute Error: ~14–15% (log-scale salary)

#### Demonstrates minimal overfitting and strong predictive accuracy

#### An Actual vs Predicted Salary plot confirms predictions closely track real salary values, with expected variance at higher salary ranges.

## 🔍 Key Insights:-

Job role and location are the strongest drivers of salary

Company size and company age significantly influence compensation

Demand for Python and Machine Learning skills is associated with higher salaries

Ensemble models outperform linear approaches for salary prediction

## 💡 Business Impact:-

Empowers job seekers with data-driven salary expectations

Helps recruiters design competitive compensation strategies

Demonstrates practical application of machine learning to real-world labor market data

