# IBM HR Dashboard

A Power BI dashboard analyzing IBM HR data. It includes insights into employee attrition, workforce distribution, high-risk employees, and key HR metrics. This project demonstrates **data transformation using Power Query** and **calculated measures using DAX**.

---

## Key Features
- Employee attrition by department
- High-risk employee identification
- Average tenure and promotion analysis
- Interactive visuals for HR insights
- Workforce composition overview

---
## Power Query Transformations

The following data transformations were applied using **Power Query**:

- Renamed and cleaned columns for clarity
- Removed duplicates and irrelevant rows
- Created **Conditional Columns** for business logic, such as:
  - if [JobSatisfaction] <= 2 and [OverTime] = "Yes" then "High Risk" else "Normal"
  - if [YearsInRole] >= 3 and [PerformanceRating] >= 4 then "Due for Promotion" else "Not Due"
- Changed data types for proper calculations
- Filtered out incomplete or invalid records
---

## Key DAX Measures

| Measure / Column Name | DAX Formula | Purpose / Insight |
|----------------------|------------|-----------------|
| Total Employees | = COUNTROWS('IBM HR Employee Attrition Data')| Counts all employees in the dataset |
| AttritionFlag | = IF('IBM HR Employee Attrition Data'[Attrition] = "Yes", 1, 0) | Converts Yes/No attrition to numeric for easier calculations
| Total attrition | = calculate(countrows('IBM HR Employee Attrition Data'), 'IBM HR Employee Attrition Data'[Attrition] = "Yes") | Total number of employee who left
| AvgPerformance | = AVERAGE('IBM HR Attrition Data'[PerformanceRating]) | Tracks overall employee performance trends.
|Due for promotion | = CALCULATE([Total employee], 'IBM HR Employee Attrition Data'[promotion status] = "Due for promotion") | Total Number of employee who are due for promotion

---

## How to Open
1. Download the `IBM_HR_Dashboard.pbix` file from this repository.
2. Open it in **Power BI Desktop**. (Recommended)
3. Interact with the visuals and explore the DAX measures in the fields pane.

---

## Additional Notes
- All data cleaning and transformations were performed using **Power Query**.
- All calculations and key metrics were created using **DAX formulas**.
- This dashboard is suitable for demonstrating HR analytics skills in **Power BI portfolios**.
  
---

- ## Screenshots

**Dashboard Overview**  
![Dashboard Screenshot](<img width="829" height="463" alt="IBM HR DASHBOARD 1" src="https://github.com/user-attachments/assets/fc667ca2-034b-4f0e-b81f-0200711f7c3b" />)

![Dashboard Screenshot](<img width="824" height="464" alt="IBM HR DASHBOARD 2" src="https://github.com/user-attachments/assets/f7a6a855-cf3c-41b2-b3b9-e988a8d95e06" />)

