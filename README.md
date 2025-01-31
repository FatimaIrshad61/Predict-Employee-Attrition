# Employee Attrition Analysis

## Project Overview

This project aims to analyze employee attrition using Exploratory Data Analysis (EDA) and machine learning models such as Random Forest and Logistic Regression. Additionally, SHAP and LIME are used to interpret model predictions and derive actionable insights to reduce attrition.

## Objectives

1. Perform EDA to identify key factors influencing attrition.
2. Train classification models (Random Forest and Logistic Regression) to predict attrition.
3. Use SHAP or LIME for model interpretability.
4. Provide actionable insights to help reduce attrition.

## Dataset

- The dataset contains employee-related information such as age, salary, department, job satisfaction, work-life balance, and attrition status.
- The target variable: `Attrition` (1 = Yes, 0 = No).

## Steps

### 1. Data Preprocessing & EDA

- Handle missing values.
- Encode categorical variables.
- Perform correlation analysis.
- Visualize key features affecting attrition (e.g., salary distribution, job satisfaction levels, tenure).

### 2. Model Training

- Split data into training and test sets.
- Train classification models:
  - **Logistic Regression**
  - **Random Forest**
- Evaluate models using accuracy, precision, recall, and F1-score.

### 3. Model Interpretation (SHAP/LIME)

- Use SHAP values to understand feature importance.
- Generate force plots to visualize individual predictions.
- Use LIME to explain specific employee attrition predictions.

### 4. Insights & Recommendations

Based on the analysis, key insights to reduce attrition include:

- **Increase Employee Engagement**: Employees with low job satisfaction are more likely to leave.
- **Improve Compensation & Benefits**: Salary disparities contribute to attrition.
- **Enhance Career Growth Opportunities**: Employees with limited promotion opportunities are more likely to leave.
- **Promote Work-Life Balance**: High workload leads to higher attrition rates.
- **Strengthen Leadership & Management**: Poor manager relationships correlate with higher attrition.

## Tools & Libraries

- **Python** (pandas, numpy, seaborn, matplotlib, scikit-learn, shap, lime)
- **Jupyter Notebook / Google Colab**

## How to Run the Project

1. Install dependencies: `pip install pandas numpy seaborn matplotlib scikit-learn shap lime`
2. Load dataset.
3. Run EDA scripts.
4. Train models and evaluate performance.
5. Interpret results using SHAP or LIME.
6. Generate insights and recommendations.

## Conclusion

This project provides a data-driven approach to understanding and reducing employee attrition. The insights derived from EDA and machine learning models can help HR departments make informed decisions to retain employees.

ok

