# 📊 Telco Customer Churn Analysis

## 📌 Project Overview
This project analyzes customer churn behavior in a telecom company using a complete data analytics workflow.  
The goal is to identify key factors driving churn and provide actionable insights to improve customer retention.

---

## 🎯 Objectives
- Analyze customer churn patterns  
- Identify high-risk customer segments  
- Understand the impact of pricing, contracts, and services  
- Quantify revenue loss due to churn  
- Build an interactive dashboard for business decision-making  

---

## 🛠️ Tools & Technologies
- **Excel** – Initial data inspection and cleaning  
- **Python (Pandas, Matplotlib, Seaborn)** – Data cleaning and exploratory data analysis (EDA)  
- **SQL (SQLite)** – Business queries and aggregation  
- **Power BI** – Data modeling, DAX measures, and dashboard visualization  

---

## 🔄 Project Workflow

### 1. Data Cleaning (Python)
- Converted `TotalCharges` to numeric format  
- Handled missing values  
- Encoded categorical variables (e.g., Churn → 0/1)  
- Removed irrelevant columns (e.g., customerID)  
- Exported cleaned dataset  

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution  
- Compared churn across:
  - Contract types  
  - Payment methods  
  - Internet services  
- Investigated relationships between:
  - Monthly charges and churn  
  - Tenure and churn  

---

### 3. SQL Analysis
- Calculated overall churn rate  
- Analyzed churn by contract type  
- Evaluated churn by payment method  
- Identified high-risk customer segments  

---

### 4. Power BI Dashboard
- Built a **star schema model**  
- Created DAX measures:
  - Total Customers  
  - Churned Customers  
  - Churn Rate  
  - Total Revenue  
  - Churned Revenue  
- Designed an interactive dashboard with:
  - KPI cards  
  - Churn drivers  
  - Customer behavior analysis  
  - Filters for segmentation  

---

## 📈 Key Insights

1. **High Overall Churn Rate (~26.6%)**  
   A significant portion of customers are leaving, indicating retention challenges.

2. **Month-to-Month Contracts Drive Churn**  
   Customers on short-term contracts are far more likely to churn than long-term customers.

3. **Payment Method Influences Churn**  
   Certain payment methods (e.g., electronic check) are associated with higher churn.

4. **Fiber Optic Customers Show Higher Churn**  
   This may indicate pricing or service quality issues.

5. **Higher Monthly Charges Increase Churn Risk**  
   Customers paying more are more likely to leave, suggesting pricing sensitivity.

6. **New Customers Are Most Likely to Churn**  
   Low-tenure customers show higher churn, pointing to onboarding issues.

7. **Revenue Loss Due to Churn is Significant**  
   A notable portion of total revenue is lost from churned customers.

---

## 💡 Recommendations

- Encourage long-term contracts through incentives  
- Improve onboarding experience for new customers  
- Review pricing strategy for high-charge segments  
- Enhance service quality for fiber optic users  
- Simplify and optimize payment systems  

---



## 📁 Project Structure
