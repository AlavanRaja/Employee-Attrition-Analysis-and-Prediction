# 📊 HR Analytics & Employee Prediction System

A Machine Learning powered HR Analytics web application built using **Streamlit** that predicts:

- 🔥 Employee Attrition (Turnover Risk)
- ⭐ Employee Performance Rating

This project demonstrates how HR data can be transformed into actionable business intelligence using Machine Learning.

---

# 🚀 Project Overview

This system uses historical employee data to build predictive models for:

## 1️⃣ Employee Attrition Prediction

**Goal:** Predict whether an employee is likely to leave the company.

**Target Variable:** `Attrition`

### Features Used:
- Age
- Monthly Income
- Years at Company
- Job Satisfaction
- Work Life Balance
- Distance From Home
- Overtime
- Marital Status

### Output:
- Attrition Risk (High / Low)
- Probability of Leaving (%)

This helps HR teams identify employees at high risk and take preventive action.

---

## 2️⃣ Performance Rating Prediction

**Goal:** Predict the employee's performance rating.

**Target Variable:** `PerformanceRating`

### Features Used:
- Education
- Job Involvement
- Job Level
- Monthly Income
- Years at Company
- Years in Current Role
- Total Working Years
- Work Life Balance

### Output:
- Predicted Performance Rating (1–4)

This helps management understand performance drivers and improve evaluation processes.

---

# 🧠 Machine Learning Models Used

| Prediction | Model |
|------------|--------|
| Attrition | Logistic Regression |
| Performance | Logistic Regression |

### Why Logistic Regression?

- Simple and interpretable
- Good baseline model
- Works well for classification problems
- Suitable for structured HR data

---

# 📊 Model Performance

### 🔥 Attrition Model
- Accuracy: ~85%
- ROC-AUC: ~0.81
- Improved using SMOTE (handling class imbalance)

### ⭐ Performance Model
- Multiclass Logistic Regression
- Good classification performance based on evaluation metrics

---

# Streamlit Interface

<img width="1753" height="787" alt="image" src="https://github.com/user-attachments/assets/3d6b2a4b-61fd-4ebb-96fb-d82ebd62f716" />
---

<img width="1805" height="826" alt="image" src="https://github.com/user-attachments/assets/af3e640f-d773-48f6-9744-80ed134ebcd7" />
---

<img width="1761" height="737" alt="image" src="https://github.com/user-attachments/assets/b444d499-1c64-4970-b4d5-91c92327e33a" />
---

<img width="1827" height="782" alt="image" src="https://github.com/user-attachments/assets/5182f6ce-9b2f-4a96-83d8-1608437af6ab" />
---






