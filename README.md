# 🔍 Credit Card Customer Churn Prediction – Thera Bank

## 📌 Project Overview

Thera Bank has recently experienced a sharp decline in the number of customers using its credit card services. Credit cards are a significant revenue stream for the bank due to various associated fees like annual fees, late payment fees, cash advance fees, and more. 

The objective of this project is to analyze customer data to:
- Identify customers likely to churn (i.e., stop using the bank's credit card services)
- Understand key drivers behind churn
- Build a classification model to predict churn
- Recommend actionable strategies to reduce attrition

---

## 🧠 Problem Statement

Customer attrition negatively impacts the bank's revenue. The bank wants to proactively identify customers who are likely to leave and understand the reasons behind their decisions. This insight will help improve customer retention and service satisfaction.

---

## 📂 Dataset Description

The dataset consists of anonymized credit card customer data, including demographics, account information, and transaction history. Below is a brief overview of the features:

| Feature | Description |
|--------|-------------|
| `CLIENTNUM` | Unique customer identifier |
| `Attrition_Flag` | Churn label: `Attrited Customer` or `Existing Customer` |
| `Customer_Age` | Age of the customer |
| `Gender` | Gender of the customer |
| `Dependent_count` | Number of dependents |
| `Education_Level` | Education level |
| `Marital_Status` | Marital status |
| `Income_Category` | Annual income category |
| `Card_Category` | Credit card type |
| `Months_on_book` | Duration of relationship with the bank |
| `Total_Relationship_Count` | Number of bank products held |
| `Months_Inactive_12_mon` | Months inactive in last 12 months |
| `Contacts_Count_12_mon` | Bank contacts in the last 12 months |
| `Credit_Limit` | Credit card limit |
| `Total_Revolving_Bal` | Balance carried over month to month |
| `Avg_Open_To_Buy` | Average amount left to spend |
| `Total_Trans_Amt` | Total transaction amount in last 12 months |
| `Total_Trans_Ct` | Total transaction count in last 12 months |
| `Total_Ct_Chng_Q4_Q1` | Change in transaction count (Q4 vs Q1) |
| `Total_Amt_Chng_Q4_Q1` | Change in transaction amount (Q4 vs Q1) |
| `Avg_Utilization_Ratio` | Average credit utilization ratio |

---

## 🧰 Tools & Technologies

- Python 🐍
- Pandas, NumPy – data manipulation
- Seaborn, Matplotlib – data visualization
- Scikit-learn – model building and evaluation
- XGBoost – advanced model performance
- Jupyter Notebook / VS Code – development environment

---

## 🔬 Exploratory Data Analysis (EDA)

Key steps performed:
- Missing value analysis and imputation
- Encoding categorical variables
- Distribution and correlation analysis
- Class imbalance check

---

## ⚙️ Model Building

A range of classification models were trained and compared, including:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (Best performer)

**Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC

---

## ✅ Best Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | XX.XX% |
| Precision | XX.XX% |
| Recall | XX.XX% |
| ROC-AUC | XX.XX |

> *(Replace XX.XX% with actual results from your best model)*

---

## 📈 Key Insights

- Customers with low transaction frequency and low contact with the bank are more likely to churn.
- Customers with low total transaction amounts or a high inactivity period are also more at risk.
- Features like `Total_Trans_Ct`, `Total_Trans_Amt`, and `Months_Inactive_12_mon` are strong predictors.

---

## 💡 Recommendations

- **Customer Engagement**: Increase proactive communication with customers showing signs of inactivity.
- **Rewards & Incentives**: Offer targeted rewards to customers with decreasing transaction trends.
- **Monitoring Tools**: Implement real-time churn prediction and alert systems for customer retention teams.
