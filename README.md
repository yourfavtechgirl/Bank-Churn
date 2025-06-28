
# 🏦 Bank Customer Churn Analysis Dashboard (Power BI)

## 📌 Project Overview

This project uses Power BI to explore and visualize customer churn patterns for a telecommunications/banking service provider. The dashboard provides actionable insights to help stakeholders understand which customers are most likely to churn, why they're leaving, and how to potentially improve customer retention.

---

## 🎯 Business Objectives

- Identify key factors contributing to customer churn
- Segment customers by churn category and reason
- Analyze usage patterns, service types, and revenue impact
- Support decision-making on loyalty, upselling, and customer service

---

## 🧾 Dataset Description

The dataset contains detailed customer profiles with demographic, service usage, and churn outcome data. Key columns include:

### 🔑 Customer Info
- `Customer_ID`, `Gender`, `Age`, `Married`, `State`, `Number_of_Referrals`, `Tenure_in_Months`

### 📶 Services & Usage
- `Phone_Service`, `Multiple_Lines`, `Internet_Service`, `Internet_Type`
- `Online_Security`, `Online_Backup`, `Device_Protection_Plan`
- `Streaming_TV`, `Streaming_Movies`, `Streaming_Music`, `Unlimited_Data`

### 💳 Billing & Contracts
- `Contract`, `Paperless_Billing`, `Payment_Method`
- `Monthly_Charge`, `Total_Charges`, `Total_Refunds`, `Total_Extra_Data_Charges`, `Total_Long_Distance_Charges`, `Total_Revenue`

### ❌ Churn Labels
- `Customer_Status` (e.g., Active, Churned, Joined)
- `Churn_Category` (e.g., Voluntary, Involuntary, Competitor)
- `Churn_Reason` (e.g., Poor customer service, High pricing)

---

## 📊 Dashboard Highlights

The Power BI dashboard includes:

### 📌 Key Metrics
- Total Customers
- Overall Churn Rate
- Revenue Lost to Churn
- Average Monthly Charges & Tenure

### 📈 Visualizations
- **Churn by Contract Type**, Payment Method, Age Group
- **Churn Reason Breakdown** (e.g., competitors, service quality, pricing)
- **Revenue Analysis**: comparing churned vs. retained customers
- **Tenure Distribution** by churn category
- **Interactive Filters**: gender, state, internet type, streaming preferences

---

## 🧠 Key Insights

- Most churned customers are on **month-to-month contracts**.
- **Paperless billing** and **high monthly charges** show higher churn risk.
- **Streaming services** usage correlates with longer tenure and reduced churn.
- Customers with **no referrals** or **basic support plans** are more likely to leave.
- Churn is highest among those citing **pricing**, **poor support**, and **competitor offers** as reasons.

---

## Recommendations
* Convert Month-to-Month Contracts to Long-Term Plans
Customers on flexible plans are more likely to churn. Offering incentives (e.g., discounts) for switching to annual contracts can increase retention.
* Bundle Streaming and Value Services
Customers who subscribe to streaming and device protection plans show lower churn. Create bundled packages that offer more perceived value.
* Target At-Risk Segments
  1.  Customers with short tenure, no referrals, or no premium support are high-risk.
   2. Use churn scores to flag and engage these users early.
* Price Optimization
Many customers leave due to “high pricing” or “found better deal.” Use competitor benchmarking and personalized offers to retain price-sensitive users.
* Improve Support and Communication
Churn reasons like “poor customer service” and “lack of support” suggest service quality issues. Strengthen training and response times in customer support teams.
## 🛠 Tools & Tech Stack

- **Power BI Desktop**  
- **Power Query** for data cleaning  
- **DAX** for calculated columns and measures  
- **SQL** for preprocessing prior to import

---



