<h1 align="center">💼 Salary Prediction Using Machine Learning</h1>
<p align="center">
  <b>Regression Modeling | Career & Compensation Analytics</b>
</p>

<hr>

<p align="center">
  <img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/7b210ce2-d628-40cb-baa2-3e0145e8d45e" />
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
In today’s competitive technology job market, understanding salary trends is
critical for <b>job seekers, recruiters, and employers</b>.
This project builds an <b>end-to-end machine learning pipeline</b> to predict
tech job salaries using job attributes such as
<b>role, skills, company characteristics, and location</b>.
</p>

<p>
Using <b>Glassdoor job postings (2017–2018)</b>, the project transforms raw salary
data, performs meaningful feature engineering, evaluates multiple regression
models, and selects a <b>robust final model</b> that generalizes well to unseen data.
</p>

<hr>

<h2>🎯 Business Objectives</h2>
<ul>
  <li>Estimate <b>realistic salary expectations</b> for job seekers</li>
  <li>Help employers and recruiters <b>benchmark compensation</b></li>
  <li>Understand how <b>job role, skills, company size, age, and location</b> impact salary</li>
  <li>Build a <b>reliable and interpretable regression model</b> for salary prediction</li>
</ul>

<hr>

<h2>📊 Dataset Description</h2>
<p>
The dataset is sourced from <b>Glassdoor job postings</b> and contains
approximately <b>950 tech job listings</b> collected between 2017 and 2018.
Each record represents a single job posting with salary and company information.
</p>

<ul>
  <li><b>Job Title</b></li>
  <li><b>Salary Estimate</b></li>
  <li><b>Job Description</b></li>
  <li><b>Company Rating</b></li>
  <li><b>Company Size & Age</b></li>
  <li><b>Location & Headquarters</b></li>
  <li><b>Industry, Sector, Ownership Type</b></li>
  <li><b>Competitors</b></li>
</ul>

<hr>

<h2>🛠️ Data Preparation & Feature Engineering</h2>
<ul>
  <li>Cleaned and parsed salary ranges into <b>minimum, maximum, and average</b> salary</li>
  <li>Applied <b>log transformation</b> to reduce salary skewness</li>
  <li>Extracted key skills (<b>Python, SQL, Excel, Machine Learning</b>) from job descriptions</li>
  <li>Created company-level features such as <b>company size</b> and <b>company age</b></li>
  <li>Engineered location features (job state, same-state HQ indicator)</li>
  <li>Reduced categorical cardinality and applied <b>one-hot encoding</b></li>
  <li>Removed high-cardinality identifiers (e.g., company name) to prevent overfitting</li>
</ul>

<hr>

<h2>🤖 Modeling Approach</h2>
<p>
Multiple regression models were trained and evaluated to compare performance:
</p>

<ul>
  <li><b>Linear Regression</b> – Baseline model</li>
  <li><b>Decision Tree Regressor</b> – Captured non-linear relationships</li>
  <li><b>Random Forest Regressor</b> – <b>Final selected model</b> ✅</li>
</ul>

<p>
The <b>Random Forest Regressor</b> was chosen due to its stability,
strong generalization ability, and superior performance compared to simpler models.
</p>

<hr>

<h2>📈 Model Performance (Test Set)</h2>
<ul>
  <li><b>R² Score:</b> ~0.80</li>
  <li><b>Mean Absolute Error:</b> ~14–15% (log-scale salary)</li>
  <li>Demonstrates <b>minimal overfitting</b> and strong predictive accuracy</li>
</ul>

<p>
An <b>Actual vs Predicted Salary</b> analysis confirms that predictions closely
track real salary values, with expected variance at higher salary ranges.
</p>

<hr>

<h2>🔍 Key Insights</h2>
<ul>
  <li><b>Job role and location</b> are the strongest drivers of salary</li>
  <li><b>Company size and company age</b> have a significant impact on compensation</li>
  <li>Demand for <b>Python and Machine Learning</b> skills is associated with higher salaries</li>
  <li><b>Ensemble models</b> outperform linear approaches for salary prediction</li>
</ul>

<hr>

<h2>💡 Business Impact</h2>
<ul>
  <li>Empowers job seekers with <b>data-driven salary expectations</b></li>
  <li>Helps recruiters design <b>competitive and market-aligned compensation</b></li>
  <li>Supports employers in <b>pay structure and workforce planning</b></li>
  <li>Demonstrates practical application of <b>machine learning to real-world labor market data</b></li>
</ul>

<hr>

<p align="center">
  <i>📌 This project showcases how machine learning can provide meaningful insights
  into compensation trends and support informed career and hiring decisions.</i>
</p>





