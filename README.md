# Employee Attrition Prediction using Machine Learning

##  Overview
Employee attrition is a major challenge for organizations as it leads to increased hiring costs, loss of experienced employees, and reduced productivity.  

This project analyzes employee data and applies machine learning models to predict whether an employee is likely to leave the company. The goal is to identify key factors driving attrition and provide actionable business insights to improve employee retention.

---

##  Objectives
- Analyze patterns and factors influencing employee attrition  
- Build predictive models to classify employees at risk of leaving  
- Compare multiple machine learning models  
- Translate technical results into business recommendations  

---

##  Dataset
- Source: IBM HR Analytics Employee Attrition Dataset (Kaggle)  
- Records: 1,470 employees  
- Features: 35 variables (demographics, job-related, performance)  
- Target Variable: `Attrition` (Yes/No)

---

##  Exploratory Data Analysis (EDA)
Key insights from the data include:

- Employees working overtime are more likely to leave  
- Lower income is associated with higher attrition  
- Certain job roles (e.g., Sales Executive) show higher turnover  
- Younger employees tend to leave more frequently  
- Dataset is imbalanced (more employees stay than leave)

---

##  Methodology
- Data cleaning and preprocessing  
- One-hot encoding for categorical variables  
- Train-test split (80-20)  
- Feature scaling using StandardScaler  

### Models Used:
- Logistic Regression (baseline model)  
- Decision Tree Classifier  
- Random Forest Classifier  

---

##  Model Evaluation
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

### Key Finding:
Random Forest achieved the highest accuracy, but showed relatively low recall, meaning it missed some employees who are likely to leave.

---

##  Feature Importance
The most important factors influencing attrition include:
- Monthly Income  
- Age  
- Overtime  
- Years at Company  

---

##  Business Insights & Recommendations
- Reduce excessive overtime to improve work-life balance  
- Review compensation structures for lower-income employees  
- Focus retention strategies on high-risk job roles  
- Provide career growth opportunities for younger employees  

---

##  Limitations
- Dataset is imbalanced, affecting recall  
- Limited features (no data on company culture or satisfaction surveys)  
- Models can be improved with tuning and better feature engineering  

---

##  Future Improvements
- Handle class imbalance using SMOTE or class weighting  
- Apply hyperparameter tuning  
- Explore advanced models such as XGBoost  
- Incorporate additional employee-related features  

---

##  Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Google Colab  

---

##  Author
Talha Qazi  
MS Business Analytics  
Suffolk University  

---
