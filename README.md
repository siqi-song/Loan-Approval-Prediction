# Loan Approval Decision - Logistic Regression

This project uses the **Loan Approval Classification Dataset** from Kaggle to analyze factors influencing loan approvals and build a classification model to predict approval outcomes.

📂 **Dataset Source**: [Kaggle - Loan Approval Classification](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data)

---

## 📌 Objective

To perform exploratory data analysis (EDA) on the dataset, clean and prepare the data, and build a machine learning model that classifies whether a loan should be approved based on applicant information.

---

## 📊 Dataset Overview

The dataset includes the following features:

- **Numerical**: `person_age`, `person_income`, `person_emp_exp`, `loan_amnt`, `loan_int_rate`, `loan_percent_income`, `cb_person_cred_hist_length`, `credit_score`
- **Categorical**: `person_gender`, `person_education`, `person_home_ownership`, `loan_intent`, `previous_loan_defaults_on_file`

The target variable is whether the loan was approved.

---

## 🧰 Libraries Used

- `pandas` for data manipulation
- `matplotlib` for visualization
- `sklearn` for preprocessing and model building
- `numpy` for numerical operations
- `kagglehub` for dataset download

---

## 🔍 Analysis Workflow

1. **Dataset Loading**:
   - Dataset is downloaded using `kagglehub` and loaded into a pandas DataFrame.
   
2. **Exploratory Data Analysis (EDA)**:
   - Distribution of numerical and categorical features.
   - Checking for missing values and outliers.
   - Visual analysis to understand feature relationships.

3. **Data Preprocessing**:
   - Standardization of numerical features.
   - Encoding of categorical features.

4. **Model Building**:
   - Classification model training using Logistic Regression.
   - Performance evaluation using accuracy.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval-decision.git
   cd loan-approval-decision

