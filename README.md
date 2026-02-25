# 🏦 Bank Loan Analysis

A comprehensive loan portfolio analysis project focused on understanding loan performance, borrower behavior, portfolio risk, and profitability.  
This project applies data analytics techniques using Python to derive business insights from structured lending data.

---

## 📌 Business Problem

Financial institutions process thousands of loan applications across different borrower profiles, regions, and loan purposes.  
However, without structured analysis, it becomes difficult to evaluate:

- Borrower repayment behavior  
- Portfolio profitability and losses  
- Seasonal demand patterns  
- High-risk vs. low-risk segments  
- Core lending KPIs  

This project addresses these challenges by analyzing historical loan data to uncover performance trends, risk drivers, and strategic opportunities.

---

## 🎯 Project Objectives

- Calculate and interpret key lending KPIs  
- Compare Good Loans vs. Bad Loans  
- Identify profitable and high-risk borrower segments  
- Analyze portfolio trends across multiple dimensions  
- Generate business-focused recommendations  

---

## 🛠️ Tools & Technologies

- **Python** – Data analysis and visualization  
- **Pandas / NumPy** – Data cleaning and transformations  
- **Matplotlib / Seaborn** – Visual analytics  
- **Jupyter Notebook** – Analysis workflow  

---

## 📊 Dataset Overview

The dataset contains borrower demographics, financial indicators, loan attributes, and repayment status.

### Preprocessing Performed

- Removed incomplete and invalid records  
- Standardized categorical and numerical formats  
- Converted DTI, income, term, and interest rates to numeric values  
- Derived month and year features for trend analysis  
- Categorized loans into:
  - **Good Loans (Fully Paid)**
  - **Bad Loans (Charged Off)**

---

## 📈 Key KPIs

| KPI | Value |
|------|--------|
| Total Loan Applications | 38,576 |
| Total Funded Amount | $435.76M |
| Total Amount Received | $473.07M |
| Net Portfolio Return | $37.31M |
| Average Interest Rate | 12.05% |
| Average DTI | 13.33% |

---

## 🔍 Key Insights

- The portfolio remains profitable with a net return of **$37.31M**  
- **86.18%** of loans are fully paid, indicating strong repayment behavior  
- Losses are primarily driven by charged-off loans  
- Significant concentration observed across:
  - California region
  - Debt Consolidation loans
  - 36-month loan terms  

---

## ⚠️ Risk Observations

- Higher default exposure among renters and short-tenure employees  
- Regional dependency introduces concentration risk  
- Certain loan purposes contribute disproportionately to losses  

---

## ✅ Business Recommendations

**Risk Control**
- Strengthen underwriting for higher-risk borrower groups  
- Implement risk-based pricing strategies  

**Portfolio Diversification**
- Reduce geographic and product concentration  
- Expand into additional borrower segments  

**Profitability Optimization**
- Focus on lower-risk, higher-repayment profiles  

---

## 📁 Project Structure
