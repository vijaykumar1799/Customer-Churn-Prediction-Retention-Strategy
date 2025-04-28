# 📉 Customer Churn Prediction & Retention Strategy

This project presents a full end-to-end data science solution to a real-world churn problem in the telecommunications industry. It includes business-driven data exploration, churn segmentation, model development, and actionable recommendations — packaged in a professional executive report and supported by machine learning deployment.

---

## 🗂️ Table of Contents

- [Problem Statement](#problem-statement)
- [Project Overview](#project-overview)
- [EDA Analysis & Key Insights](#eda-analysis--key-insights)
- [Modeling Approach](#modeling-approach)
- [Business Impact](#business-impact)
- [Results Summary](#results-summary)
- [Tech Stack](#tech-stack)
- [Files & Structure](#files--structure)
- [Author](#author)
- [Status](#status)

---

## 🧠 Problem Statement

Customer churn directly impacts recurring revenue and profitability. The objective of this project is to **predict which customers are likely to churn** and to provide **data-driven strategies** for reducing churn and preserving lifetime value (LTV).

---

## 📂 Project Overview

| Phase                     | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Business Understanding    | Defined churn problem and goals aligned with stakeholder needs             |
| Exploratory Data Analysis | Uncovered churn patterns by contract type, payment method, age group, etc. |
| Feature Engineering       | Created behavioral and financial indicators (e.g., Engagement Score)        |
| Model Building            | Trained Logistic Regression, Random Forest, and XGBoost on 3 dataset versions |
| Evaluation                | Used precision, recall, and F1-score to focus on churn prediction quality   |
| Business Impact           | Estimated model-driven churn reduction of **7.34%** and retention of **$317K+** in LTV |

---

## 🔍 EDA Analysis & Key Insights

- **High churn rates** were observed among:
  - Month-to-month contract users
  - Solo customers not enrolled in group plans
  - Customers paying via Direct Debit or Paper Check
- **Higher monthly charges and frequent customer service calls** were strong predictors of churn.
- **Younger customers (<30) and seniors** showed slightly elevated churn risks.
- **Unlimited data plan users** also churned at a higher rate than expected, indicating potential dissatisfaction.
- **Business Segments Identified** for targeted retention campaigns based on churn drivers and LTV risk.

---

## 🤖 Modeling Approach

Three models were tested across multiple dataset versions (full data, feature-selected, and feature-engineered):

- Logistic Regression
- Random Forest
- XGBoost (final selected model)

Focus was placed on maximizing **recall and F1-score for churners** to prioritize early intervention and revenue preservation.

---

## 📈 Business Impact

- **Estimated Churn Reduction**: 7.34%  
- **Estimated Revenue Retention**: ~$317,000  
- **Model Recall**: 81% (catching majority of true churners)
- **Precision**: 85% (avoiding unnecessary interventions)

The model enables efficient retention targeting and protects customer lifetime value through early churn risk detection.

---

## 📈 Results Summary

- **Best Model**: XGBoost  
- **Accuracy**: 91.13%  
- **Precision (Churn)**: 85%  
- **Recall (Churn)**: 81%  
- **F1 Score (Churn)**: 83%

---

## 🛠️ Tech Stack

- Python, Pandas, Scikit-learn, XGBoost
- Matplotlib, Seaborn, Plotly
- Streamlit (upcoming frontend deployment)
- FastAPI (upcoming API deployment)

---


---

## 👤 Author

**Vijay Kumar**  
📫 [LinkedIn](https://www.linkedin.com/in/vijaykumar1997/)

---

## ✅ Status

✅ Report complete  
✅ Model trained & evaluated  
🔜 API + Streamlit deployment
