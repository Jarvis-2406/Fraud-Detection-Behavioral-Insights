# Fraud-Detection-Behavioral-Insights

# 💼 Fraud Detection & Behavioral Insights Dashboard – Power BI Project

## 📊 Project Overview

This project presents an **interactive Power BI dashboard** built to analyze **financial frauds** using a real-world transactional dataset. The dashboard not only detects fraudulent activity but also explores **behavioral patterns, fraud typologies, and risk profiling**—helping stakeholders make data-driven decisions for fraud prevention and monitoring.

---

## 🎯 Objective

- Analyze **fraudulent transactions** using descriptive and visual analytics.
- Detect **fraud trends, patterns**, and **risky accounts**.
- Empower users with **actionable KPIs** for fraud monitoring.
- Showcase my **fraud analysis and data storytelling** skills using Power BI.

---

## 🧠 Key Features

| Page | Description |
|------|-------------|
| **1. Executive Summary** | High-level KPIs: Total Fraud %, Total Transactions, Fraud Amount, External/Internal Split |
| **2. Fraud Trend Analysis** | Time-based insights into when fraud occurs the most |
| **3. Transaction Type Risk Profile** | Identify the riskiest transaction types by fraud count & percentage |
| **4. Fraudster Behavior** | Analyze origin and destination accounts involved in fraud |
| **5. Fraud Typology Analysis** | Breakdown of fraud types and their characteristics |
| **6. (Optional) Balance Behavior Analysis** | Scatter and box plots for suspicious balance changes |

---

## 📁 Dataset Info

- **Source**: Publicly available financial transaction data
- **File**: `cleaned_sample_fraud_data.csv`
- **Columns Used**:
  - `step`, `amount`, `type`, `isFraud`, `isFlaggedFraud`, `nameOrig`, `nameDest`, `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, `newbalanceDest`, `isExternal`, `fraudType`

---

## 📐 Power BI Features Used

- DAX Measures:
  - `Total Fraudulent Transactions`
  - `Fraud Rate (%)`
  - `Fraud Count by Type`
  - `Fraud Amount by Origin`
  - ...and more
- Visuals:
  - KPI Cards, Pie/Donut Charts, Bar Charts, Line Graphs, Matrix Tables, Scatter Plots
- Interactivity:
  - Slicers by `type`, `fraudType`, `isExternal`
  - Drill-down enabled for trend analysis

---

## 🛠 Tools & Technologies

- **Power BI Desktop**: Data modeling, dashboards, DAX
- **Python (Google Colab)**: Data cleaning and preprocessing
- **Git & GitHub**: Version control and project hosting

---

## 🧩 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/fraud-detection-powerbi.git
