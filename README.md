# HR-Attrition-Data-Analysis-Power-BI
A 2-page interactive Power BI dashboard analyzing employee attrition across 1,470 employees, identifying who leaves, why, and where HR should focus retention efforts first.

## Dataset

- Source: (https://www.kaggle.com/datasets/nezukokamaado/hr-metrics-and-analytics-repository)
- Size: 1,470 employees, single table
- Target variable: Attrition (Yes/No)
- Key fields used: Department, Job Role, Age, Marital Status, Over Time,
  Monthly Income, Years At Company, Distance From Home, Job Satisfaction,
  Stock Option Level 

## Business Objective

The primary objective of this project is to provide actionable insights for HR 
leaders to proactively manage employee attrition and retention.

Specifically, this dashboard aims to address the following areas:

- **Workforce Monitoring**
  - Tracking overall headcount, active employees, and attrition rate across the organization.
- **Risk Identification**
  - Spotting departments and job roles with disproportionately high attrition (e.g. Sales, Sales Representative).
- **Demographic Analysis**
  - Uncovering attrition patterns across age bands, marital status, and tenure.
- **Behavioral & Financial Drivers**
  - Analyzing how overtime, business travel frequency, income bands, distance from home, and stock options relate to attrition.
- **Segmentation**
  - Isolating high-risk combinations (e.g. Sales Representatives on overtime) to prioritize retention action.
- **Strategic Decisions**
  - Providing a data foundation for evidence-based HR retention discussions and policy decisions.
 

## Tools & Skills

- Power BI Desktop (data model, report design).
- DAX (measures, calculated columns) and Power Query.
- Data visualization and dashboard design.
- Business/HR analytics insights.


## Dashboard Pages

### Page 1 — HR Attrition Overview

The executive overview focuses on the overall scale and distribution of employee attrition.

Key analyses include:
- Attrition % by Age Band
- Attrition % by Marital Status
- Attrition % by Department
- Attrition % by Job Role
- Attrition % by Tenure Band
- Attrition % by Overtime
- Overall workforce KPIs
- Interactive filters for Department, Job Level, Gender, Business Travel, Overtime, Job Role, and Age Band

### Page 2 — Attrition Drivers & Workforce Segmentation

The second page provides a more detailed view of potential attrition drivers and workforce segments.

Key analyses include:
- Attrition % by Business Travel
- Attrition % by Income Band
- Attrition % by Distance Band
- Attrition % by Stock Option Level
- Overtime vs. Job Role
- Department and Job Role level attrition analysis
- Attrition vs. Years at Company and Monthly Income
- Supporting metrics such as average age, income, tenure, and job satisfaction

## Key Insights

### 1. Attrition is concentrated among younger employees
Employees under 25 have the highest attrition rate at 39.18%, considerably higher than the other age bands.

### 2. Single employees show higher attrition
The attrition rate for single employees is 25.53%, compared with 12.48% for married employees and 10.09% for divorced employees.

### 3. Sales has the highest department-level attrition
Among departments:
- Sales — 20.63%
- HR — 19.05%
- R&D — 13.84%

### 4. Sales Representatives are a major high-attrition segment
Sales Representatives show the highest job-role attrition rate at 39.76%.

### 5. Overtime is strongly associated with higher attrition
Employees working overtime have an attrition rate of 30.53%, compared with 10.44% for employees without overtime.

### 6. Frequent business travel is associated with higher attrition
Employees who travel frequently have an attrition rate of 24.91%, compared with 14.96% for travel-rarely employees and 8.00% for non-travel employees.

### 7. Lower-income employees show higher attrition
Income band up to 3K  has the highest attrition rate at 28.61%, while employees earning above 10K have an attrition rate of 8.90%.

### 8. Shorter-tenure employees show elevated attrition
Employees with 0–2 years of tenure have an attrition rate of 29.82%, making early-tenure retention an important area for HR attention.

### 9. Attrition rises again after long tenure, likely due to retirement
Attrition drops sharply with tenure — from 29.82% (0–2 years) to a low of 6.67%
(10–20 years) — but rises again to 12.12% for employees with 20+ years of
tenure. This late-career up-rise is more consistent with retirement than
disengagement.

##  Business Recommendations

Based on the observed patterns, HR teams could investigate:

1. Early-tenure retention programs for employees in their first 2 years, where attrition peaks at 29.82%.
2. Overtime and workload management, particularly in high-attrition roles — overtime attrition (30.53%) is nearly 3x non-overtime (10.44%).
3. Targeted retention strategies for high-risk job roles such as Sales Representatives (39.76%).
4. Travel-related workload and employee experience for frequently travelling employees (24.91% vs. 8.00% for non-travel).
5. Compensation and career-growth factors among lower-income employee groups, where attrition reaches 28.61% in under-3K band.
6. Focused engagement initiatives for younger (under-25, 39.18%) and single (25.53%) employee segments.


## Author

**Rildon Koren** — Data Analyst | Power BI  
🔗 [LinkedIn](https://www.linkedin.com/in/rildon-koren-b11911342/) | ✉️ rildonrk6@gmail.com
