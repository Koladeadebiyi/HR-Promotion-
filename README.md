# HR Promotion Prediction Machine Learning Project

## Project Overview

This project demonstrates a machine learning model designed to predict employee promotion eligibility based on historical HR data. The goal is to support HR managers and executives in making data-driven promotion decisions, optimizing talent development, and reducing biases in promotion processes.

Stakeholders: HR managers, HR analysts, department heads, and organizational leadership.

---

## Problem Statement

Employee promotion decisions often rely on subjective assessments, leading to inconsistencies and potential bias. The organization seeks to answer:

* Which employee attributes most strongly indicate promotion readiness?
* Can a predictive model identify employees likely to be promoted within the next review cycle?
* How can HR use insights from historical data to improve fairness and efficiency in promotions?

---

## Data Structure

The dataset includes the following tables and features:

* **Employee:** Employee ID, department, tenure, age, gender, education
* **Performance:** Annual performance scores, KPIs
* **Training:** Training hours, certifications completed
* **Promotion History:** Previous promotions, promotion dates
* **Additional Features:** Attendance, project involvement, awards

<img width="441" height="236" alt="Screenshot 2026-01-19 231855" src="https://github.com/user-attachments/assets/18f6f9c8-2059-493a-b32e-9626d0c75747" />


---

## Data Analysis & Modeling Process

1. **Data Cleaning:** Handle missing values, standardize categorical variables, normalize numeric features.
2. **Feature Engineering:** Create promotion-relevant features such as performance growth rate, training intensity, and tenure brackets.
3. **Exploratory Data Analysis (EDA):** Visualize trends in promotion rates by department, performance, and demographics.
4. **Modeling:**

   * Algorithms used: Logistic Regression, Random Forest, Gradient Boosting
   * Train-test split: 80/20
   * Cross-validation to optimize hyperparameters
5. **Evaluation:** Accuracy, Precision, Recall, F1-score, and ROC-AUC metrics
6. **Interpretation:** Feature importance analysis to identify key drivers of promotion
7. 
<img width="733" height="557" alt="Screenshot 2025-12-13 121940" src="https://github.com/user-attachments/assets/ce267583-d351-428b-87a9-b731defce083" />

---

## Key Findings / Insights

* **Promotion Likelihood Drivers:**

  * High performance scores, longer tenure, and completion of targeted training programs strongly correlate with promotion.
  * Department and project involvement also influence promotion probability.
* **Bias Checks:**

  * Gender and age had minor impact on model predictions, but disparities in promotion rates exist historically.
* **Model Performance:**

  * Random Forest achieved the best results: 82% accuracy, 0.78 F1-score, and ROC-AUC of 0.85.

---

## Recommendations

1. **Leverage Model Insights for Fair Promotions**
   Use predicted promotion probabilities to support HR decisions, particularly for high-performing but under-recognized employees.

2. **Targeted Training Programs**
   Focus training and mentorship efforts on employees with high promotion potential to maximize ROI and retention.

3. **Regular Bias Audits**
   Periodically evaluate promotion outcomes against model predictions to ensure fairness across departments, genders, and tenure groups.

4. **Integrate Predictive Model into HR Workflow**
   Deploy the model in a dashboard for HR to visualize employee readiness, monitor promotion pipelines, and plan development programs.

---

## Tools and Skills Applied

* **Data Cleaning & Preprocessing:** Python (pandas, numpy), Excel
* **Exploratory Data Analysis:** matplotlib, seaborn
* **Machine Learning Modeling:** scikit-learn, XGBoost
* **Evaluation & Metrics:** Accuracy, F1-score, ROC-AUC
* **Business Insight Interpretation:** Feature importance analysis, HR domain knowledge
* **Visualization:** matplotlib, seaborn, dashboard screenshots

---



