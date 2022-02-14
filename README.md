# Pewlett-Hackard-Analysis 
## Overview of the analysis

The purpose of this analysis is to conduct a research for Pewlett Hackward with determining the number of retiring employees, their title, and identifying employees who qualified in a mentorship program. This analysis will be helpful in the hiring process so Pewlett Hackward knows detailed information of necessary employees with a specific title and department. 

## Results 
  ![EmployeeDb](https://github.com/Monsaiaung/Pewlett-Hackard-Analysis/blob/1c702ad4bde3466a7c303d1410c7741e7f4e7478/Pewlett-Hackard%20Analysis%20Folder/EmployeeDB.png)

Picture above is an ERD (Entity Relationship Diagram) that was created for visualing the relationship between the each table containing datas of employees, departments,salaries, Manager, Department of Employees and Titles.

- Before using the Distinct On code to clean up the data, the table contains some employees who have mulitple titles due to promotions throughout their time in the company. However this is a good information to know that employees do stay in the company long enough for promotion and climb up to higher positions.

 ![Unique_titles](https://github.com/Monsaiaung/Pewlett-Hackard-Analysis/blob/3a61ff79ac4ef0989503a57950c9d6fc8ce541d1/Pewlett-Hackard%20Analysis%20Folder/Unique_titles.png)
- From the Unique titles table that we created in Deliverable 1, we can observe employees that will be retiring in the "Silver tsunami" wave are in senior postions. These positions are Senior Engineer, Senior Staff, Engineer, Staff, Technique leader, Assistant Engineer, and Manager. 

![Numberretiree](https://github.com/Monsaiaung/Pewlett-Hackard-Analysis/blob/faa87dd4c4df2ea02c39535f4200c5a7669faea5/Pewlett-Hackard%20Analysis%20Folder/numberretire.png)
- In the "Silver Tsunami", there are about 26000 Senior Engineers, 25000 Senior Staffs and 9000 Engineers and 7600 Staffs retiring. So it is crucial that Pewlett Hackard finds talent or provide mentorship for younger talents to fill in these positions in the future. 

- For the Mentorship Eligibilty table, the criteria was flitering the data to see all the current employees with birth dates are between January 1, 1965 and December 31, 1965. From the data, we can see that 1549 employees are eligible for mentorship program. 
