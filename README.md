# Strategic Analysis of Employee Attrition: An HR Analytics Perspective

##  Project Overview

Employee turnover (attrition) is a critical challenge that impacts organizational stability, productivity, and recruitment costs. This project conducts a comprehensive **Exploratory Data Analysis (EDA)** on a corporate HR dataset (sourced from Kaggle) containing 1,470 employee records.

As the **Data and Business Analyst**, my objective was to identify the primary drivers of attrition, evaluate the impact of workplace factors on employee retention, and provide data-driven recommendations to minimize turnover and optimize human capital management.

---

##  Business Problem

High attrition rates lead to significant financial loss and a decline in institutional knowledge. The core business questions addressed in this analysis are:

1. **Attrition Profile:** What are the defining characteristics of employees who leave vs. those who stay?
2. **Work-Life Balance & Satisfaction:** How do environmental factors and job satisfaction correlate with the decision to resign?
3. **Compensation & Growth:** To what extent do income levels, salary hikes, and promotion cycles influence retention?
4. **Role Dynamics:** Are specific departments or job roles more susceptible to turnover than others?

---

##  Dataset Description

The dataset comprises **1,470 rows** and **35 features**, covering various facets of the employee lifecycle.

### Key Feature Categories:

* **Demographics:** Age, Gender, Education, Marital Status.
* **Employment Context:** Department, Job Role, Job Level, Business Travel frequency, Distance From Home.
* **Performance & Satisfaction:** Job Satisfaction, Environment Satisfaction, Relationship Satisfaction, Work-Life Balance, Performance Rating.
* **Compensation:** Monthly Income, Stock Option Level, Percent Salary Hike.
* **Tenure:** Total Working Years, Years at Company, Years in Current Role, Years Since Last Promotion.

**Target Variable:** `Attrition` (Yes/No) – indicates whether an employee has left the company.

---

##  Methodology & Technical Stack

### Technologies Used:

* **Language:** Python
* **Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Statistical Analysis:** Correlation Matrix, Bivariate/Multivariate Analysis

### Analytical Approach:

1. **Data Quality Audit:** Handling missing values (if any), verifying data types, and identifying unique values to filter out constants (e.g., `EmployeeCount`, `StandardHours`).
2. **Univariate Analysis:** Analyzing the distribution of the workforce across ages, departments, and roles.
3. **Bivariate Analysis:** Segmenting attrition against key variables like `MonthlyIncome`, `OverTime`, and `JobSatisfaction`.
4. **Correlation Mapping:** Identifying multi-collinearity and strong predictors of turnover.
5. **Insights Synthesis:** Translating statistical findings into business-relevant recommendations.

---

##  Key Findings (Summary)

* **Overtime Impact:** Employees working overtime exhibit significantly higher attrition rates, suggesting burnout risks.
* **The "Income Threshold":** There is a noticeable correlation between low monthly income and high turnover, particularly in junior job levels.
* **Tenure Risk:** Attrition is highest among employees with fewer years at the company, highlighting the need for better onboarding and early engagement.
* **Departmental Variance:** Specific departments like Sales show higher volatility compared to Research & Development.

---

##  How to Navigate this Project

1. **Notebooks:** The primary analysis is documented in `EDA_Employee_Attrition.ipynb`, featuring detailed visualizations and step-by-step commentary.
2. **Data:** The source file used is `HR-Employee-Attrition.csv`.
3. **Results:** Key charts and findings are summarized in the final section of the notebook.

---

##  Author

**Nandini Verma**

* **Role:** Data and Business Analyst

---

*License: This project is licensed under the MIT License - see the LICENSE file for details.*
