# HR Employee Attrition

## Table of Contents
 - [Project Overview](#project-overview)
 - [Data Sources](#data-sources)
 - [Recommendations](#recommendations) 

### Project Overview
---
In this project we will analyze the employee data to gain insights on what factors influence employee attrition. Given in the data is a set of data points on the employees who are either currently working within the company or have resigned. The objective is to identify and improve these factors to prevent loss of good people.


![Screenshot 2024-01-12 135517](https://github.com/AureliaTambur/HR-employee-attrition/assets/156318226/dcc3d09c-16db-4727-9966-dc5fccfe7b48)


### Data Sources
Data contains survey results of 1470 employees who are either currently working within the company or have resigned. It includes details about their age, salary, education, satisfaction scores, marital status, years of working etc. It is available on: Employee Attrition | Kaggle.

### Tools

- Python: pandas - Data Cleaning and Data Analysis [Download here](https://www.anaconda.com/)
- Python: matplotlib, seaborn- Data Visualization

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks: 
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis
 EDA involved exploring the data to answer at the main business goal to identify if employee attrition is influenced by such factors as department, salary, overtime, job satisfaction, and/or traveling.
 The subquestions for this analysis were:
 1. Who is leaving the organization ?
 2. When they are leaving ?
 3. Why they are leaving ?

### Data Analysis
Some interesting code worked with:
``` python
df.shape
```

``` python
df['Gender'].unique()
```

### Results/Findings
Results
The analysis results are summarized as follows:
1. Attrition rate of the organization is 16 % for the survey period.
 It is more present until age of 40,  higher for male in 3 % more than female.
2. Sales Department is the most affected with 20 % of leaving.
3. Employees are leaving after 10 year of service in 92% of cases.
4. Employees who leave have a smaller monthly salary in all departments, and/or have over-time working.
5. Attrition is decreasing with higher score of job satisfaction.
6. Most frequently employees that have business travel leave the company.

### Recommendations
Based on the analysis of employee attrition, several recommendations can be made to address and mitigate the issues identified:
1. Make a historical analysis of organization’s metrics to get full picture.
    - Targeted Retention Strategies for Age Group Below 40:
     Implement targeted retention strategies for employees below the age of 40, as they seem to be more prone to attrition. This could include career development programs, mentorship initiatives, or wellness programs.
     - Gender-Specific Retention Strategies:
    This might involve assessing and addressing factors contributing to this discrepancy, such as work-life balance or career advancement opportunities.
2. Focus on the Sales Department:
 This could involve conducting department-specific surveys to understand the reasons behind the high turnover and implementing targeted solutions.
3. Retention Programs for Long-Term Employees:
    - Recognize their contributions, provide opportunities for skill development or advancement, and ensure that they feel valued and engaged.
4. Address Salary Disparities and Overtime:
    - Review the compensation structure across all departments to address salary disparities. Additionally, consider evaluating workload and overtime policies to ensure a healthy work-life balance for employees.
5. Enhance Job Satisfaction:
    - Implement measures to improve job satisfaction. This could include conducting regular employee surveys, addressing feedback, and creating a positive work environment.
6. Business Travel Policies:
    -  This may involve providing additional support or benefits for employees who frequently travel for business, such as flexible work arrangements or additional time off.
7. Exit Interviews and Feedback Mechanisms:
    - Conduct thorough exit interviews to gather insights from departing employees. Use this feedback to identify common themes or issues contributing to attrition and adjust policies or practices accordingly.
8. Employee Engagement Initiatives:
    - Implement employee engagement initiatives across the organization. This could include team-building activities, recognition programs, and communication strategies to foster a positive workplace culture.
9. Continuous Monitoring and Adjustment:
    - Regularly monitor attrition rates and employee satisfaction levels. Make adjustments to strategies based on ongoing feedback and changing organizational dynamics.

### Limitations
Basic variables where tested by: 
  - deleting duplicates,
  - checking for null values, 
  - checking categorical and continuous values for abnormalities,
  - dropping columns with only one unique value: EmployeeCount (1), Over18 (Y), StandardHours (80).

### References
- [About Correlations](https://towardsdatascience.com/eveything-you-need-to-know-about-interpreting-correlations-2c485841c0b8)
- [Employee attrition rate](https://www.hibob.com/blog/measuring-attrition/)















