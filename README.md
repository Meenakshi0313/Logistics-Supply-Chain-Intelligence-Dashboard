# 🚛 Fleet Performance & Supply Chain Intelligence Suite


## Executive Overview
This **End-to-End Business Intelligence Suite** transforms raw transactional logistics data into actionable executive insights. Developed for a multi-regional freight operation, the dashboard provides a high-fidelity "Control Center" experience to monitor financial health, asset utilization, and safety compliance.

---

### 🔗 Quick Access

* 📊 [**View Executive Performance Report (PDF)**](Report_and_Dashboard/Fleet_Performance_Supply_Chain_Intelligence_Report.pdf)
  
* 🛠️ [**Download Power BI Dashboard (.pbix)**](Report_and_Dashboard/Logistics_Intelligence_Command_Center_v1.pbix)
  
* 💾 [**View SQL Gold-Layer Transformation Scripts**](SQL_Scripts/Gold/Gold_Layer_Views.sql)

---

## 🛠️ Technical Architecture

#### **Backend Architecture & Data Transformation**

* **SQL Gold Layer:** Engineered a series of T-SQL views to denormalize a complex Snowflake schema into a high-performance reporting model, optimizing refresh efficiency.
* **Data Integration:** Developed logic to merge disparate maintenance logs with trip-level financials to create a unified "Single Source of Truth."
* **Star Schema Design:** Implemented a robust 1:Many relationship model (Fact-Dimension) to ensure data integrity and rapid filtering.

  ---

#### **Analytical Modeling & Business Logic**

* **KPI Intelligence:** Built a custom library of calculated measures to track multi-dimensional metrics across financial and operational domains.
* **Trend & Variance Analysis:** Implemented time-intelligence logic to facilitate Year-over-Year (YoY) performance comparisons and anomaly detection.
* **Exception Reporting:** Utilized advanced filtering and diverging visualization logic to identify cost leakage, loss-making lanes, and high-risk facilities.

---

## 📊 Dashboard Gallery

*Click on any image to view it in high resolution.*

### **01. Landing & Navigation Hub**
[<img src="01_Home_Page.jpg" width="1000" alt="Home Page">](01_Home_Page.png)
> **Insight:** Features an intuitive navigation system with custom "Selected" states to guide users through four distinct operational domains.

### **02. Executive Financial Overview**
[<img src="02_Executive_Financial_Overview.png" width="1000" alt="Financial Overview">](02_Executive_Financial_Overview.png)
> **Insight:** Strategic view of margin protection. Includes a **Customer Profitability Scatter Plot** and "Accessorial Impact" tracking to monitor hidden costs.

### **03. Operational Efficiency & Assets**
[<img src="03_Operational_Efficiency_and_Assets.png" width="1000" alt="Asset Analysis">](03_Operational_Efficiency_and_Assets.png)
> **Insight:** Technical fleet management focusing on **MPG vs. Utilization correlation** and manufacturer-specific maintenance trends.

### **04. Driver Performance & Safety**
[<img src="04_Driver_Performance_and_Safety.png" width="1000" alt="Safety Analysis">](04_Driver_Performance_and_Safety.png)
> **Insight:** Human-centric analytics focusing on safety compliance and revenue efficiency. Features a **Year-over-Year Safety Incident Distribution** chart.

### **05. Logistic & Facility Analysis**
[<img src="05_Logistic_and_Facility_Analysis.png" width="1000" alt="Facility Analysis">](05_Logistic_and_Facility_Analysis.png)
> **Insight:** Tactical view of hub throughput. Utilizes a **Diverging Bar Chart** to identify "High-Yield vs. High-Loss Lanes" and identifies facilities with high detention risk.

---

## 🏗️ Data Model (Star Schema)
[<img src="Logistics_Star_Schema_Data_Model.png" width="1000" alt="Data Model">](Logistics_Star_Schema_Data_Model.png)
*Architecture showing the relationship between Fact tables (Loads, Safety, Metrics) and Dimension tables (Drivers, Trucks, Routes).*

---

## 🎨 UI/UX Design Principles
* **High-Contrast Dark Theme:** Developed for low-glare environments (Logistics Command Centers).
* **Actionable Color Palette:** Standardized color coding (Red/Green) strictly reserved for performance variances.
* **Dynamic Slicer Panel:** Global filtering synchronized across all report pages for a seamless analytical experience.

---

## 🚀 Deployment
1. Download the `.pbix` file included in this repository.
2. Open in Power BI Desktop.
3. Use the **Global Slicer Panel** to filter by Year (2023) and Month.

---

**Author:** Meenakshi Singh  
**Role:** Aspiring Data Analyst | SQL & Power BI Specialist  



