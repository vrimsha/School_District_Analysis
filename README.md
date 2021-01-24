# School_District_Analysis
## Overview of the school district analysis: 
The school board discovered that the students_complete.csv file shows evidence of academic dishonesty. The math and reading grades of ninth graders have been adjusted in Thomas High School. The school board request is prepare written report to describe how the math and reading grades replace with NaN in Thomas High School will affect the overall analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
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

Step 2. Calculate tootal numbers of schools, students and the total budget.
Schools: 15
Students: 39,170
The Total Budget: $24,649.428

Step 3. Calculate the Average Scores using the "clean_student_data".
Average reading score is 81.85579580976001;
Average math score is 78.93053295099331.

Step 4. Get the number of students that are in ninth grade at Thomas High School.
Total number of students in 9th grade at Thomas High School is 461. Which is 1.06% 9th grade students from 39,170 students.

Step 5. Subtract the number of students that are in ninth grade at Thomas High School from the total student count to get the new total student count.

![THS_9_count](THS_9_count.png)

39,170 - 38,709 = 38,709

- How is the district summary affected?



- How is the school summary affected?

![the_school_summary](the_school_summary.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


- How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade


    - Scores by school spending


    - Scores by school size


    - Scores by school type





3. Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.