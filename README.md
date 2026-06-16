# Parks_and_Recreation-SQL-Analytics
SQL-based employee data analysis and reporting project using MYSQL and Parks_and_Recreation dataset. 

### PARKS AND RECREATION SQL PROJECT 

----


**Overview**
-----


This is my first SQL project, created to demonstrate SQL skills using the fictional Parks and Recreation dataset popularized by Alex The Analyst. The dataset simulates a real-world employee management system containing employee demographics, salary information, and department data.

The goal of this project was to practice writing SQL queries, working with relational databases, and performing basic data analysis tasks commonly used in business intelligence and data analytics roles. Using SQL, the project explores employee distribution across departments, salary structures, and compensation trends, while also simulating a structured salary adjustment model to evaluate the impact of different compensation rules.

Overall, this project combines foundational SQL techniques with practical business analysis to transform raw employee data into meaningful insights about workforce structure and payroll distribution.



------

**Objectives**
----

In this project, I focused on:
* Analyzing employee distribution across departments to understand workforce structure within the organization.
* Evaluating salary patterns across departments, including total and average compensation levels.
* Identifying top-earning employees and assess how individual salaries compare within the organization.
* Determining employees earning above the organizational average to understand compensation segmentation.
* Examining salary disparities across departments, including ranges and total payroll costs.
* Simulating a structured compensation adjustment model to evaluate the impact of salary increases and departmental incentives on overall payroll distribution

------
 
**Tools Used**
------

	•	SQL
	•	MySQL
 
--------
 
**Dataset**
--------

The project uses a fictional Parks and Recreation employee dataset containing information such as:
* Employee demographics


  
<img width="824" height="447" alt="Demographics " src="https://github.com/user-attachments/assets/85386cb2-1a2d-4f25-9f9b-06cadf1f7b45" />

-----------

* Employee salaries



<img width="755" height="465" alt="salary" src="https://github.com/user-attachments/assets/9f6313f2-f03d-48c1-a40a-b330b367dd87" />


---------------
  
* Department information

  
<img width="746" height="418" alt="Screenshot 2026-06-15 at 4 08 16 PM" src="https://github.com/user-attachments/assets/a05a4011-c362-4e2a-88f6-8e9a5b20be55" />

-------------------
 
**SQL Concepts Practiced**
------

Some of the SQL concepts explored in this project include:
* SELECT statements
* WHERE clauses
* ORDER BY
* GROUP BY
* LIMIT and ALIASING 
* Aggregate functions
* JOINS
* CASE statements
* Subqueries
* Analytical thinking applied to real-world HR and payroll scenarios

 

### Business Questions and Answers 
 -------
**Employee Structure Analysis**

**Q1** How many employees are in each department?

<img width="681" height="416" alt="Q1" src="https://github.com/user-attachments/assets/9b232ef8-423d-4919-8dc0-8e17a26513ce" />

**Insight :** 

This analysis reveals that the workforce is unevenly distributed across departments. Parks and Recreation has the majority with 7 employees, followed by Public Works with 2, while Healthcare and Finance each have 1 employee. This shows that Parks and Recreation is the main operational unit, while the other departments are much smaller and likely more specialized. This structure helps identify where most resources and staffing are concentrated, which is useful for planning and resource allocation.

---------

**Q2** What is the total salary expenditure per department?

<img width="1215" height="787" alt="Q2" src="https://github.com/user-attachments/assets/63472844-beec-4311-8999-c3aacf08576e" />


**Insight :**

This builds on the employee distribution analysis by showing how salary costs are spread across departments. Parks and Recreation has the highest total payroll at 395,000, which aligns with it being the largest department in terms of staff size. Public Works follows with 147,000, while Finance 70,000 and Healthcare 55,000 have significantly lower total salary costs, reflecting their smaller workforce sizes. Overall, this indicates that salary expenditure is strongly influenced by headcount, with Parks and Recreation driving the majority of payroll costs in the organization.

----------

**Q3** Who are the top 5 earners in the organization ? 

<img width="1220" height="817" alt="Q3" src="https://github.com/user-attachments/assets/b3faf2e3-24e7-44f9-985e-bb260c690530" />

**Insight :**
This analysis highlights the organization’s highest earners and provides visibility into key compensation levels. At the top is Emmanuel Desmond (120,000), followed by Chris Traegar (90,000). The list continues with Leslie Knope (75,000), and a close grouping of Ben Wyatt (70,000) and Ron Swanson (70,000).
These employees represent the upper tier of the organization’s salary structure, likely reflecting senior responsibility, specialized roles, or leadership positions. The relatively close salaries among the lower three suggest a clustered mid-senior compensation band, while Emmanuel Desmond stands out significantly above the rest, indicating a distinct top-level pay bracket.

