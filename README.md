# School District Analysis

## Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:
* Deliverable 1: Replace ninth-grade reading and math scores
* Deliverable 2: Repeat the school district analysis
* Deliverable 3: A written report for the school district analysis (README.md)

## Results
  1. How is the district summary affected?
  ![1](https://user-images.githubusercontent.com/94920551/166074763-7aefe316-83bb-48a0-8379-8e13b0d71bd6.png)
    * All scores changed by less than 0.5 percentage points(or changed by less than 0.5%) - there is no changes on school or student count.
    
  2. How is the school summary affected?
  ![1](https://user-images.githubusercontent.com/94920551/166074887-90066dae-8a0f-404d-b527-1b739bfa8773.png)
    * The ranks did not change. The Thomas High School's scores changed by less than 1%.
    
  3. Top 5 performing schools:
  ![1](https://user-images.githubusercontent.com/94920551/166074977-6d6a8362-7fdb-48fd-aec7-a4af70f457df.png)

  4. Bottom 5 performing schools:
  ![1](https://user-images.githubusercontent.com/94920551/166075012-1f5e35df-c2e3-451f-b8f6-eb8fcc1f4f43.png)

  5. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
        There was minimal change in math and reading test scores, therefore there was no significant change in school performance relative to the other schools.
  6. How does replacing the ninth-grade scores affect the following:
      * Math and reading scores by grade
          We replaced 9th grade test scores with "NaN" which caused minimal change for ninth graders in all the schools in the district. There was a change of -0.1% for reading and -0.2% for math. 
       * Scores by school spending
            Scores by school spending was not affected when replacing 9th graders' scores with "NaN".
        * Scores by school size
            Scores by school size was not affected when replacing 9th graders' scores with "NaN".
        * Scores by school type
            Scores by school type was not affected when replacing 9th graders' scores with "NaN".

## Summary
- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
    1. Replaced the ninth graders' scores with NaN, Thomas High School's overall passing percentages and average scores changes abruptly.
    2. The district has also had its average math and reading scores decrease, as well as the overall passing percentage for students.
    3. Also, Thomas High School lost its ranking as a top five school within this District.
    4. After updating the total student counts and exclude it to the Thomas High School ninth graders and removing their scores from the school data, Thomas High              School again reach to its high average scores and gain its position as the number two school in the District.
