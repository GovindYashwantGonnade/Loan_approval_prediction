# Loan Approval Prediction  

This project predicts **loan approval status** using machine learning models. The dataset (`loan.xlsx`) was cleaned, preprocessed, and used to train multiple classifiers.  

---

## 🔑 Key Steps  
- **Data Cleaning**  
  - Filled missing values → categorical with **mode**, numerical with **mean**  
  - Created `TotalIncome = ApplicantIncome + CoapplicantIncome`  
  - Applied log transformation to skewed attributes  

- **Exploratory Data Analysis (EDA)**  
  - Count plots for categorical features  
  - Histogram plots for `LoanAmount_log` and `TotalIncome`  

- **Preprocessing**  
  - Label Encoding for categorical features  
  - Train-test split and scaling using **StandardScaler**  

- **Model Training**  
  - Algorithms: **Naive Bayes, Random Forest, Decision Tree, KNN**  
  - ✅ **Best Model → Naive Bayes** with **82.92% accuracy**  

---

## ⚙️ Tools & Libraries  
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📌 Conclusion  
Naive Bayes outperformed other models, achieving **82.92% accuracy**.  
This project demonstrates a complete ML workflow — from **data preprocessing** and **feature engineering** to **model training and evaluation**.  
