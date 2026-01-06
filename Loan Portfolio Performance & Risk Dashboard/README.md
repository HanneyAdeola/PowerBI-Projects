# Loan Portfolio: Risk & Repayment Analysis

## 📌 Project Overview

This project presents a **dual-dashboard analysis** of **Fintrust’s $1.51B loan portfolio**, combining **credit risk metrics** with **repayment performance insights** to deliver a 360-degree view of portfolio health.

Using **SQL for data processing** and **Power BI for visualization**, the analysis identifies high-risk segments, evaluates repayment efficiency, and provides actionable recommendations to improve underwriting decisions, collections strategy, and overall profitability.

---

## 🎯 Objectives

The key objectives of this project are to:

- Assess the overall financial health and risk exposure of the loan portfolio  
- Identify loan products and customer segments with the highest default risk  
- Analyze repayment performance across regions, time periods, and payment methods  
- Provide data-driven recommendations to optimize portfolio strategy and cash flow  

---

## 🧰 Tools & Technologies

### SQL (MySQL)
- Data aggregation and table joins  
- KPI calculations (Default Rate, Collection Rate, Outstanding Balance)  
- Segmentation by product type, region, and employment category  

### Power BI
- Interactive dashboard development  
- Risk and repayment trend visualization  
- Drill-down analysis by segment and geography  

### Data Analysis
- Root-cause analysis of high-default segments  
- Comparative performance evaluation across products and regions  

---

## 📊 Dataset Description

The analysis is based on a structured loan portfolio dataset containing:

- **Loan Disbursements:** Loan amount, product type, borrower, region, and disbursement date  
- **Repayment Transactions:** Amount paid, payment mode, and transaction date  
- **Borrower Demographics:** Employment type (Self-Employed, Employed, Student, Unemployed)  
- **Loan Products:** Education, SME, Salary Advance, and Personal loans  

The dataset covers **1,000 unique borrowers**, tracking performance from loan disbursement through repayment cycles.

---

## 📈 Key Performance Indicators (KPIs)

### Portfolio Overview (Risk Dashboard)

- **Total Loan Disbursed:** $1,510,745,071  
- **Expected Repayment:** $1,702,456,118  
- **Amount Collected:** $773,020,292  
- **Outstanding Balance:** $929,435,826  
- **Overall Default Rate:** 16%  
- **Unique Borrowers:** 1,000  

### Repayment Performance (Repayment Dashboard)

- **Total Amount Paid:** $773,020,292  
- **Top Repaying Region:** Abuja Kubwa ($220.2M)  
- **Top Repaying Segment:** Self-Employed ($222.4M)  
- **Preferred Payment Mode:** Bank Transfer ($261.8M)  

---

## 🔍 Key Insights

### 1. Risk Concentration & Product Performance

- **Education Loans** represent the largest portfolio share ($401.9M) but record the **highest default rate (26.51%)**, indicating significant credit risk.
- **Salary Advance Loans** have the **lowest default rate (10.63%)**, making them the most stable and sustainable product.
- **Self-Employed borrowers** received the highest funding ($443M) with a manageable **16% default rate**.

### 2. Repayment Efficiency Analysis

- **Abuja Kubwa** is the top-performing region for repayments ($220.2M), suggesting strong repayment discipline or effective collections.
- **Bank Transfers** are the dominant repayment method ($261.8M), highlighting customer preference and reliability.
- Monthly repayments remain relatively stable, with mild seasonal fluctuations.

### 3. Integrated Risk–Repayment Profile

| Segment | Risk Profile | Repayment Performance | Strategic Implication |
|------|-------------|----------------------|----------------------|
| Education Loans | 🔴 High Risk (26.51%) | Moderate ($200.1M) | Urgent underwriting and collection review |
| Self-Employed Borrowers | 🟡 Medium Risk | 🟢 Strong ($222.4M) | Monitor and segment further |
| Abuja Kubwa Region | 🟡 Medium Risk | 🟢 Top Performer ($220.2M) | Replicate best practices |

---

## 🌍 Regional & Segment Analysis

- **Top Disbursement Regions:** Lagos Island, Lagos Mainland  
- **Top Repayment Regions:** Abuja Kubwa, Ikeja  
- **Employment Type Distribution:**
  - Self-Employed: 29.3%
  - Employed: 25.1%
  - Unemployed: 23.4%
  - Student: 22.2%
- **Monthly Trends:**
  - Loan disbursement peaked in April ($178M)
  - Repayments show consistent monthly patterns

---

## 🖼️ Dashboard Previews

### Risk Dashboard
![](./Dashboard%203.png)

### Repayment Dashboard
![](./Dashboard%204.png)

---
---

## 💡 Recommendations & Action Plan

| Priority | Action | Expected Impact |
|--------|--------|----------------|
| 🟢 Immediate | Targeted collections for delinquent Education loans | Improved cash recovery |
| 🟢 Immediate | Revise Education loan underwriting criteria | Reduced future defaults |
| 🟡 Short-Term | Scale Salary Advance loan offerings | Improved portfolio risk mix |
| 🟡 Short-Term | Replicate Abuja Kubwa collection practices | Higher regional efficiency |
| 🔴 Strategic | Enhance credit scoring with risk–repayment insights | Better long-term risk prediction |

---

## 📌 Conclusion

This analysis reveals that **Fintrust’s portfolio performance is constrained by high-risk Education loans**, while **Salary Advance products and the Abuja Kubwa region demonstrate strong repayment efficiency**.

By addressing underwriting gaps, strengthening collections, and leveraging top-performing segments, Fintrust can significantly improve portfolio health, reduce defaults, and drive sustainable profitability through data-driven decision-making.

---


