# Healthcare Fraud Detection Project

## Overview
This project focuses on detecting fraudulent claims in healthcare datasets. We applied multiple machine learning models to identify potential fraud cases and compared their performance.

## Team Members
- Abdel Rahman 13004775
- Eyad Yehia 13005828
- Mohamed Amgad 13001830
- Omar Soliman 10003810 

## Dataset
The dataset contains information about beneficiaries, inpatient and outpatient claims, and labeled fraud cases. It was split into training and testing sets for model evaluation.

## Models Used
We trained and evaluated four models:  
- **Random Forest**  
- **Gradient Boosting**  
- **XGBoost + SMOTE**  
- **Logistic Regression**

## Performance Summary
- **Random Forest:** Precision 96%, Recall 90% – very reliable overall.  
- **Gradient Boosting:** Precision 95%, Recall 85% – nearly as effective.  
- **XGBoost + SMOTE:** Recall 91%, Precision 63% – good for catching fraud but more false positives.  
- **Logistic Regression:** Recall 100%, Precision 9% – flags almost everything as fraud.

**Conclusion:** Random Forest is the best-performing model.

## Error Analysis
We inspected false positives and false negatives to understand where the models make mistakes. This helps improve model interpretability and trustworthiness.

## SHAP Analysis
We used SHAP (SHapley Additive exPlanations) to visualize feature importance for the Random Forest model. This highlights which features contribute most to fraud predictions.

## How to Run
1. Clone the repository
