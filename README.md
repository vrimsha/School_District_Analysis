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
- How is the district summary affected?



- How is the school summary affected?


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


- How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade


    - Scores by school spending


    - Scores by school size


    - Scores by school type





3. Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.