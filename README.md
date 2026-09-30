# MERSON'S RECRUITMENT AND EMPLOYEE ATTRITION ANALYTICS REPORT

## Table of contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning Process](#data-cleaning-process)
- [Data Transformation,Analysis and Insights](#data-transformation-analysis-and-insights)
- [Visualization](visualization)
- [Recommendations](#recommendations)
- [Limitations](#limitations)


### Project Overview

The primary purpose of this analysis is to provide insights into workforce patterns that can support data-driven human resource decision-making within the organization.

### Data Source

The dataset used for this analysis was gotten from the Kaggle.com website. The dataset includes the following fields:
Employee_Name,EmpID,Salary,Position,State,DOB,Sex,MaritalDesc,RaceDesc,DateofHire,TermReason,Employmentstatus,Department,ManagerName,RecruitmentSource,PerformanceScore,Empsatisfaction,Absences.                                   

### Tools

- Microsoft Excel - Data Cleaning
- Microsoft PowerBI - Data Transformation
- Microsoft Word - Report writing


### Data Cleaning Process
  
1.	Fixing Column Headers
2.	Blank space detection and replacement
3.	Duplicate check and removal
4.	Column labeling
   
### Data Transformation, Analysis and Insights

##### Tranformation
The cleaned dataset was imported into Power BI environment for analysis. As part of the data preparation process, the dataset was transformed by creating the following column and measures using DAX functions.

| DAX Functions |   Measures   |
|---------------|--------------|
|AVERAGE        |Average Price |
|CALCULATE      |Top Country   |
|CALCULATE      |Top Color     |
|SUM            |Total Quantity|          |
|SUM            |Total Sales   |          |
|SUM            |Total Orders  |          |
|SUM            |              |TotalSales| 

##### Analysis and Insights
1st Objective: Analyze iPhone sales performance by Country, iPhone model and month.

* Sales performance by country: The UK performed the most in sales with 118K, USA with 115K, Canada with 84K, UAE with 78K, Germany with 53K and Pakistan with 47K.
* Sales performance by iPhone model: The iPhone 14 pro performed the most with 115K in sales, followed by the iPhone 15 pro max with 101K in sales. 
* Sales Monthly trend: The iPhone experienced a downward sales trend with 160K in the month of January compared to 99K in April.  


2nd Objective: Analyze customer purchasing patterns by storage, color and model.

* Most popular color: Out of 100 orders, there were 25 orders for iPhones with the color blue, making it the most popular color.
* Most popular storage: Out of 100 orders, there were 38 orders for iPhones with 256GB making it the most popular storage choice among the customers. 
* Most purchased iPhone model: Out of 100 orders, there were 24 orders for the iPhone 14 pro, making it the customer’s favorite. 


### Visualization
### iPhone Sales Performance
<img width="440" height="246" alt="Screenshot 2026-08-29 120532" src="https://github.com/user-attachments/assets/de27b6a1-73fc-4d6d-aefc-d2419bafb53d" />

### Customer Purchasing Patterns
<img width="434" height="248" alt="Screenshot 2026-08-29 120554" src="https://github.com/user-attachments/assets/ed4edb41-888c-496b-b4a4-d13c456df677" />


### Recommendations
Based on the analysis, we recommend the following actions:

- Address Weak Sales Performance in Pakistan.
- Improve the Performance of Underperforming iPhone Models.
- Address the Declining Monthly Sales Trend.
- Address Low Demand for Less Popular Colors.
- Reduce the Risk of Slow-Moving Storage Options.
- Improve the Quality and Coverage of Future Sales Data.

### Limitations
- The dataset only covers transactions from Jan 1, 2025 to May 1, 2025. As a result, findings may not reflect long term sales trends.
- The analysis is limited to the countries present in the dataset and may not represent the company’s performance in other countries.
- The dataset has limited customer information limiting customer behavior analysis.
- The Price column is generalized, so there is no way to know if the price of each iPhone model is per country or standard iPhone price.



