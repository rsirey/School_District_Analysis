# School District Analysis

## Project Overview

Analysis has been completed for Py City Schools in regards to testing scores in math and reading for grades nine through twelve. Trends in performance were showing in regards to specific schools, school size, school budget, and school type.

After the initial analysis, there was evidence of academic dishonesty, specifically in the ninth-grade scores at Thomas High School.

The analysis for the district needed to be conducted a second time, with the ninth grade Thomas High School scores removed, and the results compared with the original analysis. 

The following questions are to be answered by comparing the analysis:
* How is the district summary affected?
* How is the school summary affected?
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
  * Scores by school spending
  * Scores by school size
  * Scores by school type

## Resources

### Data Sources 

Schools_complete.csv

students_complete.csv


### Software 

Python 3.7.6

	Pandas
  
Anaconda 4.10.1

	Jupyter Notebook


## Results

The results of the comparative analysis can be seen in the data frames below. Each time data frames are shown, the first is the analysis completed including the 9th-grade math and reading scores from Thomas High School, and the latter showing those scores reported as NaNs.

### District Summary:

![district_summary_before2.png](Resources/district_summary_before2.png)

![district_summary_after.png](Resources/district_summary_after.png)

### Per School Summary:

![per_school_before.png](Resources/per_school_before.png)

![per_school_after.png](Resources/per_school_after.png)

With the questionable scores included in Thomas High School’s analysis, they rank in the top five schools in the district with all of their passing percentages (math, reading, overall) in the 90s. Once the 9th-grade math and reading scores are reported as NaNs, their passing percentages fall to 66.9%, 69.7%, and 65.1%, respectively. 

### Math Scores by Grade

![math_grade_before.png](Resources/math_grade_before.png)

![math_grade_after.png](Resources/math_grade_after.png)

### Reading Scores by Grade 

![reading_grade_before.png](Resources/reading_grade_before.png)

![reading_grade_after.png](Resources/reading_grade_after.png)

### Scores by School Spending 

![spending_grade_before.png](Resources/spending_grade_before.png)

![spending_grade_after.png](Resources/spending_grade_after.png)

### Scores by School Size 

![size_grade_before.png](Resources/size_grade_before.png)

![size_grade_after.png](Resources/size_grade_after.png)

### Scores by School Type

![type_grade_before.png](Resources/type_grade_before.png)

![type_grade_after.png](Resources/type_grade_after.png)


## School District Analysis Summary
The changes to the school district anaylsis once replaceing the 9th grade math and reading scores at Thomas High School as NaNs impacts the over scores for that school. Their overall passing in math and reading are drastically lowered, which does affect the district score overall. The testing and reporting condition at Thomas High School should be reviewed and adjusted as necessary to ensure accurate data reporting in the future. 
