# 📊 HR Analytics Dashboard | Power BI Project

An interactive Power BI dashboard designed to visualize and analyze key HR metrics such as attrition, promotion, job satisfaction, retrenchment, department-wise headcount, and employee demographics with full-page navigation across Home, Action, and Detail screens.

---

## 📚 Table of Contents
- [Project Title](#project-title)
- [Brief One-Line Summary](#brief-one-line-summary)
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Navigation](#navigation)
- [Dataset](#dataset)
- [Tools and Technologies](#tools-and-technologies)
- [Methods](#methods)
- [Key Insights](#key-insights)
- [Dashboard Output](#dashboard-output)
- [How to Run This Project](#how-to-run-this-project)
- [Results & Conclusion](#results--conclusion)

---

## Project Title
**HR Analytics Dashboard – Full Insights using Power BI**

---

## Brief One-Line Summary
A dynamic HR dashboard that enables data-driven decision-making by visualizing employee metrics like promotion, retrenchment, satisfaction, and performance.

---

## Overview
This Power BI dashboard aggregates and visualizes HR-related KPIs to help HR managers understand workforce dynamics and make strategic decisions. It includes gender ratios, promotion readiness, retrenchment alerts, job satisfaction distribution, service years, and more across departments and job roles.

---

## Problem Statement
Many HR departments struggle with identifying trends in workforce retention, job satisfaction, or promotion-readiness due to scattered data and static reporting tools. This dashboard centralizes and visualizes these KPIs for immediate insights, improved efficiency, and proactive decision-making.

---

## Navigation
The dashboard includes three navigable pages for a smooth user experience:
- **Home Page**: Summary stats for gender, promotions, retrenchment, and KPIs.
- **Action Page**: Drill-down by department, job role, and job satisfaction level.
- **Detail Page**: Deep insights on service years, retrenchment risk, office distance, job levels, and more.

Navigation buttons on the left allow seamless transitions between the pages.

---

## Dataset
- Source: Simulated HR dataset
- Format: Embedded in `.pbix`
- Key Fields:
  - Employee ID, Name
  - Gender
  - Job Role, Department
  - Years of Service, Distance from Office
  - Overtime Status
  - Promotion Due Flag
  - Retrenchment Status
  - Job Satisfaction Level
  - Performance Rating
  - Employment Status (Active, Retrenched)

---

## Tools and Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Microsoft Excel (for preprocessing)

---

## Methods
- Data cleansing and transformation in Power Query
- DAX Measures:
  - Promotion count
  - Retrenchment totals
  - Job satisfaction levels
  - Gender distribution
- Bookmark navigation between pages
- KPI cards, bar charts, pie charts, and lists
- User interaction enabled via slicers and buttons

---

## Key Insights
- **1470 total employees** — 60% male, 40% female
- **72 employees** due for promotion (5%)
- **117 employees** marked for retrenchment (8%)
- **Highest retrenchment** in the Manager role (44 employees)
- **R&D department** has the highest number of promotion-due and retrenched employees
- **63.95% of employees** live very close to office
- Employees with high satisfaction mostly remain active

---

## Dashboard Output

### 🏠 Home Page
- Total employees, gender breakdown
- Employees due for promotion
- Retrenchment summary
- KPI tiles with % ratios

![Home Snapshot](Snapshot%20of%20HR%20Analysis%20Dashboard%20(HOME).png)

---

### 🚀 Action Page
- Department-wise due for promotion vs retrenched
- Job satisfaction categories
- Overtime distribution
- Job Role analysis

![Action Snapshot](Snapshot%20of%20HR%20Analysis%20Dashboard%20(ACTION).png)

---

### 🔍 Detail Page
- Years of service by count
- Promotion & retrenchment overview
- Distance from office distribution
- Job levels analysis

![Detail Snapshot](Snapshot%20of%20HR%20Analysis%20Dashboard%20(DETAIL).png)

---

## How to Run This Project?

1. Download and open `HR ANALYSIS DASHBOARD With Navigation.pbix` in **Power BI Desktop**.
2. The dataset is already embedded. No need to import external files.
3. Use the left-side **navigation buttons** to explore:
   - Home
   - Action
   - Detail
4. Click on slicers or charts to dynamically filter the dashboard.
5. Review KPIs and visualizations to gain actionable HR insights.

---

## Results & Conclusion
This HR Dashboard centralizes workforce analytics into a single powerful tool. It:
- Provides a real-time view of HR KPIs
- Helps prioritize promotions and retrenchments
- Analyzes gender gaps and workforce composition
- Enables strategic workforce planning
- Is ideal for HR executives, analysts, and people managers
