# Employee Attrition Prediction using Machine Learning

**Internship Project — Week 2 | Xylofy AI | June 2026**

## Overview
Built a machine learning system to predict employee attrition using the IBM HR Analytics dataset (1,470 records). The project covers end-to-end data science — from EDA to model comparison to business recommendations.

## Dataset
IBM HR Analytics Employee Attrition Dataset — 1,470 rows, 35 features  
Source: [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Models Trained
|        Model        | ROC-AUC |
|---------------------|---------|
| Logistic Regression |  0.798  |
| Random Forest       |  0.771  |
| Gradient Boosting   |  0.794  |

**Best Model: Logistic Regression** (highest AUC + best Recall for HR use case)

## Key Findings
- Sales Representatives have the highest attrition rate at 39.76%
- Overtime is the strongest predictor of employee exit
- Employees who left earned ~27% less than those who stayed
- Attrition peaks in the first 1–2 years of employment

## Project Structure

├── analysis.ipynb               # Complete Jupyter Notebook

├── HR-Employee-Attrition.csv    # Dataset

├── summary.pdf                  # Non-technical HR Director summary
 
└── charts/                      # All visualization charts

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook