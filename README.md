# Employee Attrition Prediction

## About This Project

Employee attrition is a common challenge faced by organizations. When experienced employees leave, companies spend significant time and money on recruitment, training, and productivity recovery. The goal of this project was to analyze employee data and identify patterns that may indicate whether an employee is likely to leave the organization.

This project was completed as part of my Data Science Internship (Week 2). The focus was not only on building prediction models but also on understanding employee behavior and translating the findings into practical business recommendations that an HR team can use.

---

## Problem Statement

Organizations often struggle to identify employees who may be at risk of leaving. By analyzing factors such as job role, salary, work-life balance, experience, and work history, this project aims to uncover the key drivers of employee attrition and provide insights that can support employee retention strategies.

---

## Dataset Information

Source: IBM HR Analytics Employee Attrition Dataset

Dataset Size:

* 1,470 employee records
* 35 attributes
* Target Variable: Attrition (Yes / No)

The dataset contains employee-related information including demographics, job details, compensation, performance, work-life balance, and career history.

---

## Project Workflow

### 1. Data Exploration

* Loaded and examined the dataset
* Calculated overall attrition rate
* Identified numerical and categorical features
* Checked dataset structure and quality

### 2. Data Cleaning & Preprocessing

* Checked for missing values
* Removed irrelevant columns
* Converted target labels into numerical format
* Applied One-Hot Encoding to categorical variables
* Standardized numerical features

### 3. Exploratory Data Analysis

The analysis focused on understanding how attrition varies across:

* Departments
* Job Roles
* Monthly Income
* Work-Life Balance
* Years at Company

Several visualizations were created to identify meaningful business patterns.

### 4. Model Development

The following classification models were trained and compared:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

### 5. Model Evaluation

Models were evaluated using multiple performance metrics and compared to identify the most suitable approach for employee attrition prediction.

### 6. Business Insights

The final stage focused on translating analytical findings into actionable HR recommendations.

---

## Key Findings

Some important observations from the analysis include:

* The Sales department showed the highest employee attrition.
* Sales Representatives experienced the highest turnover among all job roles.
* Employees with lower monthly income were more likely to leave.
* Work-life balance appeared to influence employee retention.
* Employees in their early years at the company showed a greater tendency to resign.

These findings suggest that employee attrition is influenced by multiple factors rather than salary alone.

---

## Business Recommendations

Based on the analysis, the following actions may help reduce employee turnover:

* Prioritize retention efforts in departments and job roles with high attrition.
* Strengthen onboarding and support programs for newer employees.
* Conduct regular employee engagement and career development discussions.
* Review overtime practices and workload distribution.
* Use employee feedback to proactively identify retention risks.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

Employee-Attrition-Prediction

├── Employee_Attrition_Prediction.ipynb

├── WA_Fn-UseC_-HR-Employee-Attrition.csv

├── summary.pdf

├── README.md

└── charts/

```
├── chart1_department.png

├── chart1_jobrole.png

├── chart2_income_boxplot.png

├── chart3_confusion_matrix.png

├── chart4_feature_importance.png

└── chart5_roc_curve.png
```

---

## Learning Outcome

This project helped me understand the complete workflow of a machine learning project, from data preprocessing and visualization to model building and business interpretation. More importantly, it demonstrated how data can be used to support real-world HR decision-making and employee retention strategies.

---

## Author

Mandeep Kumar Roshan

B.Tech Computer Science Engineering

Lovely Professional University

Aspiring Data Scientist
