# HR-Analysis-MySQL-PowerBi

![HR PIC](https://github.com/JaneNnyawira/HR-Analysis-MySQL-PowerBi/assets/134518125/a226385e-1421-4b3f-aac5-7166d522bc80)


# Data Used
* Data - HR Data with over 23000 rows from the year 2000 to 2020
* Data Cleaning and Analysis - MySQL Workbench
* Data Visualization - PowerBI

# Questions
* What is the gender breakdown of employees in the company?
* What is the race/ethnicity breakdown of employees in the company?
* What is the age distribution of employees in the company?
* What is the age distribution of gender in the company?
* How many employees work at headquarters versus remote locations?
* What is the average length of employment for employees who have been terminated?
* How does the gender distribution vary across departments and job titles?

# Insights
* There are more male employees.
* The White race is the most dominant. The Native Hawaiian and American Indian are the least dominant.
* 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
* Non-conforming were least aged, then females and most aged were the males.
* A large number of employees work at the headquarters versus remotely.
* The average length of employment for terminated employees is around 8 years.
* The gender distribution across departments is fairly balanced but there are generally more male than female employees.

# Limitations
* Some records had negative ages and these were excluded during querying (967 records). Thus ages used were 18 years and above.
* Some termdates were far into the future and were not included in the analysis too (1599 records). The only term dates used were those less than or equal to the current date.
  
