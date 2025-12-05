# HR Analytics: Workforce, Atttrition & Promotion Insights

A Power BI dashboard analyzing IBM HR data. It includes insights into employee attrition, workforce distribution, high-risk employees, and key HR metrics. This project demonstrates **data transformation using Power Query** and **calculated measures using DAX**.


# Project Objective
The objective of this project is to analyze IBM’s HR dataset and generate meaningful insights that can help HR leadership make data-driven decisions.
This analysis focuses on understanding:

- Total workforce composition
- Attrition patterns and retention risks
- Employee promotion readiness (Years in Role, Job Level, Performance Rating)
- Employee satisfaction levels
- Work-life balance and overtime patterns
- Distance-from-home impact
- Department and job role distributions
- Identification of high-risk employees (low satisfaction, overtime, etc.)

---

# Tools Used
 **Power BI** – Dashboard creation & data visualization
 
**Power Query** – Data cleaning & transformation

**DAX** – Calculations for KPIs and performance metrics

**Microsoft Excel** – Initial data review

---

# Dashboard Overview

The Power BI dashboard contains the following key sections:

1. Key Performance Indicators (KPIs)

 |KPI	     |Result
 
 Total Employees	| 1,470
 Average Satisfaction Score |	2.73
 Total Attrition|	237 employees
Attrition Rate |	16%
Average Performance |	3.15
Due for Promotion |	134 employees
Not Due for Promotion	| 1,336 employees

2. Department-Level Insights

- Attrition is highest in Sales and Research & Development.
- Human Resources has the lowest attrition but also the smallest workforce.
- Most employees are in Job Level 1 & 2, showing a lower-entry workforce structure.

3️. Promotion Readiness

- Using Years in Role + Performance Rating:
- 134 employees are due for promotion.
- Research & Development has the highest number of promotion-ready employees.

4. High-Risk Employees

- An employee is marked High Risk if they have:
- Low job satisfaction
- Overtime
- High workload indicators

**Result**:

- Research & Development has the highest number of high-risk employees (104).

5. Employee Satisfaction

- Satisfaction levels are moderate overall (avg: 2.7–2.8).
- Sales has the highest satisfaction score (avg 2.7).
- Human Resources shows the lowest average satisfaction, suggesting work-pressure issues.

6️. Overtime & Workload Patterns
- Research & Development department has the highest number of employees working overtime.
- Sales also shows high overtime, contributing to attrition levels.

7️. Distance-from-Home Impact

- Most employees live very close or close, showing that distance does not significantly affect attrition for majority.
- However, a noticeable portion of “far distance” employees score lower in satisfaction and performance.

8️. Performance Rating Insights

- Sales Executive and Research Scientist employees have the highest average performance ratings.

---
 
 # Key Insights
1. Workforce Composition

- The company has a total of 1,470 employees, with the highest concentration in Research & Development and Sales. The workforce is mainly at Job Levels 1 & 2, showing early-career dominance.

2. Attrition & Retention Risks

- Attrition rate is 16% (237 employees).
- Sales and Research & Development are the leading contributors to employee exits.
- Retention is strongest in Human Resources.

3. Promotion Eligibility

- 134 employees qualify as due for promotion based on years in role & performance.
- Most promotion-ready staff come from Research & Development.
- Very few employees in HR qualify for promotion due to low entry numbers.

4. Employee Satisfaction

- Overall satisfaction is moderately low (2.73/5).

5. High-Risk Employees

- A large number of employees in Rsearch & Development and Sales show high-risk indicators (low satisfaction and overtime).
- These departments need urgent intervention to avoid future turnover.

6. Overtime & Workload

- Research & Development and Sales have the highest overtime load.
- Overtime is strongly linked to lower satisfaction and high attrition.

---

# Recommendations
1️. Improve Employee Satisfaction

- Address workload pressure, provide better support systems, improve working conditions, and introduce incentives.

2️. Review Promotion Policies

- Promote the 134 employees already due.
- Re-evaluate promotion criteria to ensure fairness and career progression.

3️. Reduce Overtime in High-Pressure Departments

- Research & Development and Sales require workload balancing.
- Introduce shift-based work or redistribute tasks.

4️. Strengthen Retention Strategies

- Target Sales and Research & Development with engagement programs.
- Provide mentorship, mental health support, and job redesign options.

5️. Train Managers in High-Risk Departments

- Areas with low satisfaction and high attrition may benefit from leadership training and better communication channels.

6️. Monitor Distance-from-Home Effects

- Provide transportation support for employees living far away, especially those showing performance decline.

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

