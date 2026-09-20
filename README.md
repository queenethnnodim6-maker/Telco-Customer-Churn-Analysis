# 📊 Telco Customer Churn Analysis — Power BI

An interactive Power BI dashboard analyzing customer churn, identifying key churn drivers, and quantifying the financial impact of lost customers.

---

## 📌 Project Overview

Customer churn is one of the most costly challenges in the telecommunications industry. Losing customers affects recurring revenue and increases the pressure to continuously acquire new ones.

This project uses **Power BI** to analyze approximately **7,043 telecom customer records** and answer a critical business question:

Which customers are most likely to churn, why are they leaving, and how much revenue is at stake?

The dashboard provides stakeholders with an interactive view of churn patterns across **contracts, tenure, services, billing methods, demographics, and customer value**.

The goal is to help businesses identify high-risk customer segments and support more targeted retention strategies.

---

## 🎯 Business Objectives

The analysis was designed to:

- Identify the major factors associated with customer churn.
- Determine which customer segments have the highest churn rates.
- Analyze churn across contract and payment types.
- Understand how customer tenure relates to churn.
- Examine the relationship between additional services and customer retention.
- Quantify the financial impact of churn.
- Provide an interactive dashboard for business decision-making.

---

## 📂 Dataset

**Source:** [Telco Customer Churn Dataset — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset contains approximately **7,043 customer records** covering:

- Customer demographics
- Account information
- Contract details
- Internet and additional services
- Payment methods
- Monthly charges
- Total charges
- Customer tenure
- Churn status

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development and data visualization |
| **Power Query (M)** | Data cleaning and transformation |
| **DAX** | KPI measures and calculated columns |
| **GitHub** | Project documentation and portfolio hosting |

---

## 🧹 Data Preparation

Before building the dashboard, the dataset was prepared using **Power Query**.

Key data-cleaning steps included:

- Handling missing and null values
- Replacing inconsistent values
- Correcting data types
- Standardizing categorical fields
- Preparing numerical fields for analysis
- Creating analysis-ready columns

This ensured the data was consistent and suitable for visualization and DAX calculations.

---

# 📈 Key Performance Indicators

The dashboard tracks several KPIs to provide a high-level view of customer churn and its financial impact.

| KPI | Description |
|---|---|
| **Churn Rate** | Percentage of customers who have churned |
| **Total Customers** | Total number of customers in the dataset |
| **Avg Monthly Charges** | Average monthly recurring charge per customer |
| **Avg Tenure** | Average length of the customer relationship in months |
| **Churned Revenue** | Monthly recurring revenue associated with churned customers |
| **Total Charges Lost** | Historical lifetime billing associated with churned customers |

---

# 📊 Dashboard Pages

The Power BI report contains multiple interactive pages designed to analyze churn from different business perspectives.

### 1. 📌 Churn Overview

Provides a high-level snapshot of:

- Total customers
- Churn rate
- Average monthly charges
- Average tenure
- Churned revenue
- Overall churn distribution

---

### 2. 💳 Contract & Billing

Examines how contractual and payment characteristics relate to churn.

Analysis includes:

- Contract type
- Payment method
- Billing preferences
- Monthly charges
- Churn distribution

---

### 3. ⏳ Tenure & Loyalty

Analyzes customer churn across different stages of the customer lifecycle.

The analysis focuses on:

- Early-tenure customers
- Mid-tenure customers
- Long-term customers
- Churn patterns across tenure buckets

---

### 4. 🔌 Services & Add-ons

Explores whether additional services are associated with customer retention.

Services analyzed include:

- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

---

### 5. 💰 Financial Impact

Quantifies the financial consequences of customer churn.

This page focuses on:

- Churned monthly revenue
- Total charges associated with churned customers
- Revenue exposure
- Customer value

---

### 6. 👥 Demographics

Examines churn patterns across customer characteristics such as:

- Senior citizen status
- Partner status
- Dependents
- Customer segments

---

### 7. 🌳 Root Cause Analysis — Decomposition Tree

The **Decomposition Tree** allows users to drill down into churn and explore how different customer attributes contribute to high-risk segments.

Users can interactively investigate dimensions such as:

**Contract → Internet Service → Payment Method → Tenure → Services**

This makes it easier to move from a high-level churn figure to specific customer segments.

---

# 🔍 Key Insights

The analysis revealed several notable churn patterns.

### 1. Add-on Services & Customer Retention

Customers with **no additional services** show noticeably higher churn compared with customers subscribed to multiple add-on services.

This suggests that broader service adoption may be associated with stronger customer retention.

---

### 2. Contract Type

**Month-to-month customers** show substantially higher churn compared with customers on one-year and two-year contracts.

This highlights contract structure as an important dimension when analyzing customer retention.

---

### 3. Internet Service

Customers using **fiber optic internet** show elevated churn compared with some other internet-service segments.

Further investigation would be required to determine the underlying business reasons for this pattern.

---

### 4. Payment Method

Customers paying through **electronic check** also show elevated churn.

This makes payment method a useful segment for further retention analysis.

---

### 5. Early-Tenure Churn

A meaningful proportion of churn occurs during the **early stages of the customer lifecycle**.

This suggests that onboarding, early engagement, and first-month customer experience are important areas to investigate when developing retention initiatives.

---

# 💡 Business Implications

The findings point to several areas that a telecom business could investigate further:

- Strengthen onboarding for new customers.
- Monitor month-to-month customers more closely.
- Investigate customer experience among fiber-optic users.
- Examine why electronic-check customers have higher churn.
- Encourage relevant add-on service adoption.
- Develop targeted retention campaigns based on customer risk segments.
- Monitor high-value customers who show early signs of churn.

**Note:** The dashboard identifies relationships and patterns in the dataset. These findings should not automatically be interpreted as proof that a particular factor causes churn.

---
# Skills Demonstrated

This project demonstrates practical experience in:

Data Cleaning
Data Transformation
Exploratory Data Analysis
Power Query
DAX
KPI Development
Data Visualization
Dashboard Design
Customer Churn Analysis
Financial Impact Analysis
Business Intelligence
Data Storytelling
Business Insight Communication

# What This Project Demonstrates
Raw Data
    ↓
Data Cleaning
    ↓
Data Transformation
    ↓
Data Modeling
    ↓
DAX Measures
    ↓
Exploratory Analysis
    ↓
Dashboard Development
    ↓
Business Insights
    ↓
Decision Support
