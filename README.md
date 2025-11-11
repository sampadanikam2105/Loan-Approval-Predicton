# 💰 Loan Approval Prediction Project

## 📘 Overview
This project predicts whether a loan application will be approved or not based on applicant information such as income, credit history, employment, and loan amount.  


---
## 🎯 Objective
To build a predictive model that can automatically classify loan applications as **Approved (1)** or **Not Approved (0)** using historical data.

---


## 🧩 Steps Followed
1. **Data Loading** — Import the dataset and understand structure.  
2. **Data Cleaning** — Handle missing values.  
3. **Encoding** — Convert categorical variables using LabelEncoder and OneHOtEncoder.  
4. **Feature Scaling** — Standardize numeric columns.
5. **SMOTE** - Balance data.
6. **Model Building** — Train Logistic Regression and XGBoost models.  
7. **Evaluation** — Compare models using Accuracy and Confusion Matrix.  
8. **Conclusion** — Identify the best-performing model for loan approval prediction.

---

## 📊 Dataset
- The dataset contains applicant details such as:
  - Gender, Married, Dependents, Education, Self_Employed,
    ApplicantIncome, CoapplicantIncome, LoanAmount, Credit_History, Property_Area  
  - Target variable: `Loan_Status` (Y = Approved, N = Rejected)

📁 **Dataset Source:** [Google Drive Link] https://drive.google.com/file/d/1-Pa_ll25_eMEofNW5ZtEdIclx_MQDJ8A/view?usp=sharing

---

## ⚙️ Technologies Used
| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Core language |
| **Pandas, NumPy** | Data handling |
| **Matplotlib, Seaborn** | Visualization |
| **Scikit-learn** | Machine Learning (Logistic Regression, scaling, splitting) |
| **SMOTE** | Balance data|
| **XGBoost** | Boosted model for improved accuracy |
| **Google Colab Notebook** | Development environment |

---

## 🧮 Model Performance
| Model | Accuracy | 
|--------|-----------|
| Logistic Regression | 0.75 | 
| XGBoost | 0.71 | 


---

## 📈 Key Insights
- Applicants with a **strong credit history** are more likely to get loan approval.  
- **Higher applicant income** improves approval probability.  
- Education level and Total Income also influence loan decisions.  


