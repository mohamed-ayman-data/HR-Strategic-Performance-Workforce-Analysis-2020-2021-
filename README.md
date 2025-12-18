# 📊 HR Strategic Performance & Workforce Analysis (2020-2021)

## Executive Summary
A dynamic Excel dashboard built to diagnose a **critical 11% drop in employee performance** across key Egyptian branches (Cairo, Alexandria, Tanta). This analysis empowered HR leadership with actionable insights into salary disparities, experience gaps, and department-level trends, culminating in a tool for proactive talent management.

---

## 🎯 Project Objectives
- **Diagnose Performance Decline:** Identify root causes of the 11% overall performance decrease between 2020 and 2021.
- **Analyze Geographic & Departmental Variances:** Compare metrics across three cities and all functional departments.
- **Audit Compensation Equity:** Uncover and visualize salary gaps for similar roles and experience levels.
- **Build an HR Toolkit:** Create an interactive, user-friendly dashboard with employee search functionality for daily HR operations.

---

## 🛠️ Tools & Technologies
- **Microsoft Excel (Advanced):** PivotTables, PivotCharts, Slicers, Timeline
- **Data Modeling:** Custom columns, XLOOKUP/VLOOKUP
- **Dashboarding:** Form Controls (Buttons), Cell Linking, Bookmark Navigation
- **Data Analysis:** Conditional Formatting, Advanced Formulas

---

## 📁 Data & Process
The analysis followed a structured ETL and storytelling process:

### 1. **Data Preparation & Cleaning**
- Removed duplicate entries and empty columns to ensure data integrity.
- Created key calculated columns:
  - `Years of Experience`: (Based on joining date).
  - `Age`: Calculated from birth date.
  - `Performance Delta`: **2021 Performance - 2020 Performance** (revealing the -11% trend).

### 2. **Core Analysis & Modeling**
- Built a suite of **PivotTables** as the analytical engine, segmented into two streams:
  - **Location Analysis:** Comparing Cairo, Alexandria, and Tanta.
  - **Department Analysis:** Drilling into trends across Finance, Sales, IT, HR, etc.
- Established data relationships to ensure single-source truth for dashboards.

### 3. **Interactive Dashboard Development**
- **Page 1: Navigation & High-Level KPIs**
  - Central hub with `Employee Count`, `Average Age`, and `Highest Performance` metrics.
  - Navigation buttons (using **Form Controls & Bookmarks**) to seamlessly switch between views.
  
- **Page 2: Location Overview**
  - **Key Visuals:** 
    - `% Salary by Location` (Donut Chart)
    - `Salary by Location` (Bar Chart showing Min, Avg, Max)
    - `Avg. Age & Experience by Location` (Combo Chart)
    - `Performance per Location` (Metric Card)
  - **Primary Insight:** Identified significant salary compression and a mismatch between experience and compensation in specific cities.

- **Page 3: Department Overview**
  - **Key Visuals:** 
    - `Number of Employees by Department` (Treemap/Bar Chart)
    - `Performance by Department` (Line Chart)
  - **Primary Insight:** Pinpointed departments with the steepest performance declines and those resisting the trend.

- **Page 4: Employee Search Tool**
  - Built a **searchable index** using `VLOOKUP`/`XLOOKUP`.
  - HR staff can search by **Employee Name or ID** to instantly pull up a profile card with all relevant details (Experience, Age, Performance Trend, Location, Degree).
 
---

## 🔍 Key Insights & Business Impact

| Insight | Implication | Potential Action |
| :--- | :--- | :--- |
| **Overall performance dropped by 11%.** | Organization-wide productivity and engagement concern. | Launch focused employee sentiment surveys in Q1. |
| **Significant salary gaps exist for the same role in different locations.** | Risk of internal inequity and attrition in high-cost areas. | Conduct a compensation benchmark review by city and role. |
| **A weak correlation between experience and performance in certain departments.** | Experienced hires are not translating tenure into results in some teams. | Review onboarding and role alignment for tenured staff in underperforming units. |
| **Specific departments (e.g., Sales) showed resilience against the performance decline.** | These departments may have effective management or practices. | Document and share best practices from leading departments across the organization. |
| **High concentration of employees in specific locations/departments.** | Operational risk and succession planning vulnerability. | Develop a strategic workforce redistribution and cross-training plan. |

---

## 📂 Repository Structure
```text
HR Performance Analysis - Excel/
│
├── HR_Strategic_Analysis.xlsx       # The core interactive Excel file
└── Dashboards/                      # High-resolution captures of the analysis
    ├── Location_Overview.png        # regional KPI analysis
    ├── Department_Overview.png      # Salary and headcount by job title
    ├── Employee_Search_Page.png     # The VLOOKUP search interface
    └── Navigation_Home.png          # The main entry point of the tool

```
## 🚀 How to Use the Dashboard
1. **Open** `HR_Performance_Dashboard.xlsx`.
2. Start on the **`Performance Analysis`** sheet (Navigation Hub).
3. Use the **buttons** (`Employee Information`, `Location Overview`, `Department Overview`) to navigate.
4. In the **`Employee Information`** sheet, type an Employee Name or ID into the search cell to retrieve their full profile.
5. Use **Slicers** and **Filters** on the Location/Department sheets for ad-hoc analysis.

---

## 📬 Let's Connect
This project demonstrates my ability to transform raw HR data into a **strategic asset for decision-making**. I am passionate about using data to solve complex people and business problems.

**Interested in leveraging data to drive your organization's talent strategy?** 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mohamed-ayman-data/)
[![Email](https://img.shields.io/badge/Email-Profile-red?style=for-the-badge&logo=gmail)](mohmedaymn2025@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)](https://github.com/mohamed-ayman-data)


*Open to roles in: **People Analytics | HR Business Intelligence | Data Analysis***
