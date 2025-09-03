# **Predicting Medical Insurance Costs with Linear Regression**

**Background**

HealthSure Insurance Ltd provides medical insurance coverage to clients across different regions.
Management wants to better understand the factors influencing insurance charges and be able to predict medical costs for new applicants.

This project uses Linear Regression to analyze historical insurance data and generate insights into what drives medical expenses.

**Dataset**

The dataset includes the following variables:

**age:** Age of the individual

**sex:** Male / Female

**bmi:** Body Mass Index (indicator of healthy/unhealthy weight)

**children:** Number of dependents covered

**smoker:** Smoking status (yes/no)

**region:** Residential region (northeast, northwest, southeast, southwest)

**charges:** Medical insurance charges (target variable)

**Source:** Kaggle – Medical Insurance Dataset

**Methodology**

**Understanding the business problem** – Why prediction matters for insurers

**Data exploration & cleaning** – Check for missing values, inconsistencies, outliers

**Descriptive analysis** – Average charges, smoker vs non-smoker differences, region comparison

**Feature engineering** – Encoding categorical variables, interaction terms (e.g., smoker × BMI)

**Train/Test split** – 80/20 split for evaluation

**Linear Regression modeling** – Fit model and interpret coefficients

**Model evaluation** – R², MAE, MSE, RMSE

**Business insights & recommendations** – Translating findings into actionable insurance strategies

**Results**

Model Performance (example – update with your actual metrics):

**R² Score: 0.75**

**MAE: $4,200**

**MSE: 45,000,000**

**RMSE: $6,500**

**Key Findings:**

Smoking is the strongest predictor of higher medical costs.

Age and BMI are positively correlated with charges.

Region and gender have smaller effects.

Smokers with high BMI incur the highest charges.

**Business Recommendations**

**Premium adjustments:** Charge higher premiums for smokers and individuals with high BMI.

**Preventive programs:** Offer incentives for smoking cessation and weight management.

**Tech Stack**

Python

Pandas, NumPy – Data wrangling

Scikit-learn – Linear regression & evaluation

Jupyter Notebook / Google Colab

**Project Structure**
insurance-cost-prediction/
│── data/
│   └── insurance.csv
│── notebooks/
│   └── insurance_case_study.ipynb
│── results/
│   └── metrics.txt
│── requirements.txt
│── README.md

**How to Run**

Clone this repository from GitHub.

Open the notebook in Jupyter Notebook or Google Colab.

Install the required libraries from requirements.txt.

Run all cells step by step.

**By:**
Regina Mulei
Nairobi, 
Kenyareginangina@gmail.com,
LinkedIn- https://www.linkedin.com/in/regina-mulei-892942132/
