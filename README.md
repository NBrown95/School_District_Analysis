# School District Analysis

## Overview of Project

For this project, we are analyzing school district data to determine standardized test scores per school. Then, we analyze if these scores may be correlated with school size, school type, or the budget per student. However, for one high school, there was evidence of academic dishonesty. So, for all the ninth grader scores for Thomas High School, these scores may not be accurate and therefore, we must exclude them from the analysis. 

So, we replaced all the scores for the ninth grade at Thomas High School with “NaN” and completed the rest of the analysis excluding these scores.

## Results

We found that there were 461 9th graders at Thomas High School. After replacing their reading and math scores, the summary of the analysis was changed in multiple ways. The following list discusses how dropping those scores to the analysis affected the metrics.

* The number of students with passing math scores dropped by 431
*	The number of students with passing reading scores dropped by 452 as seen in the following images

With 9th graders from Thomas High School:

![Screenshot 1](https://user-images.githubusercontent.com/81498850/118349616-4ca9be00-b517-11eb-9732-f70b90ad6590.png)

Without 9th graders from Thomas High School:

![Screenshot 2](https://user-images.githubusercontent.com/81498850/118349627-677c3280-b517-11eb-99f3-c3739d33cadc.png)

*	The percentage of students with passing math scores dropped by 0.22%
*	The percentage of students with passing reading scores dropped by 0.14% as seen in the following images

With 9th graders from Thomas High School:

![Screenshot 3](https://user-images.githubusercontent.com/81498850/118349673-a27e6600-b517-11eb-91fa-b987c529c2fd.png)

Without 9th graders from Thomas High School:

![Screenshot 4](https://user-images.githubusercontent.com/81498850/118349693-bf1a9e00-b517-11eb-955e-9c766822e415.png)

*	The overall passing percentage dropped by 0.32%

With 9th graders from Thomas High School:

![Screenshot 5](https://user-images.githubusercontent.com/81498850/118349707-e1acb700-b517-11eb-8c27-eeb56b913c8d.png)

Without 9th graders from Thomas High School:

![Screenshot 6](https://user-images.githubusercontent.com/81498850/118349721-fbe69500-b517-11eb-8960-fdaef33c0354.png)

The reason the percentages did not change much is because the total number of students also declined due to the 461 scores that were removed from the calculation.

*	Thomas High School was 25 percentage points away from the top 5 schools in overall passing percentages before the 9th grade scores were excluded. Only counting the scores from 10th through 12th grade placed them second overall in overall passing percentages. The top five performing schools can be seen in the following images

With 9th graders from Thomas High School:

![Screenshot 7](https://user-images.githubusercontent.com/81498850/118349746-34866e80-b518-11eb-8734-39181f417483.png)

Without 9th graders from Thomas High School:

![Screenshot 8](https://user-images.githubusercontent.com/81498850/118349767-5253d380-b518-11eb-843c-41e45420c899.png)

*	As seen in the following images, the average percentage of 9th graders who had passing math and reading scores slightly decreased after Thomas High School was excluded.

With 9th graders from Thomas High School:

![Screenshot 9](https://user-images.githubusercontent.com/81498850/118349785-77484680-b518-11eb-9b97-4727e67efcfb.png)

Without 9th graders from Thomas High School:

![Screenshot 10](https://user-images.githubusercontent.com/81498850/118349795-8cbd7080-b518-11eb-98b8-2aaec459c9b3.png)

*	Because the overall percentages of reading scores, math scores, and overall passing scores were elevated after the exclusion of 9th graders at Thomas High School, all of the bins that Thomas High School was placed in had an elevated percentage rate. 
*	For instance, medium sized schools saw an increase in percentages, charter type schools saw an increase in percentages, and schools that spend $630-644 per student saw an increase in percentages across the board because of the changes in analysis.

## Summary

### Four Changes

As seen in the previous list, there were several changes that occurred now that the 9th graders reading and math scores were excluded from the analysis. Most notably, the percentage of students who had passing reading scores, passing math scores, and overall passing scores increased dramatically. This change made Thomas High School the second top performing school based on overall passing percentages. Removing the 9th graders scores also slightly altered the percentages of every metric as well. These changes also increased the performance of medium sized charter type schools that spend between $630 and $644 per student. 
