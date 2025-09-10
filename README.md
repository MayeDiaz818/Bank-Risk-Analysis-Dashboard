# 💳 Financial Risk Analysis Dashboard  

## 📌 Introduction  
This project focuses on **Bank Risk Analysis**, aiming to evaluate the probability of a client representing a financial risk for the bank.  

It addresses key questions such as:  
- Will the customer default on a loan?  
- Does the client have enough assets to cover liabilities?  
- Is the financial behavior stable or risky?  
- What is the exposure across financial products?  

By answering these questions, financial institutions can make better decisions on:  
- Loan approvals  
- Credit card limits  
- Customer loyalty strategies  
- Interest rates & loan conditions  

---

## 🎯 Project Objective  
Develop an end-to-end **risk analytics solution** using:  
- **Python** → Data cleaning, feature engineering, exploratory analysis  
- **Power BI** → KPI tracking, interactive dashboards, creditworthiness evaluation  

The goal is to enable banking institutions to minimize the risk of financial losses while lending.  

---

## ⚙️ Tools & Technologies  
- **Python** → Pandas, Matplotlib, Seaborn  
- **Power BI Desktop** → Dashboards & reports  
- **GitHub** → Documentation & project sharing  

---

## 📊 Dashboard Overview   

### Page 1 – Client Demographics & Portfolio Overview  
- Distribution of clients by **Gender, Nacionality & Loyalty distribution**   
- Key metrics: Averages of Estimated Income, Savings, Deposits and Loans

![Dashboard 1](Bank-Risk-Analysis-Dashboard/Images/Portafolio_overview.jpg) 
 
### Page 2 – Risk Analysis and Correlations  
- Breakdown of financial products across **Risk Level**  
- Comparison of income, deposits, loans, savings.
- Correlation of numerical variables
  
![Dashboard 2](Bank-Risk-Analysis-Dashboard/Images/Risk_Analysis_Correlation.jpg)

### Page 3 – Creditworthiness Evaluation  
- KPIs: Debt-to-Income Ratio, Debt-to-Asset Ratio, Loan Ratios  
- **Approval / Review / Rejection** classification model  
- Client segmentation with filters (Age Group, Loyalty Tier)

![Dashboard 3](Bank-Risk-Analysis-Dashboard/Images/Creditworthiness_Evaluation.jpg) 

You can explore the **Power BI report** here:  

➡️ [Download Bank Risk Dashboard (.pbix)](Bank-Risk-Analysis-Dashboard/Report/Risk_Analysis_Dashboard.pbix)

---

## 📈 Insights from Data  
- Most clients maintain a **Loan-to-Deposit Ratio < 2**, though a few outliers (>20) suggest aggressive borrowing.  
- Average **Loan-to-Income Ratio ~4.7**, indicating manageable leverage for most clients.  
- **Debt-to-Asset Ratio** shows extreme outliers (up to 544), highlighting over-leveraged customers.  
- The dashboard enables **credit approval decisions** based on customer profiles.  

---

## 🚀 How to Run the Project  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Bank-Risk-Analysis-Dashboard.git
   cd Bank-Risk-Analysis-Dashboard