-------------

**Q4** What is the total salary expenditure of the organization ? 

<img width="709" height="414" alt="Screenshot 2026-06-16 at 9 27 54 PM" src="https://github.com/user-attachments/assets/d2152897-a97a-451d-9cae-b28a56ec44d0" />


**Insight :**

The organization’s total salary expenditure is 807,000, representing the full payroll cost across all departments. This figure is driven largely by Parks and Recreation, which accounts for the biggest share of staffing and therefore the highest portion of salary spending. Public Works follows at a moderate level, while Finance and Healthcare contribute the smallest portions due to their limited headcount. This total provides a clear baseline for understanding overall payroll scale and is essential for budgeting, cost control, and financial planning.

--------------

**Q5** What is the average salary across the organization 

<img width="761" height="390" alt="Screenshot 2026-06-16 at 9 32 00 PM" src="https://github.com/user-attachments/assets/24fc9665-cfb0-44e4-83f3-04a0d4498e00" />


**Insight :** 

The average salary is 62,076.92, which serves as a benchmark for evaluating individual and departmental compensation. It helps identify whether salaries are generally balanced or skewed toward higher or lower earners and supports comparisons across departments. When used alongside total salary, it provides a clearer picture of both overall payroll size and typical employee compensation levels.


_____________ 


**Q6** Which employees earn above the organization's average salary

<img width="1226" height="819" alt="Screenshot 2026-06-16 at 9 39 17 PM" src="https://github.com/user-attachments/assets/6dd3cb8e-c19f-460c-96bb-25e05f2ffcd7" />

**Insight :** 

There are 6 employees earning above the organization’s average salary of 62,076.92, indicating a relatively small group of higher-compensated staff within the organization. This group represents the upper segment of the pay structure and likely includes more experienced or senior-level roles.

Employees above average salary:

* Emmanuel Desmond — 120,000
* Chris Traeger — 90,000
* Leslie Knope — 75,000
* Ben Wyatt — 70,000
* Ron Swanson — 70,000
* Craig Middlebrooks — 65,000

------------------

**Q7** How would employee salaries change after applying a structured compensation policy based on salary bands and departmental incentives?

<img width="1223" height="820" alt="Screenshot 2026-06-16 at 9 50 01 PM" src="https://github.com/user-attachments/assets/7075568e-9585-417f-9dcf-4dbc5dc878a8" />

**Insight :**

This analysis models a proposed compensation structure to understand its impact on employee pay across the organization. Under this policy, employees earning below 50,000 receive a 5% increase, while those earning 50,000 or more receive a 7% increase. In addition, employees in the Finance department receive an extra 10% bonus applied on top of the adjusted salary.

This approach helps evaluate how rule-based salary adjustments would affect overall payroll distribution. It highlights the impact of combining performance-based or banded increases with department-specific incentives, showing how certain groups (especially Finance) would experience relatively higher compensation growth compared to others.

---------- 






**Project Structure**
-------
* Dataset 
* Read.me


**Key Learnings**
----------


* Developed strong understanding of how to use SQL aggregation functions such as COUNT, SUM, and AVG to analyze workforce and salary data.
* Improved ability to use GROUP BY to segment data by department and derive meaningful business insights.
* Gained experience in identifying salary distribution patterns, including top earners, above-average employees, and departmental pay differences.
* Applied JOIN operations to combine employee demographic and salary datasets for richer analysis.
* Strengthened skills in using subqueries to compare individual salaries against departmental and organizational averages.
* Learned how to use CASE WHEN statements to simulate real-world compensation policies and model business scenarios.
* Built understanding of how data analysis can support HR and finance decision-making, especially in budgeting and workforce planning.


---------

**Future Improvements**
-------

* Expand the dataset to include additional attributes such as job titles, tenure, and performance ratings for deeper analysis.
* Introduce time-based data to track salary changes, promotions, and employee growth over time.
* Build interactive dashboards (e.g., Power BI or Tableau) to visualize salary distribution and department performance.
* Enhance the compensation model by adding performance-based bonuses and more realistic HR rules.
* Perform deeper statistical analysis to identify pay gaps, outliers, and equity issues across departments.
* Automate SQL queries using Python or scheduled workflows for repeatable reporting.
* Incorporate data validation and cleaning steps to ensure accuracy and consistency of future datasets.

 
--------
 
**Acknowledgement**

This project was inspired by the SQL training content created by Alex The Analyst and was completed as part of my self-learning journey in data analytics.

-----------------




