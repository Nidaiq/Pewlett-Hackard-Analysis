# Pewlett-Hackard-Analysis

# Background
Pewlett Hackard is a large company with thousands of employees.  As baby boomers retire, Pewlett-Hackard would need to offer retirement packages and also recognize what positions would need to be filled as the number of upcoming retirements would leave a large number of job openings.  The data is present in the form of various csv files.  These files would need to be joined in-order to achieve the information to analyze the job opportunities that could arise in the future for Pewlett-Hackard.

## Purpose
The purpose of this report is to:
- Create a retirement_titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955 to understand the employees that would be retiring so that plans can be made to fill their positions.  

- Create a mentorship_eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965 so that new employees can be mentored by those eligible for mentorship.

# Results
Images used for the analysis are found under the Resources folder, the tables under the Queries folder and the code in the Employee_Database_challenge.sql file.

- Looking at the silver_tsunami count.png image in the Resources folder it can be seen that Pewlett-Hackard will lose over 90398 positions during the phase.  If plans are not made to fill these positions accordingly it can seriously impact the company. Suitable measures need to be taken right away.

- Looking at the retiring_titles.png in the Resources folder it can be seen that Senior Engineer positions are the ones that will be heavily impacted followed by the Senior Staff positions.

- Referring again to the retiring_titles.png in the Resources folder, Engineers are the third highest titles retiring.

- List of employees for mentorship has been created and should be indicative of how many employees are ready to mentor new and upcoming talent.

- The mentor_count.png in the Resources folder shows how many employees would be eligible (sorted by their titles) to mentor the new employees.

# Summary and Conclusions
- Referring to the silver_tsunami count.png image in the Resources folder it can be seen that Pewlett-Hackard will lose over 90398 which can severely impact the day to day functions of the company if proper plans are not implicated to fill these positions right away.  Looking at the mentor_count.png file in the Resources folder it is evident that there aren’t enough employees to mentor the new employees that would need to be hired to fill empty positions.

- It is evident that Engineering will be the highest hit department when it comes to employees retiring in the near future.  Plans should be made to recruit future employees to fill the positions.  One way to start planning is to conduct a query to see how many positions are eligible for mentorship.  This can be done as a count function query which has been done and can be found as mentor_count.png in the Resources folder.  This query can be used to understand how many current employees can be promoted into senior positions and how many would need to be hired.  Looking at the mentor_count.png file it is evident that there aren’t enough people eligible to mentor the new employees.  Therefore, the company needs to speed up employing senior level staff that may be eligible to mentor and fill in the gaps.

- A query could also be conducted for specifically the engineering department to understand the turnover rate to get an idea about how many additional jobs would need to be panned for.  One way to do this is actually to run a query on the employees that have left and joining it with the salaries table.  This can indicate if employees in a certain salary range are leaving.  This could also lead hr to do further research if the companies salary range is too low and does not meet the industry standards. 

- It is also important to note that in deliverable # 2, since the titles are not sorted according to the instructions in the challenge, a different result is obtained every time the query is run because of the distinct on function used.  If the titles table is sorted the required results would be achieved consistently.

