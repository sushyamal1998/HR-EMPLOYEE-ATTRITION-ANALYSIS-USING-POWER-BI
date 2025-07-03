# HR-EMPLOYEE-ATTRITION-ANALYSIS-USING-POWER-BI
In this project i have to analyzes the fact why employees leaving  company.

## Overview
This project analyzes an HR dataset focused on employee attrition, sourced from kaggle.<br>
It aims to explore key questions such as:
- What's the main factor for employee attrition?
- How does attrition vary by department, job role, or overtime?
- What insights can we extract to improve retention?


## Dataset
- **File Name:** WA_Fn-UseC_-HR-Employee-Attrition.csv
- **Rows:** 1470
- **Columns:** This dataset contains column like Age, Business Travel, Department, Job role, Attribution etc.

## Analysis Performed

**Data Cleaning & Preparation**
- Converted categorical data to appropriate types
- Checked for missing values and inconsistencies
- Create calculate Columns


**Exploratory Data Analysis (EDA)**
- Count the total employee, attrition count,Attrition rate.
- Attrition count by Gender, education background, job role.
- Attrition count by Monthly Income Rate.
- Impact of overtime on attrition.


**Power BI Dashboard**
- Built dashboards using DAX measures such as:
   - `Attrition Rate by Department`
   - `Avg Monthly Income by Job Role`
- Used slicers to filter by Department, Gender.

## Key insights
- Attrition rate 16.1% and most of employee are Male.
- Life Science has most attribution rate 38%, then Medical 27%.
- Most of employee whose monthly salary between 1 to 5000, they left company.
- Overtime strongly correlates with higher attrition


## Tools Used
- Power BI (for interactive dashboard and DAX measure)
- DAx (to build average age, Attrition count etc)


## Conclusion
Based on analysis of the HR Employee Attrition dataset, we can conclude:
- Overtime is strongly linked to Attrition
- Attrition is concentrated in certain departments and roles.
- Monthly Income is strongly related to Attrition.


