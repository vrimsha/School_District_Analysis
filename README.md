# School_District_Analysis
## Overview of the school district analysis: 
The school board discovered that the students_complete.csv file shows evidence of academic dishonesty. The math and reading grades of ninth graders have been adjusted in Thomas High School. The school board request is prepare written report to describe how the math and reading grades replace with NaN in Thomas High School will affect the overall analysis.

## Results: 
### Deliverable 1: Replace the reading and math scores.
Replace the 9th grade reading and math scores at Thomas High School with NaN.

Step 1. Import numpy as np.

Step 2. I used loc method on the student_data_df to select all the reading scores from the 9th grade at Thomas High.

![Loc_method](Loc_method.png)

Step 3. Refactor the code in Step 2 to replace the math scores with NaN.

![Refactor_the_code](Refactor_the_code.png)

Step 4. Check the student data for NaN's. 

![Student_data_for_NaN](Student_data_for_NaN.png)

### Deliverable 2 : Repeat the school district analysis
### District Summary
Step 1. Combine the data (student_data and school_data)into a single dataset.

![Combine_the_data](Combine_the_data.png)

<br>Step 2. Calculate tootal numbers of schools, students and the total budget.</br>
<br>Schools: 15</br>
<br>Students: 39,170</br>
<br>The Total Budget: $24,649.428</br>

<br>Step 3. Calculate the Average Scores using the "clean_student_data".</br>
<br>Average of clean reading score is 81.85579580976001 compare to original school data 81.87784018381414. The dirrence is 0.02204437405413.</br>
<br>Average of clean math score is 78.93053295099331 compare to original school data 78.98537145774827. The dirrence is 0.05483850675496.</br>

Please see below average reading and math scores from original school data:

![the_average](the_average.png)


Step 4. Get the number of students that are in ninth grade at Thomas High School.
Total number of students in 9th grade at Thomas High School is 461. Which is 1.06% 9th grade students from 39,170 students.

![THS_9_count](THS_9_count.png)

Step 5. Subtract the number of students that are in ninth grade at Thomas High School from the total student count to get the new total student count.

![new_student_count](new_student_count.png)

Step 6. Calculate the passing rates using the "clean_student_data".

<bk>Passing math count from the clean student data is 28,939 which is 74.76% compare to original passing math count 29,370 which is 74,98%.</bk>
<bk>Passing reading count from the clean student data is 33,158. which  is 85.65% compare to original passing reading count 33610 which is 85.80%..</bk> 

Overall passing percentage is 64.9% compare to the orogonal data 65.2%. The difference is 0.3%.

As a result, the district summary with the clean student data did affect approx. on 0.3% on the data results.

Please see below the district summary:

![district_summary](district_summary.png)

### School Summary 
Please see below per School Summary:

![per_school_summary](per_school_summary.png)

Please see below how replacing the ninth graders’ math and reading scores affects Thomas High School’s performance relative to the other schools.

![per_school_summary_no9th_grade](per_school_summary_no9th_grade.png)

<bk>The school summary was affected slightly, only in % of passing math, reading, and overall passing scores at the Thomas High School.</bk>

<br>% Passing math score went up by 26.3% from 66.9% to 93.2%.</br>
<br>% Passing reading score went up by 27.3% from 69.7% to 97.0% </br>
<be>% Overall passing score went up by 25.1% from 65.0% to 90.1%

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade


#### Scores by school spending


#### Scores by school size


#### Scores by school type





## Summary: 

Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.