# Pewlett-Hackard-Analysis 
## Overview of the analysis

The purpose of this analysis is to conduct a research for Pewlett Hackward with determining the number of retiring employees, their title, and identifying employees who qualified in a mentorship program. This analysis will be helpful in the hiring process so Pewlett Hackward knows detailed information of necessary employees with a specific title and department. 

## Results 
  ![EmployeeDb](https://github.com/Monsaiaung/Pewlett-Hackard-Analysis/blob/1c702ad4bde3466a7c303d1410c7741e7f4e7478/Pewlett-Hackard%20Analysis%20Folder/EmployeeDB.png)

Picture above is an ERD (Entity Relationship Diagram) that was created for visualing the relationship between the each table containing datas of employees, departments,salaries, Manager, Department of Employees and Titles.

- Before using the Distinct On code to clean up the data, the table contains some employees who have mulitple titles due to promotions throughout their time in the company. However this is a good information to know that employees do stay in the company long enough for promotion and climb up to higher positions.

 ![Unique_titles](https://github.com/Monsaiaung/Pewlett-Hackard-Analysis/blob/3a61ff79ac4ef0989503a57950c9d6fc8ce541d1/Pewlett-Hackard%20Analysis%20Folder/Unique_titles.png)
- From the Unique titles table that we created in Deliverable 1, we can observe employees that will be retiring in the "Silver tsunami" wave are in senior postions. These positions are Senior Engineer, Senior Staff, Engineer, Staff, Technique leader, Assistant Engineer, and Manager. 

![Numberretiree](https://github.com/Monsaiaung/Pewlett-Hackard-Analysis/blob/97ed489d188d191dfacb87b927b9af9c18b2b1b2/Pewlett-Hackard%20Analysis%20Folder/numberretire.png)
- In the "Silver Tsunami", there are 29414 Senior Engineers, 28254 Senior Staffs and 14222 Engineers, 12243 Staffs retiring, 4502 Technique Leader, 1761 Assistant Engineer and 2 Manager. So it is crucial that Pewlett Hackard finds talent or provide mentorship for younger talents to fill in these positions in the future. 

- For the Mentorship Eligibilty table, the criteria was flitering the data to see all the current employees with birth dates are between January 1, 1965 and December 31, 1965. From the data, we can see that 1549 employees are eligible for mentorship program. 

## Summary

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
- There will be a total of 90,398 roles to be filled in the "silver tsunami". 57668 of the 90,398 roles (64%) of the roles are in senior positions. So Pewlett Hackward should mentor their existing employees or find senior level employees so they can fill in the positions of retirees in the "silver tsunami". 

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
- According to Mentorship Eligibility data table, there are 1549 eligible employees who qualify to be mentored. There are 57668 senior position retirement-ready employees. So there are enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. In fact, Pewlett Hackward should filter the age range of mentorship eligibility so there will be more employees to be trained. 

Two other queries or tables that could probide more insight into the upcoming "silver tsunami"
- A table with the count and title of the Mentorship Eligibility would be helpful in knowing the exact number in a glance of how many mentorship eligible employees there are so Pewlett Hackward would know the exact Mentor to Mentoship ratio. 
- Another table would be to have a wider birth date filter of Mentorship Eligibility so Pewlett Hackward can fill the leaving positions better. Also a table knowing how long an employee in each department has been in the company would help Pewlett Hackward know who know the company system well enough for promotion or mentorship program. 

