# Employee Data Report – Power BI

## Overview
A two-page interactive Power BI report built on employee data, providing insights into attendance, demographics, and salary.

---

## Files
| File | Description |
|---|---|
| `Report.pbix` | Power BI report file |
| `Employee_Data.xlsx` | Source data file |

---

## Pages

### Page 1 – Employee Data Report
**KPI Cards**
- Total Enrolled
- Present
- Absent
- Average Attendance

**Charts & Visuals**
- **Team Wise** – Clustered bar chart showing Present vs Absent count across Team 1 to Team 5
- **Manager Wise** – Clustered bar chart showing Present vs Absent count per Senior Manager (Dan, Lewis, Sam, Kent, Wade)
- **Gender Wise** – Donut chart showing Female vs Male distribution
- **Job Level Wise** – Matrix showing employee count by Job Level

**Slicers**
- Training Model
- Senior Manager
- Team
- Job Level
- Reset Slicers button

---

### Page 2 – Salary Analysis
**KPI Cards**
- Total Salary
- Min Salary
- Max Salary
- Avg Salary
- Count of Record

**Charts & Visuals**
- **Top 5 Employees by Salary** – Bar chart displaying the top 5 highest-paid employees with salary labels

**Slicers**
- Training Model
- Senior Manager
- Team
- Job Level
- Reset Slicers button

---

## How to Use
1. Open `Report.pbix` in Power BI Desktop.
2. Ensure `Employee_Data.xlsx` is accessible at the original data source path, or update the data source path via **Transform Data → Data Source Settings**.
3. Use the slicers on each page to filter the visuals.
4. Click **Reset Slicers** to clear all applied filters.
