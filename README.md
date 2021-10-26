# Pewlett Hackard - Retirement Analysis
## Overview
This analysis was conducted to create 2 tables to analyze the number of retiring employees along with their position titles as well as determine the number of employees eligible for the mentorship program. The first table included the employee full name, employee number, position title as well as start/end dates. In the 2nd table, we have employee number, full name, birth date, start/end date and position title. Both queries were conducted using SQL in pgAdmin. The source query file for this analysis can be viewed ![here](https://github.com/JonathanBrown003/Pewlett_Hackard_Analysis/blob/b7fc65c07f9185199a9a84dbe578a194176ad630/Queries/Employee_Database_challenge.sql).

## Results
1) From the ![retiring_titles](https://github.com/JonathanBrown003/Pewlett_Hackard_Analysis/blob/6a250f36857c78b70e96704f29c52c6bf3f46beb/Data/retiring_titles.csv) csv file, we can clearly ascertain that 2/3 of likely upcoming retirements will be Senior Engineers or Senior Staff. 
2) We should have our recruiting department start to bring in replacements soon for training and to soak up as much institutional knowledge as they can from these senior staff close to retirement. 
3) We can also have leadership view the ![mentorship_eligibility](https://github.com/JonathanBrown003/Pewlett_Hackard_Analysis/blob/b7fc65c07f9185199a9a84dbe578a194176ad630/Data/mentorship_eligibility.csv) candidates in this file to review and decide which employees will be eligible to be a mentor going forward. 
4) We can pair these employees with new or mid-career staff for training and understanding of company culture, strategy and operations. This will ensure smooth operations moving forward as the "silver tsunami" sweeps Pewlett Hackard with retirements. 

## Summary
As the "silver tsunami" starts to sweep Pewlett Hackard, I'd create another query to organize potential retirees by department using the department table. This will help count the number of employees with retirement in the near horizon by department. Those departments with the highest number of retirees could have their leadership alerted so they can put an action plan in place to hire and train the future of the workforce while institutional knowledge is still present with the retiring staff.

Another query we can conduct is mentorship-eligible employees ordered by department and counted by position title. This will also give a good indication to senior leadership of a hiring strategy going forward by department based on the number of senior staff in that department. 
