# Project 1 — Customer Churn Prediction 📊

## View Notebook
👉 [Open Notebook in NBViewer](https://nbviewer.org/github/dhanshreesarangAI/Data-Science-Internship-Projects/blob/main/Project-1-Customer-Churn-Prediction/Customer_Churn_Prediction.ipynb)  

## Problem Statement
Can we predict which customers are likely to stop 
using a telecom service based on their behavior?

## Dataset
- Name: IBM Telco Customer Churn
- Source: Kaggle
- Rows: 7043 customers
- Columns: 50

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Steps Performed
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Encoding
5. Train Test Split
6. Model Building
7. Model Evaluation

## Models & Results
| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 81.1% | 0.870 |
| Decision Tree | 80.6% | 0.854 |

## Key Findings
- Month-to-month customers churn 43%
- New customers churn more in first 12 months
- High monthly charges increase churn risk
- No tech support = more churn

## Conclusion
Logistic Regression performed best with 81.1% 
accuracy and 0.870 ROC-AUC score
