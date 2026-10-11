# 📊 Telco Customer Churn Analysis Dashboard

<img width="1700" height="934" alt="Telco Customer Churn Power BI Dashboard" src="https://github.com/user-attachments/assets/721b72c2-d50b-435e-abc0-4f9a3e493aab" />

[![Power BI](https://img.shields.io/badge/Power_BI-Interactive_Dashboard-F2C811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Data-Power_Query_%26_DAX-217346?style=flat&logo=microsoftexcel&logoColor=white)](https://office.com)
[![Dataset](https://img.shields.io/badge/Source-IBM_Telco_Churn-006699?style=flat)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

**Course:** DSC651 — Data Representation and Reporting Techniques  
**Faculty / Group:** CDCS2416A | Universiti Teknologi MARA (UiTM)  
**Supervisor:** Dr. Amri Bin Ab. Rahman  

---

## 📌 Executive Summary & Analytical Findings

Analysis of **7,043 telecommunications customer records** to identify the primary drivers of subscriber attrition and quantify contractual churn risks:

* **Overall Attrition:** 1,869 customers churned, representing a baseline **26.54% churn rate** (5,174 retained).
* **Contractual Risk Concentration:** **88.55% of all churned accounts** were on month-to-month contracts, indicating extreme vulnerability during early subscription windows compared to 1-year or 2-year commitments.
* **Tenure Vulnerability:** 1,037 customers churned within their **first 12 months** of service, establishing early onboarding as the most critical customer retention window.
* **Service Correlates:** Fiber optic subscribers experienced higher attrition than DSL customers, driven by billing dispute sensitivity and electronic check payment preferences.

---

## 👥 Project Team
* Muhammad Luqman Hakim Bin Syahrulnizam
* Nurul Amira Ainna Binti Abdullah
* Adriana Maisarah Binti Mohd Zamri
* Muhammad Luqman Haqimi Bin Shahmizan

---

## 📈 Dashboard Architecture & Visuals

The interactive Power BI dashboard delivers multi-dimensional diagnostic reporting across customer touchpoints:

1. **Executive KPI Header:** Real-time dynamic cards tracking Total Customers (7,043), Churn Rate (26.54%), Retained Count, and Churned Count.
2. **Contract Type Slicers:** Cross-filtering churn patterns across Month-to-Month, One Year, and Two Year agreements.
3. **Tenure Cohort Breakdown:** Visualizes attrition across tenure bands (0–12 months, 13–24 months, 25+ months).
4. **Billing & Service Diagnostics:** Visual breakdown comparing Internet Service (Fiber optic vs. DSL vs. No internet) and payment method exposure.

---

## 📁 Repository Structure

| File / Folder | Purpose |
|---|---|
| `ProjectPowerBI_DSC651_Telco.pbix` | Master Power BI Desktop dashboard with data model & DAX calculations |
| `Cleaneddataset_with dax_and_all.xlsx` | Transformed IBM Telco dataset with feature engineering |
| `data/TelcoChurn_PowerBI_Ready.xlsx` | Final structured reporting dataset consumed by Power BI |
| `data/raw/` | Original IBM Telco customer churn CSV data files |
| `docs/` | Formal academic proposals and group research report |
| `versions/` | Version-controlled snapshots tracking report iterations |

---

## 🛠️ Tools & Technologies
* **BI Platform:** Microsoft Power BI Desktop
* **ETL & Data Wrangling:** Power Query M Language
* **Calculations:** DAX (Data Analysis Expressions) for dynamic churn rates and percentage shares
* **Dataset:** IBM Cognos Telco Customer Churn
