# School_District_Analysis
The school board has found, that students_complete.csv file shows academic dishonesty. Specifically, reading and math grades for Thomas High School for ninth graders seems to be altered. Therefore, school board decided to investigate in detail, to uphold state-testing standards. Maths and reading scores for Thomas High School are replaced with NaNs while keeping the rest of the data intact. After replacing the math and reading scores, school district analysis is performed to write up a report to describe how these changes affect the overall analysis.
This analysis will be used to make stretegic decisions upon school testing and passing criteria.


# Results
In the following, we will discuss the results of the above analysis; i.e, after removing all the scores for grade 9 students for Thomas High School: 
### How is the district summary affected?
Below are the screenshots of the District summary before and after the analysis was performed. It shows total population, budget, average scores and passing rates for the entire district. By comparing the total students column, we can see that 9th graders from Thomas High are 1.17% of the total student population.

Figure-1: Original District Summary![Original District Summary](https://github.com/FatimaJHussain/python_project/blob/main/original_district.png).
Figure-2: Revised District Summary ![Revised District Summary](https://github.com/FatimaJHussain/python_project/blob/main/revised_district.png).

### How is the school summary affected? 
only Thomas high high school was affected and overall passing was improved from 65% to 90%
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
only Thomas high high school was affected and overall passing was improved from 65% to 90%

### How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade
The Average Math Score drops by ___.
The Average Reading Score  ___.
The % Passing Math  ___.
The % Passing Reading  ___.
The % Overall Passing  ___.
* Scores by school spending

Changing scores of 9th grade didnot affect the school spending. Thomas High School remained in G2 and have spending ------

* Scores by school size
It didnot change as Thomas High scholl is in medium sized school and no scores changed in medium sized school (1000-2000)

* Scores by school type
There is no change in scores (by school type), when replaced by Naan

# Summary
Overall the discrepency of the scores impacted the entire analysis. The revised analysis would not be a true statement as we are not calculating the actual true student population for this district. Though the student count of 461 from 9th grade attending Thomas High is minimal compared to a total of 39,170 students; their true scores may still impact the results positively or negatively.

1. The performance for Thomas High individually situates them at the second place in the top 5 schools list. This may change if we had the actual results from the 9th grade. The results may put them in the bottom producing schools.

2. The performance results on each grade level may be impacted as well. Currently the results have the 9th grade per school performing at the same rate. Actual results may show Thomas High's 9th grade performing better or worse than the other schools.

3. Based on the performance the budget per student may change as well which will impact the decision for the school boards funding allocation. The true results may change the averages and the passing percentages, placing them in the next higher or lower bin of spending.

4. Once the true results from Thomas High's 9th grade is received, and if the averages are low, this may pull the overall passing rate down for the school itself, trickling down and change the results of the School Type summary. We may see District schools out performing the Charter schools.

Following are the major changes in the school district analysis after reading and math scores have been replaced:
* Thomas High School ---overall passing was improved from 65% to 90%
* Average math score was drop
*
