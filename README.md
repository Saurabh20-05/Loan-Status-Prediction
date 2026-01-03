# 🏦 Loan Status Prediction using Support Vector Machine (SVM)

This project uses **Support Vector Machine (SVM) Classification** to predict whether a **loan will be approved or not** based on applicant details such as income, education, marital status, employment, and property area.  
The model is trained on a **Loan Approval Dataset** (`loan_dataset.csv`) to accurately classify loan approval status.

---

## 📘 Project Overview

This is a **Supervised Machine Learning** based **Binary Classification** project.  
By analyzing applicant and financial attributes, the model predicts the **loan approval status** (`Approved` / `Not Approved`).  
The goal is to build an efficient, accurate, and reliable **loan eligibility prediction system** using a **Linear SVM Classifier**.

---

## 🗂️ Dataset Information

**Dataset Name:** Loan Approval Dataset  
**Format:** CSV file (`loan_dataset.csv`)

### 📌 Columns

- **Loan_ID** → Unique loan identifier  
- **Gender** → Applicant gender  
- **Married** → Marital status  
- **Dependents** → Number of dependents  
- **Education** → Education level  
- **Self_Employed** → Employment status  
- **ApplicantIncome** → Applicant income  
- **CoapplicantIncome** → Co-applicant income  
- **LoanAmount** → Loan amount  
- **Loan_Amount_Term** → Loan repayment term (in months)  
- **Credit_History** → Credit history record  
- **Property_Area** → Area type (Rural / Semiurban / Urban)  

### 🎯 Target Variable

- **Loan_Status**
  - `1` → Loan Approved  
  - `0` → Loan Not Approved  

---

## 🧠 Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## ⚙️ Project Workflow

1. Load the dataset using Pandas  
2. Display the first few rows and dataset dimensions  
3. Perform statistical analysis using `describe()`  
4. Check missing values using `isnull().sum()`  
5. Handle missing values by dropping null rows  
6. Encode target variable (`Loan_Status`)  
7. Convert categorical features into numerical values  
8. Perform data visualization using count plots  
9. Split features and target:
   - **X** → All columns except `Loan_ID` and `Loan_Status`  
   - **Y** → `Loan_Status`  
10. Split the dataset into **90% training** and **10% testing**  
11. Train the model using **Support Vector Machine (Linear Kernel)**  
12. Evaluate model performance using **Accuracy Score**  
13. Build a predictive system for custom user input  

---

## 📊 Model Performance

### ✅ Training Data
- Accuracy Score : **High**

### ✅ Testing Data
- Accuracy Score : **Slightly lower than training accuracy**

This shows that the model performs well and generalizes effectively on unseen data.

---

## 🧪 Predicting Custom Input

You can paste any row from the dataset in the following format:

Input_data: (Male,Yes,0,Not Graduate,No,2583,2358,120,360,1,Urban)

Output = 
**Loan Approved**

OR

**Loan Not Approved**

---

## 👨‍💻 Author

Developed by **Saurabh**

Feel free to connect or contribute to this project!

⭐ If you found this project helpful, don’t forget to star the repository!
