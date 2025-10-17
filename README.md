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
## Get the Data :
Collected employee data (age, salary, department, job role, education, years in company, attrition)

## Cleaning the Data :
Removed mistakes/empty values.

## Making groups : 
Age groups, Salary ranges, etc.

## Create Calculations (DAX) :
Total Employees,
Attrition Count,
Attrition Rate = Attrition ÷ Total Employees,
Average Age, Salary, Years at Company.

## Build Visuals :
Cards : Overall employees, Attrition, Rate, Avg Age, Avg Salary, Years at company.
Charts : Attrition by Age, Education, Salary, Years at company, Job Role.
Donut/Bar/Line charts depending on what looks clear.

## Format & Design :
Used a clean color theme.
Added filters/slicers (e.g., Department, Gender).
Arranged visuals neatly for easy reading.

## Check & Share :
Verified numbers.
Published to Power BI Service.
Shared with HR team.

# Dashboard Interaction 
<a href="https://github.com/visakhjp/HR-Analytics-dashboard/blob/main/attrition.pbix">Dashboard</a>

# Dashboard Image
![Attrition dashboard](https://github.com/user-attachments/assets/c1554b29-3c5e-4797-b0ef-0e6f89773bb4)

# Project Insights
The HR Analytics dashboard shows that the organization has 1,470 employees, out of which 237 have left, giving an attrition rate of 16.1%. Most attrition is seen among employees aged 26–35, indicating younger staff are more likely to leave. Employees from Life Sciences and Medical backgrounds form the largest share of attrition, while those in Sales and Laboratory Technician roles are also highly affected. The data highlights that people with lower salary bands, especially up to 5k, and those with only one year of service, are leaving more often. Additionally, male employees show a higher attrition count compared to females. These patterns suggest that low pay, early-career challenges, and certain job roles contribute significantly to employee turnover.

# Conclusion
The study shows that attrition is concentrated among young employees in low salary bands and early service years, especially in sales and technical roles. Focused interventions in pay structure, career development, and employee support during the first year can help improve retention.
