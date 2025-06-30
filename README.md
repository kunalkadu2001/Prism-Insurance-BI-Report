# Prism-Insurance-BI-Report
This project is an insurance dashboard created in Power BI. Data was first cleaned in MS SQL Server and then imported into Power BI. Key insights like claim amount by age, policy status, and premium by policy type were visualized with filters for easy analysis.

# Project Objective:
To analyze insurance data and provide key insights into policy status, claim trends, and premium distribution using an interactive Power BI dashboard for better decision-making.

## Dataset used
- <a href="https://github.com/kunalkadu2001/Prism-Insurance-BI-Report/blob/main/InsuranceData.csv"> Dataset</a>

## Questions(KPIs)

- What is the total number of active and inactive policies?
- What is the total claim amount made across all policies?
- Which age group has the highest total claim amount?
- What is the average premium paid per policy type?
- What percentage of claims have been approved vs rejected?
- How many policies are issued to male vs female customers?
- What is the trend of claim amounts over time (monthly/quarterly)?

## Process

- Imported raw insurance data into MS SQL Server for initial storage.
- Performed data cleaning by removing duplicates and identifying null values.
- Transformed columns (like dates, text formatting) and corrected data types.
- Loaded the cleaned data into Power BI for analysis.
- Created DAX measures and added interactive visuals for better insights.


## Dashboard

![Screenshot 2025-06-29 220219](https://github.com/user-attachments/assets/7f62a26c-3a0b-4a18-a530-42fa763cef91)


## Insights

- Total Active vs Inactive Policies: Most policies are currently active, indicating strong customer retention.
- Total Claim Amount: The total claim amount across all records is significantly high, showing active claim usage.
- Highest Claiming Age Group: Customers aged 40–60 have filed the highest total claims.
- Average Premium by Policy Type: Health policies have the highest average premium compared to other types.
- Claim Approval Rate: Over 70% of claims are approved, showing a positive claim settlement trend.
- Gender-Based Policy Count: Male customers hold a slightly higher number of policies than females.
- Claim Trend Over Time: Claims show a rising trend in the last two quarters, indicating seasonal or policy-related impacts.


## Final Conclusion:
- This dashboard highlights key trends in policy status, claim behavior, and customer demographics, helping stakeholders make better decisions on policy offerings and claims handling.








