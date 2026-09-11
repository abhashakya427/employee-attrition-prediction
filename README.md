# employee-attrition-prediction
Machine learning project for predicting employee attrition risk using SMOTE, Logistic Regression, Random Forest, and Gradient Boosting, with actionable HR intervention strategies.
# Predicting Employee Attrition Risk Using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations, resulting in recruitment costs, productivity loss, disruption of teams, and loss of organizational knowledge.

This project uses **Machine Learning and HR Analytics** to predict employees who may be at risk of attrition before they formally leave the organization. The objective is to move HR decision-making from a **reactive approach to a proactive, data-driven approach**.

The project uses a publicly available HR dataset containing approximately **100,000 employee records** and analyzes factors such as employee satisfaction, salary, tenure, overtime, performance, department, and other job-related characteristics. :contentReference[oaicite:0]{index=0}

## 🎯 Objectives

- Identify the major factors influencing employee attrition.
- Develop a machine learning model to predict attrition risk.
- Address class imbalance using **SMOTE**.
- Compare multiple classification algorithms.
- Evaluate models using Accuracy, Precision, Recall, and F1-Score.
- Identify the most important predictors of employee attrition.
- Translate model predictions into actionable HR retention strategies.

## 🛠️ Methodology

The project follows a structured machine learning pipeline:

**Data Collection → Data Preprocessing → EDA → Train-Test Split → SMOTE → Model Training → Model Evaluation → Feature Importance → HR Intervention**

### Data Preprocessing

The dataset was processed through:

- Missing value treatment
- Categorical variable encoding
- Numerical feature standardization
- Train-test splitting
- SMOTE for class imbalance

The dataset has an approximately **90:10 distribution between non-attrition and attrition cases**, making class imbalance an important modeling challenge. SMOTE was applied only to the training data to avoid contaminating the test set. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

## 🤖 Machine Learning Models

Three classification algorithms were developed and compared:

### 1. Logistic Regression
Used as an interpretable baseline model.

### 2. Random Forest
Used to capture non-linear relationships and interactions between employee characteristics.

### 3. Gradient Boosting
Used as the advanced ensemble model and selected as the **best-performing model** in the study. :contentReference[oaicite:3]{index=3}

## 📊 Key Findings

The feature importance analysis identified five major predictors of employee attrition:

1. **Job Satisfaction Score**
2. **Monthly Salary**
3. **Tenure**
4. **Overtime / Workload Pressure**
5. **Performance Rating** :contentReference[oaicite:4]{index=4}

The findings indicate that employee attrition is a **multifactorial problem**, meaning organizations should not rely on a single indicator when assessing retention risk. :contentReference[oaicite:5]{index=5}

## 💼 Business Application

The project converts machine learning predictions into a **risk-tiered HR intervention framework**:

| Risk Level | HR Approach |
|---|---|
| 🔴 High Risk | Immediate intervention |
| 🟡 Medium Risk | Monitor & engage |
| 🟢 Low Risk | Maintain retention focus |

High-risk employees can be prioritized for interventions such as leadership conversations, compensation reviews, role redesign, career-path discussions, and personalized retention strategies. :contentReference[oaicite:6]{index=6}

## 🚀 Business Value

This project demonstrates how machine learning can help HR teams:

- Identify employees with elevated attrition risk.
- Prioritize retention efforts.
- Understand key drivers of employee turnover.
- Develop targeted rather than organization-wide interventions.
- Support proactive workforce planning.
- Use data to complement managerial decision-making.

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## ⚠️ Disclaimer

The project uses a publicly available proxy HR dataset rather than confidential organizational employee data. Therefore, the results demonstrate the **application of predictive analytics to HR decision-making** and should not be interpreted as universally applicable to every organization.
