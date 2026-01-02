# 🏠 Home Loan Approval – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Home Loan Approval dataset to uncover patterns, trends, and key factors that influence loan approval decisions. The analysis helps understand borrower behavior and provides a strong foundation for building predictive models in the future.

The dataset contains applicant demographic details, income information, credit history, loan characteristics, and property details. Through systematic data cleaning, visualization, and analysis, meaningful business insights were derived.

---

## 🎯 Objectives

* Understand borrower demographics and financial profiles
* Analyze factors affecting loan approval and loan amounts
* Identify data quality issues such as missing values and outliers
* Apply suitable data preprocessing techniques
* Extract actionable insights for financial decision-making

---

## 🧰 Tools & Technologies Used

* **Python**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – static visualizations
* **Plotly** – interactive visualizations

---

## 📂 Dataset Information

* **Rows:** 367
* **Columns:** 12
* **Target Context:** Loan approval analysis

### Key Features:

* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Gender, Married, Education, Dependents
* Self_Employed, Property_Area

---

## 🧹 Data Cleaning & Preprocessing

* Checked and handled missing values

  * Categorical columns filled using **mode**
  * Numerical columns filled using **mean**
* Verified and removed inconsistencies
* Applied **IQR-based outlier capping (Winsorization)** to:

  * ApplicantIncome
  * CoapplicantIncome
  * LoanAmount
  * Loan_Amount_Term

This ensured reduced skewness while retaining all data points.

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Income and loan amounts are **right-skewed**
* Most loan terms cluster around **360 months**
* Coapplicant income is zero for the majority of applicants

### 🔹 Bivariate Analysis

* Applicant income shows a **positive relationship** with loan amount
* Credit history strongly influences sanctioned loan amounts
* Loan terms are largely **policy-driven**, not amount-driven

### 🔹 Multivariate Analysis

* ApplicantIncome and LoanAmount are positively correlated
* CoapplicantIncome has a moderate influence on loan size
* Credit_History acts as a critical but independent risk indicator

---

## 👥 Demographic Insights

* Majority applicants are **male and married**
* Most applicants are **graduates**
* Salaried individuals dominate over self-employed applicants
* **Semiurban and urban areas** show higher loan application activity

---

## ✅ Key Takeaways

* Income and credit history are the strongest drivers of loan decisions
* Outlier treatment significantly improves data reliability
* Borrower demographics reveal clear lending patterns
* The dataset is well-suited for **predictive modeling** in future work

---

## 🚀 Future Scope

* Build machine learning models for loan approval prediction
* Feature engineering and encoding for categorical variables
* Model evaluation using classification metrics
* Bias and fairness analysis in loan approval decisions

---

## 👤 Author

**Monu Gupta**
Aspiring Data Analyst | Python | SQL | Data Analytics

📧 Email: [monugupta8758@gmail.com](mailto:monugupta8758@gmail.com)

---

⭐ If you found this project insightful, feel free to star the repository and share feedback!
