# AI-Driven Developer Stress Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting the stress levels of software developers using machine learning techniques.  
The model leverages productivity, behavioral, and performance-related metrics to identify patterns that contribute to developer stress.

Early stress prediction can help organizations reduce burnout, improve productivity, and promote a healthier work environment.

---

## 🎯 Problem Statement
To build a machine learning model that accurately predicts the **Stress_Level** of software developers based on performance metrics such as coding hours, sleep patterns, cognitive load, task duration, and error rates.

---

## 📊 Dataset Description
- **Dataset Name:** AI_Developer_Performance_Extended_1000.csv  
- **Records:** 1000  
- **Type:** Structured CSV dataset  

### Features:
- Hours_Coding
- Lines_of_Code
- Bugs_Found
- Bugs_Fixed
- AI_Usage_Hours
- Sleep_Hours
- Cognitive_Load
- Task_Success_Rate
- Coffee_Intake
- Task_Duration_Hours
- Commits
- Errors

🎯 **Target Variable:** Stress_Level (0–100)

---

## 🧠 Approach
The project follows a complete end-to-end machine learning workflow:

1. Data Loading & Understanding  
2. Exploratory Data Analysis (EDA)  
3. Data Preprocessing & Feature Scaling  
4. Train-Test Split  
5. Model Training  
   - Linear Regression (Baseline Model)  
   - Random Forest Regressor (Final Model)  
6. Model Evaluation  
7. Feature Importance Analysis  
8. Prediction on New Data  

---

## 🤖 Machine Learning Models Used
- **Linear Regression**
- **Random Forest Regressor**

Random Forest was selected as the final model due to its superior performance in capturing non-linear relationships in human behavior data.

---

## 📈 Model Performance

| Model | R² Score | RMSE |
|------|---------|------|
| Linear Regression | ~0.60 | Higher |
| Random Forest | ~0.88 | Lower |

---

## 🔍 Key Insights
- Cognitive load is the strongest contributor to stress levels  
- Reduced sleep significantly increases stress  
- Long coding hours combined with high cognitive load lead to burnout  
- Moderate AI usage helps reduce stress  
- Higher error rates correlate with increased stress  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---
💼 Business Applications

Early detection of developer burnout

Workforce stress analytics

Productivity optimization

AI-assisted workload planning

---
⚠️ Limitations

Dataset is simulated and may not represent real-world conditions

Psychological and emotional factors are not included

Model performance may vary with different datasets

---
🔮 Future Scope

Integration with real-time developer activity data

Deployment as a web application (Streamlit/Flask)

Time-series stress prediction

Inclusion of psychological assessment metrics

---

\
   git clone https://github.com/your-username/ai-developer-stress-prediction.git
