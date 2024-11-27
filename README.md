# Employee Performance Analysis - Tableau Dashboard

### Overview

This project focuses on visualizing employee performance data to evaluate productivity, identify high achievers, and improve team management. Using employee performance data, the project provides insights into:

- Performance Distribution: Analyze how employees are performing across departments and roles.
- Project Completion Rates Over Time: Track average project completion trends over time.
- Team Performance Comparison: Compare department-level performance metrics and satisfaction scores.

The processed data is visualized using Tableau, enabling dynamic exploration of employee KPIs, project completion rates, and satisfaction levels.

### Key Features

##### 1. Data Cleaning and Preprocessing

- Converted Dates: Transformed Hire_Date into a datetime format to enable time-based analysis.
- Handled Missing Values: Verified no critical missing data; filled other missing values where necessary.
- Removed Duplicates: Checked for and removed any duplicate entries in the dataset.
- Feature Engineering:
- Calculated Productivity Score: Ratio of Projects_Handled to Work_Hours_Per_Week.
- Derived Overtime Percentage: Percentage of overtime hours worked.
- Created Long-Tenure Flag: Identified employees with over 5 years at the company.
- Computed Average Department Satisfaction: Aggregated satisfaction scores by department.

##### 2. Data Output for Visualization

Employee Performance Distribution:
- Key Fields: Employee_ID, Department, Job_Title, Performance_Score, Monthly_Salary.
- Use Case: Visualize performance distribution across departments and job roles.

Project Completion Rates Over Time:
- Key Fields: Hire_Date, Projects_Handled.
- Use Case: Display trends in project completion rates over time.

Team Performance Comparison:
- Key Fields: Department, Performance_Score, Employee_Satisfaction_Score.
- Use Case: Compare department-level average performance and satisfaction scores.

### Future Enhancements

- Incorporate additional metrics such as training hours or employee churn rates.
- Perform predictive analysis to forecast future performance trends.
- Add clustering to identify employee segments based on performance, satisfaction, and productivity.
