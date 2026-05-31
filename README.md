# Customer Churn Prediction 📊

## Project Overview
Predicting which customers are likely to leave a telecom company
using Machine Learning models.

## Dataset
- IBM Telco Customer Churn Dataset
- 7043 customers, 50 columns
- Source: Kaggle

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Steps Performed
1. Data Loading & Exploration
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection & Encoding
5. Model Building
6. Model Evaluation

## Models Used
| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 81.1% | 0.870 |
| Decision Tree | 80.6% | 0.854 |

## Key Findings
- Month-to-month contract customers churn 43%
- New customers (less than 12 months) churn more
- Higher monthly charges = higher churn risk
- Customers without tech support churn more

## Conclusion
Logistic Regression performed best with 81.1% accuracy.
Tenure, Monthly Charge and Contract Type are the most
important factors in predicting churn.
