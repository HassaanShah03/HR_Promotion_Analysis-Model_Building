# HR_Promotion_Analysis-Model_Building

# 📊 HR Analytics: Employee Promotion Prediction

## 📌 Project Overview

This project analyzes employee data to identify key factors influencing promotions within an organization and builds a machine learning model to predict whether an employee will be promoted.

The goal is to combine **data analysis + machine learning** to generate actionable business insights and predictive capability.

---

## 🎯 Objectives

- Understand factors affecting employee promotion  
- Perform exploratory data analysis (EDA)  
- Derive meaningful business insights  
- Build and evaluate machine learning models  
- Predict promotion outcomes on unseen data  

---

## 📁 Dataset

The dataset contains employee-related information such as:

- Demographics (age, gender, region)  
- Department and education  
- Training performance  
- Work experience  
- Previous ratings  
- Promotion status (target variable)  

---

## 🧹 Data Preprocessing

- Handled missing values  
- Removed inconsistencies and duplicates  
- Converted categorical variables using encoding  
- Feature engineering (training score bins)  
- Ensured proper data types  

---

## 📊 Exploratory Data Analysis

Key analysis performed:

- Univariate analysis (distribution of features)  
- Bivariate analysis (feature vs promotion)  
- Department-wise promotion trends  
- Training score impact analysis  
- Advanced visualizations (bubble plots, heatmaps, binned analysis)  

---

## 🧠 Key Insights

- High training scores (80+) significantly increase promotion chances  
- Low-performing employees are rarely promoted  
- Age has minimal impact on promotions  
- Experience shows diminishing returns after mid-level  
- Promotion rates vary significantly across departments  
- Large departments tend to have lower promotion rates  
- Performance alone does not always guarantee promotion  

---

## 💼 Business Recommendations

- Strengthen performance-based promotion policies  
- Investigate low-performing departments  
- Improve transparency in promotion criteria  
- Focus on improving mid-range performers  
- Standardize evaluation across departments  
- Use high-performing departments as benchmarks  

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression (baseline)  
- Decision Tree  
- Random Forest  
- XGBoost (final model)  

### 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score (primary metric due to class imbalance)  

---

## 🚀 Final Model

**XGBoost Classifier** was selected as the final model due to:

- Best F1 Score  
- Balanced precision-recall tradeoff  
- Strong overall performance  

---

## 📈 Model Evaluation

- ROC-AUC Curve used to evaluate classification performance  
- Confusion Matrix used to analyze prediction accuracy  
- Feature Importance identified key drivers of promotion  

---

## 📦 Test Data Prediction

- Applied same preprocessing pipeline on unseen test data  
- Generated predictions using final model  
- Created submission file with predicted promotion labels  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

---

## 📌 Project Structure
