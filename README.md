# School District Analysis

## Project Overview
A city's school district chief data scientist needs to analyze information about schools in the area.

Given datasets of high school students and schools, the following has been extracted:
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting the each of the following metrics:
	+ Top 5 and bottom 5 performing schools, based on the overall passing rate
	+ The average math score received by students in each grade level at each school
	+ The average reading score received by students in each grade level at each school
	+ School performance based on the budget per student
	+ School performance based on the school size
	+ School performance based on the type of school


## Resources
Data Sources:
- schools_complete.csv
- students_complete.csv

Software:  
- Python 3.7.4
- Anaconda 4.7.12

## Summary
*refer to JupyterNotebook*

## Challenge Overview
The grades of ninth graders at Thomas High School have been changed due to some extent of academic dishonesty. All the math and reading scores of the ninth graders at Thomas High School must be removed.

## Challenge Summary
How is the district summary affected?  
*Compared to the original district summary, the adjusted one shows a .1 drop in Average Math Score and a 1% drop in the % Passing Math, % Passing Reading, and % Overall Passing*

How is the school summary affected?  
*Removing the ninth-grade scores resulted in a 26.3609% drop in % Passing Math, a 27.6453% drop in % Passing Reading, and a 27.003% drop in % Overall Passing*

How does removing the ninth grader's math and reading scores affect Thomas High School's performance, relative to other schools?  
*Compared to other schools, Thomas High School went from having the 2nd highest % Overall Passing to 11th highest after removing the ninth-grade scores*

How does removing the ninth-grade scores affect the Math and Reading Scores By Grade, Scores by School, Scores by School Spending, Scores by School Size, and Scores by School Type?  
*The Math and Reading Scores By Grade tables simply reflected that all Math and Reading scores for the ninth graders at Thomas High SChool are NaN.*  
*The Scores by School table showed Thomas High School as the 11th best Overall Performance school after the grader were removed.*  
*The Scores by School Spending table showed a drop of 6.5903% in % Passing Math, 6.9113% in % Passing Reading, and 6.7508% in % Overall Passing for schools with spending ranges of $630-$644 per student.*  
*The Scores by Size table's Medium Size School row was affected with a drop of 5.2721% in % Passing Math, 5.529% in % Passing Reading, and 5.4006% in % Overall Passing.*  
*The Scores by School Type table showed that Charter school performance dropped by 3.2951% in % Passing Math, 3.4556% in % Passing Reading, and 3.3749% in % Overall Passing when the ninth-grade scores were removed.*



