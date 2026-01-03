# ❤️ Heart Disease Prediction & Risk Analysis

## 📌 Project Overview
This project focuses on predicting the presence of heart disease using patient clinical data and identifying key medical risk factors that contribute to cardiovascular conditions.

---

## 🎯 Objectives
- Analyze healthcare data to understand heart disease risk patterns  
- Perform exploratory data analysis (EDA) on clinical attributes  
- Build a predictive machine learning model  
- Support early diagnosis and preventive healthcare decisions  

---

## 🧠 Methodology
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Training (Logistic Regression / Random Forest)  
- Model Evaluation  

---

## 🔍 Exploratory Data Analysis (EDA)

### Distribution of Heart Disease Cases
![Target Distribution](images/target_distribution.png)

*Shows the distribution of patients with and without heart disease.*

---

### Age Distribution by Heart Disease Status
![Age Distribution](images/age_distribution_by_target.png)

*Older patients exhibit a higher likelihood of heart disease.*

---

### Chest Pain Type vs Heart Disease
![Chest Pain vs Target](images/chest_pain_vs_target.png)

*Chest pain type shows a strong association with heart disease presence.*

---

### Correlation Heatmap of Clinical Features
![Correlation Heatmap](images/correlation_heatmap.png)

*Correlation analysis highlighting relationships between clinical attributes and heart disease.*

---

## 📊 Key Insights
- Age, chest pain type, exercise-induced angina, and ST depression strongly influence heart disease risk  
- Chest pain type and maximum heart rate show strong positive correlation with heart disease  
- Some traditional indicators such as cholesterol and fasting blood sugar show weaker predictive influence  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🚀 Results
The model helps identify high-risk patients, enabling early medical intervention and improved healthcare outcomes.

---

## 📂 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
