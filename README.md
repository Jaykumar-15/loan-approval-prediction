# Loan Approval Prediction System

## 📌 Overview
This project predicts whether a loan application should be **Approved or Rejected** using Machine Learning.  
It uses applicant financial and demographic data to assist in decision-making.

---

## 🏦 Problem Statement
Loan approval is traditionally a manual and time-consuming process.  
There is a risk of:
- Rejecting eligible applicants  
- Approving high-risk applicants  

This project builds a Machine Learning model to automate and improve loan approval decisions.

---

## 🎯 Objective
- Build a classification model for loan approval prediction  
- Reduce manual decision errors  
- Improve consistency using data-driven insights  

---

## 🧠 Approach
The project follows a standard ML pipeline:

1. Data Loading  
2. Data Exploration (`df.head()`, `df.info()`, `df.describe()`)  
3. Handling Missing Values  
4. Feature Encoding (Label Encoding + One-Hot Encoding)  
5. Train-Test Split  
6. Model Training  
7. Model Evaluation  

---

## 🤖 Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

---

## 📊 Evaluation Metrics
- Precision  
- Recall  
- F1-score  
- Accuracy  

👉 Evaluation is done using `classification_report`

---

## 📂 Dataset Features
The dataset contains applicant information such as:

- Income (Applicant & Co-applicant)  
- Employment Status  
- Credit Score  
- Loan Amount & Term  
- Savings & Collateral  
- Property Area  
- Education Level  
- Existing Loans  
- Debt-to-Income Ratio  

**Target Variable:**
- `Loan_Approved` → 1 (Approved), 0 (Rejected)

---

## 🔄 Workflow Summary
- Cleaned and prepared dataset  
- Encoded categorical variables  
- Trained multiple ML models  
- Compared model performance  
- Selected best-performing model  

---

## 📸 Results

### Dataset Preview
![Dataset](images/img_01.png)

### Data Information
![Info](images/img_02.png)

### Missing Values Handling
![Missing](images/img_03.png)

### Feature Encoding
![Encoding](images/img_04.png)

### Model Evaluation (Classification Report)
![Results](images/img_06.png)
---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
