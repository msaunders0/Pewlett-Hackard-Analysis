# Pewlett-Hackard-Analysis

## Overview
  The purpose of this analysis was to determine the number of retiring employees for each job title and identify employees who are eligible to participate in a mentorship program for Pewlett Hackard.

## Results
<ul>
  <li>Using the ERD, I was able to easily determine how to join the necessary tables in order to create the new tables that were used to examine both the number of retiring employees and to identify empoloyees who were eligible to participate in the mentorship program.
</ul>    

<p align='center'><img src=https://github.com/msaunders0/Pewlett-Hackard-Analysis/blob/main/img/EmployeeDB.png></p>

<ul>
  <li>The retirement titles table contains employees who were born between January 1, 1952 and December 31, 1955 and lists their respective titles. However, some employees have had multiple titles throughout their tenure and this needed to be cleaned up.
</ul>

<p align='center'><img src=https://github.com/msaunders0/Pewlett-Hackard-Analysis/blob/main/img/retirement_titles.png></p>

<ul>
  <li>The unique titles table is a slice of the retirement tables table, where only the most recent job title for a soon to retire employee is indicated.
</ul>

<p align='center'><img src=https://github.com/msaunders0/Pewlett-Hackard-Analysis/blob/main/img/unique_titles.png></p>

<ul>
  <li>The mentorship eligibility table holds current employees who were born between January 1, 1965 and December 31, 1965. Thus, based on the qualifications for the mentorship program, these employees are eligible for mentorship!
</ul>
    
<p align='center'><img src=https://github.com/msaunders0/Pewlett-Hackard-Analysis/blob/main/img/mentorship_eligibility.png></p>

## Summary
<p>In the midst of the "Silver Tsunami" retirement onslaught, many roles will eventually need to be filled. These roles are as follows:</p>
<ul>
  <li>25,916 Senior Engineers
  <li>24,926 Senior Staff
  <li>9,285 Engineers
  <li>7,636 Staff
  <li>3,603 Technique Leaders
  <li>1,090 Assistant Engineers
  <li>2 Managers
    
<p align='left'><img src=https://github.com/msaunders0/Pewlett-Hackard-Analysis/blob/main/img/retiring_titles.png></p>

<p>After creating a new query to determine how many mentors will be needed in order to fulfill the demands of the mentorship program, it appears as though there are more than enough qualified, retirement-ready employees in all departments to serve as mentors. This is determined by comparing the image directly above to the image below.</p>
    
<p align='left'><img src=https://github.com/msaunders0/Pewlett-Hackard-Analysis/blob/main/img/count_mentorship.png></p>
    
<p>Additionally, since there is quite an imbalance between soon to be retirees vs. employees who are eligible for mentorship, I would recommend to Pewlett Hackard that the qualifications for the mentorship be expanded to include more participants. The filtered range for birth_date could be expanded, for example, or a new query including the hire_date from the Employees table could be used to create more expansive targetting.
