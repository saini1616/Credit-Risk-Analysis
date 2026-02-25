# 📊 Credit Risk Analysis & Prediction Dashboard

An end-to-end analytics project focused on evaluating loan default risk using SQL, Python, and Power BI.  
The project transforms raw loan applicant data into predictive insights and an interactive dashboard for credit risk monitoring.

---

## 📌 Project Overview

Financial institutions must assess borrower risk accurately to minimize defaults and optimize portfolio performance.  
This project develops a complete analytical pipeline to:

- Clean and transform loan applicant data  
- Engineer risk-relevant features  
- Train predictive models  
- Estimate default probabilities  
- Visualize portfolio risk metrics  

---

## 🛠️ Tech Stack

- **SQL (PostgreSQL, pgAdmin4)** – Data cleaning, transformations, feature engineering  
- **Python (Pandas, Scikit-learn, XGBoost, Random Forest)** – Model training & evaluation  
- **Power BI** – Dashboard design & visualization  

---

## 🔑 Implementation Workflow

### **1️⃣ Data Preparation (SQL)**

- Imported raw loan applicant dataset into PostgreSQL  
- Cleaned missing values using:
  - Median imputation (numeric variables)
  - Mode imputation (categorical variables)

- Engineered predictive features:
  - Loan-to-Income Ratio  
  - Employment Category (Binned Employment Length)  
  - Age Bands, Income Bands, Interest Rate Bands  

- Validated data distributions and default rates across categories  

---

### **2️⃣ Machine Learning (Python)**

- Encoded categorical variables using **OneHotEncoder**  
- Built predictive pipelines with:
  - Random Forest  
  - XGBoost  

- Performed hyperparameter tuning using **GridSearchCV**

**Model Performance**

- Accuracy: ~93%  
- Recall (Defaults): ~75% after XGBoost tuning  

- Extracted feature importance rankings  
- Generated default predictions and probabilities  
- Enabled scalable inference for **5,000+ applicants**

---

### **3️⃣ Dashboard Development (Power BI)**

- Imported processed dataset into Power BI  
- Developed DAX measures:

  - Default Probability  
  - Actual Loss (Observed Defaults)  
  - Expected Loss = Exposure × PD × LGD  

- Designed interactive dashboard with filters for:
  - Loan Intent  
  - Loan Grade  
  - Income Range  

---

## 📈 Portfolio Metrics Snapshot

- Good Loans: 78.18%  
- Default Rate: 22%  
- Predicted Defaults: 21.82%  
- Expected Loss: $68.16M  
- Total Loan Amount at Risk: $77M  

---

## 🔍 Key Insights

- Loan Grades **F and G** exhibit default rates exceeding 70%  
- Debt Consolidation loans contribute the largest share of defaults  
- **Loan-to-Income Ratio** and **Interest Rate** are dominant predictors  
- Early-career borrowers show elevated risk levels  
- XGBoost demonstrated superior recall compared to Random Forest  

---

## 🚀 How to Run

1. Clone the repository  
2. Execute SQL scripts in PostgreSQL for data preparation  
3. Run `model_training.ipynb` for model evaluation  
4. Open the Power BI dashboard file to explore insights  

---

## 🔮 Future Enhancements

- Deploy model via Flask API for real-time scoring  
- Integrate live scoring into Power BI  
- Extend analysis with survival modeling  
- Explore advanced ML architectures  

---

## 📌 Conclusion

This project demonstrates how SQL, machine learning, and business intelligence tools can be combined to evaluate credit risk, estimate default probabilities, and support data-driven lending decisions.

---

## ⚠️ Note

This repository is recreated for learning and analytical practice using publicly available datasets and analytical concepts.
