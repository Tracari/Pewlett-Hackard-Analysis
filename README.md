# Pewlett-Hackard-Analysis
## Overview
Pewlett-Hackard is a large company preparing for their “Silver Tsunami”, a cycle-out of retirement eligible employees. Pewlett-Hackard more familiar with Excel’s VBA will be aquainted with PostGreSQL, a more suitable and up-to-date relational database that uses SQL to query, construct, and catalogue data. Working with 6 .csv files of employee data, data-modeling, -engineering, and -analysis will be applied to Excel's dataframes and tabular data to diagram and illustrate the workforce/staffing requirements for the Company's mentorship initiaitive for position transitions. 

#### Data environment: 
- PgAdmin 6.10
- PostgresSQL 7.1.1
- QuickDatabaseDiagrams


## Result 
- The retirement_titles table inaccurately identifies the retiring population. This dataset contains multiple duplicate
	employee numbers representing more potential vacancies than actual.
  
<img width="716" alt="Screen Shot 2022-09-19 at 8 22 52 PM" src="https://user-images.githubusercontent.com/105556091/191146795-ad021b03-9334-4b8b-8abb-938cf94e18aa.png">


- The unique_titles table identifies anticipated vacancy titles more precisely however, its a low level analysis of whats essentially being questioned. How many vacancies can be expected by title, by department? It leaves more work to be done.

<img width="558" alt="Screen Shot 2022-09-19 at 8 32 49 PM" src="https://user-images.githubusercontent.com/105556091/191147746-93f5e297-0a82-4990-b4e9-7980f498d0b5.png">

- The retiring_titles table is a high level dissolution that is essentially the purpose of the data analysis for the 'Silver Tsunami'

<img width="219" alt="Screen Shot 2022-10-02 at 12 22 49 PM" src="https://user-images.githubusercontent.com/105556091/193465005-c35b99ad-eaff-4bae-a1d4-6528e4a52682.png">


- The mentorship_eligibility table is effective but can be more advantageous if were organized by department, and  additionally filtered to identify the total employees by department
 
 <img width="795" alt="Screen Shot 2022-09-19 at 8 36 47 PM" src="https://user-images.githubusercontent.com/105556091/191148173-c4a59f9d-aeaf-4eec-8389-955fb856f44c.png">


## Summary  

As the Silver Tsunami takes impact Pewlett Hackard will need to anticipate the vacancies of:
- 25,916 Senior Engineers, 
- 24,926 Senior Staff, 
- 9,285 Engineers, 
- 7,636 Staff, 
- 3,603 Technique Leaders, 
- 1,090 Assistant Engineers, and 
- 2 Managers, for a total 72,458 positions.
 
<img width="264" alt="Screen Shot 2022-10-02 at 2 15 08 PM" src="https://user-images.githubusercontent.com/105556091/193473052-0dd27ff0-be9f-4bd3-bd67-4b7d8cc774ee.png">



With further analysis, 2 additional queries were performed to verify if enough retirement-ready employee were available to mentor the next generation of Pewlett Hackard employees. Unfortunately though, there are not enough eligible mentors for the Company’s initiative to be successful. In the mentorship eligibilty initiative there are only 1,549 eligible mentors. There are:
- No Managers, 
- Only 291 Senior Engineer, 
- 434 Senior Staff, 
- 397 Engineers, 
- 290 Staff, 
- 77 Technique Leaders, 
- 60 Assistant Engineers. 

<img width="222" alt="Screen Shot 2022-10-02 at 12 30 50 PM" src="https://user-images.githubusercontent.com/105556091/193473061-4c1ed2c2-26ab-472e-a423-32e12dc4fa3b.png">


<img width="618" alt="Screen Shot 2022-10-02 at 3 45 09 PM" src="https://user-images.githubusercontent.com/105556091/193473236-d7649fda-d237-415c-855e-cda7637e1c12.png">






