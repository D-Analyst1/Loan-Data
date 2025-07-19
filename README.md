# 🔍 Loan & Transaction Performance Analytics for Financial Decision-Making

<img width="351" height="144" alt="image" src="https://github.com/user-attachments/assets/280bf3ad-f51a-4bd8-8d18-925ead1fbb23" />


## 📊 Project Overview

This project presents an interactive Power BI dashboard that analyzes loan applications and transaction behavior. The goal is to deliver actionable insights for financial institutions by examining customer profiles, loan approval trends, transaction risks, and overall performance over time,  It allows users to navigate data across time, risk levels, and customer demographics in a meaningful way. The solution empowers financial institutions to better understand lending performance, identify high-value clients, and assess potential risks.

The dataset combines **loan applications** and **transactional data**, merged and modeled to enable a 360° view of customer financial activity.

---

## 🧠 Key Objectives

- Understand loan approval trends, risk, and interest rate patterns.
- Identify high-value customers and transaction behavior.
- Spot fraudulent activities and analyze post-transaction balances.
- Profile customers based on income and financial status.
- Monitor financial performance across time.

---

## 📁 Dataset Description

1. **Loan Applications Dataset**
   - `customer_id`
   - `loan_amount_requested`
   - `interest_rate_offered`
   - `application_date`
   - `loan_status`, `employment_type`, etc.

2. **Transaction Dataset**
   - `customer_id`
   - `transaction_amount`
   - `transaction_type`, `device`, `location`, `merchant_category`
   - `transaction_date`

These datasets were joined using relationships in Power BI, anchored by a unified calendar table.

---

## 🖥️ Dashboard Pages Breakdown

### 📌 Page 1 – Executive Overview

- **KPIs:** Total Loan Requests, Approved Loans, Total Customers, Avg. Loan Amount
- **Visuals:** 
  - Loan Distribution by Status
  - Transaction Summary by Type
  - Highest Spending Customers
  - Loan Type Breakdown

---

### 📌 Page 2 – Loan Analysis

- **Purpose:** Explore loan-specific trends and customer behavior.
- **Visuals:**
  - Bar Chart: Loan Amount by Employment Type
  - Comparative: Requested vs Approved (by Gender)
  - Matrix: Loan Status by Region/Marital Status
  - Line: Interest Rate Trend vs Tenure
  - Scatter: Monthly Income vs Loan Requested
  - Optional Heatmap: Loan Approval Rate by Month/Region

---

### 📌 Page 3 – Transaction Behavior & Risk

- **Purpose:** Investigate spending patterns, risk, and fraud insights.
- **Visuals:**
  - Transaction Breakdown by Type
  - Domestic vs International Spend
  - Fraud Risk by Device or Location
  - Line Chart: Account Balance Trend
  - Bar/Tree: Merchant Category Spend

---


### 📌 Page 4 – Performance Over Time

- **Purpose:** Monitor temporal trends and detect seasonality.
- **Visuals:**
  - Line Chart: Loan Requests by Month
  - Area Chart: Cash Flow Over Time
  - Decomposition Tree: Drilldown into Monthly Loan Patterns
  - Timeline Slicer: From Unified Calendar Table

---

## Dashboards

# Page 1

<img width="973" height="543" alt="image" src="https://github.com/user-attachments/assets/5873fe4a-4c37-4d8b-afb8-04163ca8ff61" />

# Page 2

<img width="968" height="550" alt="image" src="https://github.com/user-attachments/assets/8b8d02a0-9d80-40e5-97b4-a473ecaa904f" />

# Page 3

<img width="974" height="546" alt="image" src="https://github.com/user-attachments/assets/2dec7b7c-e77b-4726-a7fb-ccd97940c455" />

# Page 4

<img width="971" height="547" alt="image" src="https://github.com/user-attachments/assets/9b044abe-f057-44b4-897a-60a99cbcdadd" />





## 🛠️ Tools & Techniques Used

- **Power BI**: Visualizations, DAX, Relationships, Calendar Tables
- **Power Query**: Data Transformation & Cleaning
- **DAX Measures**: Custom KPIs (e.g., Avg Interest, Total Loans Approved)
- **Conditional Formatting**: Based on income, transaction value
  

---


## 📌 Recommendations


1. **Prioritize Financial Support for Low-Income but Responsible Borrowers**  
   The analysis identified customers with modest monthly incomes but strong repayment behavior. These individuals pose lower credit risk despite their income level. It is recommended that lenders introduce flexible loan packages or loyalty incentives tailored to this demographic to promote financial inclusion and long-term engagement.

2. **Strengthen Monitoring for High Loan Applicants with Irregular Transaction Patterns**  
   Some customers with high loan application amounts exhibit sparse or unusual transaction behavior. These cases require additional scrutiny. Lenders should flag such profiles for enhanced due diligence before approving new credit lines to minimize default risks.

3. **Targeted Customer Education for Regions with Lower Approval Rates**  
   Specific regions recorded significantly lower loan approval rates. This may be due to insufficient documentation, ineligibility, or poor application practices. Financial institutions should implement localized awareness campaigns and onboarding support to improve loan access and reduce rejection rates.

4. **Reassess Employment Segments with Low Loan Performance**  
   Applicants in freelance, informal, or gig-based employment categories show lower approval rates and inconsistent repayment patterns. Institutions are advised to build alternative scoring models or use non-traditional credit indicators (such as transaction trends or digital footprint) to fairly evaluate creditworthiness in these sectors.

5. **Develop Products for Active Transaction Customers with Low Loan Uptake**  
   A distinct customer segment is highly active in transactional behavior but has minimal engagement with credit products. This presents an opportunity to promote micro-loans, credit-builder products, or short-term financing tailored to their behavior, increasing loan penetration without significant risk exposure.

6. **Monitor Transaction Amount Spikes to Flag Financial Strain or Fraud**  
   Outliers with sudden spikes in transaction value could indicate either financial emergencies or potential fraud. Monthly monitoring of transaction anomalies should be adopted to proactively identify customers in distress or flag suspicious activities.

7. **Incorporate Seasonal Trends into Lending and Marketing Strategies**  
   Seasonal analysis uncovered clear patterns in loan applications and spending behavior. Financial institutions should leverage this by aligning campaign rollouts, promotional offers, and cash flow planning with periods of peak demand, such as festive months or year-end.



---  

## 🙌 Author

**[Onwuka Chukwuma]**  
Power BI Developer | Data Analyst   



