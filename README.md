# School-District-Analysis

## Overview (of the school district analysis)
In this module, we analyzed the performance of high school student's math and reading scores at a certain school district to see if there are any relationships between passing scores with school funding, size and type. We later learn that at a specific school, Thomas High School, there is academic dishonesty in the 9th grader's math and reading scores. We will need to omit these student's scores and re-evaluate these numbers and correlations.

### Purpose
The purpose of this is to find the new math, reading and overall passing grade percentages at Thomas High School after omitting all ninth grader's test scores. We will update Thomas High School's math and reading passing rates and overall school summary analysis. Additionally, taking these new numbers and see how it will affect the school district analysis.

## Results 

- How is the district summary affected?

The district summary is not affected significantlly. The average math score was 78.9853 and now 78.9305 after removing the ninth grade scores. The average reading score also did not change too much from 81.8778 to 81.8557. 

- How is the school summary affected?

While all the other schools remained the same. Thomas High School has NaN inplace for both ninth grader's math and reading scores. The analysis only took into account of the 10th-12th graders in Thomas High School. It's percentages of students passing went up. The percentage of students passing math is 93.19%. The percentage of students passing reading is 97.02%. The overall percentage of students passing is 90.63. Below is a dataframe showing each school's summary. 

![Per School Summary (After)](https://github.com/sydney-chen95/School-District-Analysis/blob/main/DataFrames/Per%20School%20Summary%20(After).png?raw=true)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Before replacing the ninth grader's math and reading scores, Thomas High School had an overall passing percentage of 65.08%. After omitting these scores, Thomas High School become one of the top performing schools with an overall passing percentage of 90.63%. As seen below, we can see that Thomas High School is ranked number 2.

![Top Performing Schools](https://github.com/sydney-chen95/School-District-Analysis/blob/main/DataFrames/Top%20Performing%20Schools.png?raw=true)

- How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade
    
    Every grade except for ninth grade stays the same. The ninth grade scores for Thomas High School remains NaN since there is no value for these students. 
  
    - Scores by school spending
    
    There is no significant change in scores by school spending.
  
    - Scores by school size
    
    There is no significant change in scores by school size.
  
    - Scores by school type
    
    It changed the averages and passing rates for Charter schools since Thomas High School is a Charter school. However, there is no significant change in these numbers.
  
## Summary 
After omitting the Thomas High School's ninth grader math and reading scores, we did our analysis again to see if it will affect the original analysis. We find out that when we replaced the scores with NaN, the passing math percentage, passing reading percentage, and overall passing percentage changed significantly. This is due to the fact that the total students at Thomas High School is 1635 but we omitted the ninth graders so our new analysis only took account for 1174 students ranging from 10th-12th grade for Thomas High School. This ended up boosting Thomas High School to being one of the top performing schools. Overall, the average math and reading scores changed but only slightly. The affect also impacted Charter schools since Thomas High School is a Charter school but insignificantly. 

