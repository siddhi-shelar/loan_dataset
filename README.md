# loan_dataset
Loan Approval Prediction

This project predicts whether a loan will be **Paid Off (Approved)** or **Defaulted (Collection)** using a machine learning model.  
It is based on the dataset **Loan payments data.csv** which contains information about loan applicants, their demographics, and repayment status.

---

## 🚀 Features
- Preprocesses raw loan dataset (encoding categorical features).
- Handles class imbalance using **SMOTE**.
- Trains a **Random Forest Classifier** to predict loan outcomes.
- Provides a function to test **new loan applicants** and predict:
  - `PAIDOFF` → Loan approved and repaid.
  - `COLLECTION` → Loan defaulted (not repaid).
  - `COLLECTION_PAIDOFF` → Initially late but later repaid.

---

## 📂 Dataset
The dataset contains the following columns:
- `Loan_ID` → Unique loan identifier  
- `loan_status` → Target variable (`PAIDOFF`, `COLLECTION`, `COLLECTION_PAIDOFF`)  
- `Principal` → Loan amount  
- `terms` → Loan term (15 or 30 days)  
- `effective_date` → Loan start date  
- `due_date` → Loan repayment date  
- `paid_off_time` → Actual repayment date  
- `age` → Age of borrower  
- `education` → Education level (`High School or Below`, `College`, `Bechalor`, `Master or Above`)  
- `Gender` → Male / Female  

