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


|MEASURES	              |DAX FUNCTION|
|-----------------------|------------|
|Active Employees	      |COUNT       |
|Attrition Rate	        |DIVIDE      |
|Average Satisfaction	  |AVERAGE     |
|Exceeds Expectations	  |CALCULATE   |
|Exceeds Percentage	    |CALCULATE   |
|Retention Rate	        |CALCULATE   |
|Terminated Employees	  |CALCULATE   |
|Total Employees	      |COUNT       |
|Voluntary Terminations |CALCULATE   |


##### Analysis and Insights

* **1st Objective: To analyze employee performance across different recruitment sources.**
  
Employee performance quality varies meaningfully by recruitment source. Diversity Job Fair hires recorded the highest proportion of employees rated "Exceeds Expectations" at 20.7%, followed by Employee Referral at 16.1%.

* **2nd Objective: To examine employee attrition patterns across recruitment sources.**
  
Terminated employee counts varied considerably by recruitment source. Google Search recorded the highest number of terminations (30), followed by Indeed (21), LinkedIn (18), Diversity Job Fair (16) and CareerBuilder (11), while Employee Referral (5), Website (1), Online Web Application (1) and Other (1) recorded far fewer. 

* **3rd Objective: To analyze the reasons for employee termination and identify the major drivers of attrition.**

The analysis shows that employee departures were concentrated around a small number of recorded reasons. "Another position" (20 cases), "Unhappy" (14), "More money" (11), "Career change" (9), and "Hours" (8) collectively accounted for 59.6% of all 104 recorded terminations. Attendance-related exits (7) and "Performance" (4) followed.

* **4th Objective:  Examine attrition levels across different departments**
  
Attrition is heavily concentrated in specific departments. Production recorded the highest attrition rate at 39.7%, followed by Software Engineering at 36.4%, Admin Offices at 22.2%, IT/IS at 20.0%, and Sales at the lowest, 16.1%. 

* **5th Objective: To evaluate recruitment sources based on employee retention, performance, and satisfaction outcomes.**
  
Employment outcomes differ sharply by recruitment source. Website (92.3% active), Employee Referral (83.9% active) and LinkedIn (76.3% active) produced the strongest retention outcomes, while On-line Web Application (0% active, single hire), Google Search (38.8% active) and Diversity Job Fair (44.8% active) produced the weakest. 
 


### Visualization
### Workforce and Recruitment Overview Dashboard
<img width="975" height="558" alt="image" src="https://github.com/user-attachments/assets/3f398d9d-f78a-45aa-985e-a603a1b5f6a1" />

### Attrition Analysis Dashboard
<img width="975" height="552" alt="image" src="https://github.com/user-attachments/assets/08da782a-95ea-4d1b-a7be-02a4f678b761" />



### Recommendations
Based on the analysis, we recommend the following actions:

- Recruitment Source Distribution
- Attrition Across Recruitment Sources
- Reasons for Employee Termination
- Performance and Attrition
- Recruitment Source and Employee Outcomes



### Limitations
- The dataset represents employee information from a specific period and may not reflect the organization's current workforce structure, recruitment practices, or employee outcomes.
- The dataset identifies the recruitment source used for employees but does not contain detailed information about recruitment costs, time-to-hire, candidate qualifications, or the recruitment process. 
- Although termination reasons are recorded, the dataset does not provide detailed qualitative information explaining the circumstances behind each departure. 
- Employee performance is recorded using categorical performance classifications rather than continuous performance measurements. 




