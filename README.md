# School District Analysis

## Overview of the School District Analysis

### Purpose
After submitting our initial analysis, the school board notified the team that they suspected academic dishonesty in Thomas High School's 9th grade class. We have been tasked to replace all math and reading scores for this class with NaNs. Upon doing so, we will present our findings and determine how this class's scores skewed the data.

## Results:
  - How is the district summary affected?
    - Prior to removing Thomas High School's 9th grade class, the overall passing percentage of all schools was listed as 65.17% in the Module. By school type, district schools had a 54% overall passing rate while charter schools had a 90% overall passing rate. After removing the class, the overall passing rate for all 15 schools went down slightly to 64.9%. The vast majority of the data overlap with the same number of passing students. The main difference is in the 461 students from the freshmen class of Thomas High Schoool, which would reduce the total number of students, thereby reducing the percentagea s well.
  
  - How is the school summary affected?
    - The percentage of students at Thomas High School increases dramatically after dropping the 9th grade class. You can see the comparison directly below:
  - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - After replacing the ninth graders' math and reading scores at Thomas High School, the overall percentage at Thomas increases dramatically. As such, Thomas High School ranks among the top schools in the district after removing the ninth graders' scores.
  - How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - By grade, the only change is among the ninth graders. The other classes will remain the same.
  - Scores by school spending
    - Relatively little change. Removing the 461 students in one high school has little effect on the data that is grouped by school spending.
  - Scores by school size
    - Larger schools on average perform worse. However the 461 students have little effect on the data that is grouped by school size
  - Scores by school type
    - Charter schools perform better than disctrict schools. Removing 461 students had little effect on data grouped by school type.

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
  - Thomas High Schools's math, reading, and overall percentage passing rates increased dramatically after removing 9th graders. 
  - Most of the other data listed by different categories, including school type, school size, and school spending, was not affected by the removal of those 461 students. In a dataset of tens of thousands of students, 461 was not enough to move the needle. 
  - The percentage of overall passing rates across all 15 schools increased. 
  - While the changes can be seen on the individual school at Thomas, there is not much of a difference across all schools.
