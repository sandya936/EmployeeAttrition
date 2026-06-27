# 📊 Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is a major challenge for organizations as it leads to increased recruitment costs, loss of experienced employees, and reduced productivity. This project develops a machine learning solution to predict whether an employee is likely to leave the company based on HR-related factors such as job role, monthly income, overtime, work-life balance, and years at the company.

The objective is to help HR teams identify employees at higher risk of attrition and support data-driven retention strategies.

---

## 🎯 Business Objective

- Predict employee attrition using historical HR data.
- Identify the key factors influencing employee turnover.
- Provide actionable insights for HR decision-making.
- Support proactive employee retention strategies.

---

## 📂 Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

- **Source:** Kaggle
- **Records:** 1,470 employees
- **Features:** 35 HR attributes
- **Target Variable:** Attrition (Yes / No)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📋 Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded the HR dataset
- Explored dataset structure
- Identified target variable
- Checked data types and class distribution

### 2️⃣ Data Cleaning & Preprocessing
- Checked missing values
- Removed irrelevant columns
- Encoded categorical variables
- Standardized numerical features

### 3️⃣ Exploratory Data Analysis (EDA)
- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition

### 4️⃣ Model Building
Implemented and compared three machine learning models:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

### 5️⃣ Model Evaluation
Models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

### 6️⃣ Feature Importance
Identified the most influential factors contributing to employee attrition.

### 7️⃣ Business Recommendations
Translated model findings into practical HR recommendations for improving employee retention.

---

## 📊 Visualizations

The project includes:

- Department-wise Attrition Analysis
- Job Role Attrition Analysis
- Monthly Income Distribution
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison

---

## 💼 Business Impact

This project enables HR teams to:

- Identify employees at risk of leaving.
- Understand the major factors driving attrition.
- Focus retention efforts on high-risk employee groups.
- Reduce recruitment and training costs.
- Improve workforce planning through data-driven decisions.

---

## ⚠️ Limitations

The model is trained using historical HR data and cannot capture personal circumstances, future organizational changes, or external factors affecting employee decisions. It should be used as a decision-support tool alongside HR expertise.

---

## 📁 Project Structure

```
EmployeeAttrition_[Kaki_Sandya]/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── summary.pdf
├── README.md
│
└── charts/
    ├── department_attrition.png
    ├── jobrole_attrition.png
    ├── monthly_income_boxplot.png
    ├── confusion_matrix.png
    ├── feature_importance.png
    └── roc_curve.png
```

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Explainable AI (SHAP/LIME)
- Deployment using Streamlit or Flask
- Real-time HR dashboard integration

---

## 👩‍💻 Author

**Sandya Kaki**

B.Tech – Computer Science & Engineering (Data Science)

GitHub: https://github.com/sandya936
