# HR-Analytics-dashboard
 This dashboard provides a overview of human resources data, focusing on key metrics related to employee attrition, including attrition rate, age, salary, and job role.
# Objective
The primary objective of this dashboard is to provide a clear and concise overview of key Human Resources metrics, with a specific focus on analyzing and understanding employee attrition. It aims to help HR managers and stakeholders quickly identify trends, patterns, and potential risk factors associated with employee turnover across different demographics and job roles.

# Dataset used
<a href="https://github.com/visakhjp/HR-Analytics-dashboard/blob/main/HR_Analytics.csv">Dataset</a>

# KPIs Mentioned
-Overall Employees
-Attrition
-Attrition Rate
-Average Age
-Avg Salary
-Years at Company

# Process
## Get the Data 
Collect employee data (age, salary, department, job role, education, years in company, attrition)

## Clean the Data:
Remove mistakes/empty values.

## Make groups : 
Age groups, Salary ranges, etc.

## Create Calculations (DAX):
Total Employees.
Attrition Count.
Attrition Rate = Attrition ÷ Total Employees.
Average Age, Salary, Years at Company.

## Build Visuals:
Cards : Overall employees, Attrition, Rate, Avg Age, Avg Salary, Years.
Charts : Attrition by Age, Education, Salary, Years, Job Role.
Donut/Bar/Line charts depending on what looks clear.

## Format & Design:
Use a clean color theme.
Add filters/slicers (e.g., Department, Gender).
Arrange visuals neatly for easy reading.

## Check & Share:
Verify numbers.
Publish to Power BI Service.
Share with HR team.

# Dashboard Interaction 
<a href="https://github.com/visakhjp/HR-Analytics-dashboard/blob/main/attrition.pbix">Dashboard</a>

# Dashboard Image
![Attrition dashboard](https://github.com/user-attachments/assets/c1554b29-3c5e-4797-b0ef-0e6f89773bb4)

# Project Insights

Overall Employees: 1470, with 237 attritions and 16.1% attrition rate.
Age Factor: Highest attrition is in the 26–35 age group (young workforce leaving more).
Education: Employees from Life Sciences (37.55%) and Medical (26.58%) background contribute the most to attrition.
Salary: Most attrition happens in the lowest salary band (up to 5k) clear link between pay and resignations.
Experience: Employees with 1 year of service show the highest attrition, early exits are common.
Job Role: Sales Representatives and Laboratory Technicians face the highest attrition.
Gender: Male attrition (140) is higher than female attrition (79).

# Conclusion

- High attrition is mainly among young, less-experienced, and low-paid employees.
- Sales and technical roles need special focus for retention.
- Improving salary packages, career growth opportunities, and employee engagement in the first year can help reduce attrition.
