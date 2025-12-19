💼 Salary Prediction using Machine Learning
📌 Project Overview

In today’s competitive tech job market, understanding salary trends is crucial for job seekers, employers, and recruiters. This project aims to predict tech job salaries using machine learning based on job attributes such as role, skills, company size, company age, and location.

Using job posting data from Glassdoor (2017–2018), I built an end-to-end regression pipeline that cleans raw salary data, performs feature engineering, compares multiple models, and selects the most stable and accurate model for salary prediction.

🎯 Business Objectives

Help job seekers estimate realistic salary expectations

Assist employers and recruiters in benchmarking compensation

Understand how job role, skills, company size, and location influence salaries

Build a robust predictive model for salary estimation

📊 Dataset Description

The dataset contains ~950 job postings with features including:

Job Title

Salary Estimate

Job Description

Company Rating

Company Size & Age

Location & Headquarters

Industry, Sector, Ownership Type

Competitors

🛠️ Key Data Preparation & Feature Engineering

Cleaned and parsed salary ranges (min, max, average)

Applied log transformation to salary to reduce skewness

Extracted skills (Python, SQL, Excel, Machine Learning) from job descriptions

Created company-level features like company size and company age

Engineered location features including job state and same-state HQ indicator

Reduced categorical cardinality and applied one-hot encoding

Removed high-cardinality identifiers (e.g., company name) to prevent overfitting

🤖 Modeling Approach

The following regression models were trained and compared:

Model	Purpose
Linear Regression	Baseline model
Decision Tree Regressor	Capture non-linear relationships
Random Forest Regressor	Final selected model
✅ Final Model

Random Forest Regressor (default configuration)

Chosen for its stability, generalization, and strong performance

📈 Model Performance (Test Set)

R² Score: ~0.80

Mean Absolute Error: ~14–15% (log-scale salary)

Demonstrated strong generalization with minimal overfitting

An Actual vs Predicted Salary plot confirms predictions closely follow real salary values, with expected variability at higher salary ranges.

🔍 Key Insights

Job role and location are the strongest drivers of salary

Company size and age significantly influence compensation

Demand for Python and Machine Learning skills is associated with higher salaries

Ensemble models outperform linear approaches for this problem
