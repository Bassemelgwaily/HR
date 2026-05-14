# HR & Training Analytics Dashboard (Excel - Power Pivot)

## 📋 Project Overview
This project features a comprehensive HR Analytics system built entirely in **Microsoft Excel**. It provides data-driven insights into workforce dynamics, employee performance, and training ROI. By leveraging Excel's advanced analytical capabilities, this dashboard helps HR leaders monitor retention, optimize training investments, and analyze recruitment trends.

The analysis is structured into two main views:
1.  **General HR Analysis:** Tracking headcount, attrition rates, and workforce demographics.
2.  **Training Analysis:** Evaluating training costs, pass rates, and the effectiveness of professional development programs.

## 📊 Key Features & Insights

### 1. General HR Dashboard
* **Workforce Metrics:** Monitoring Total Headcount and Gender Distribution (56% Female / 44% Male).
* **Attrition Tracking:** Analyzing the 12.9% Attrition Rate across departments, identifying high-turnover areas like Software Engineering.
* **Performance Overview:** Visualizing average employee ratings across business units.
* **Recruitment Funnel:** Tracking total applicants (3,000) and hiring efficiency.

### 2. Training Analysis Dashboard
* **Budget Management:** Tracking a total training investment of $1,675,886.
* **Success Rates:** Analyzing the 50% Pass Rate and identifying training gaps by program and department.
* **Trend Analysis:** Monitoring training performance and costs over time (2022–2024).

## 🛠️ Tech Stack & Tools
* **Microsoft Excel:** The primary platform for the dashboard and analysis.
* **Power Query:** Used for ETL (Extract, Transform, Load) to clean and prepare HR data.
* **Power Pivot (Data Modeling):** Implemented a **Star Schema** to handle multiple tables and complex relationships.
* **DAX (Data Analysis Expressions):** Utilized to create advanced Pivot Table measures like Attrition Rate, Average Ratings, and Training ROI.
* **Dynamic Slicers:** Enabled interactive filtering by Year and Department for a customized user experience.

## 📂 Data Model Structure
The project follows professional BI standards using a relational model:
* **Fact Tables:** `training_and_development`, `employee_engagement_survey`, `recruitment_data`.
* **Dimension Tables:** `employee_data` (Central Dim), `Date` (Calendar Table).

## 🚀 How to View
1.  Download the `.xlsx` file from this repository.
2.  Open it in **Excel** (Ensure Power Pivot is enabled).
3.  Interact with the **Slicers** to explore different views and time periods.

---
**Developed by:** Bassem Mohamed
*Junior Data Analyst | HR Analytics Specialist*
