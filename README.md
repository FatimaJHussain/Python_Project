# School_District_Analysis
The school board has found, that students_complete.csv file shows academic dishonesty. Specifically, reading and math grades for Thomas High School for ninth graders seems to be altered. Therefore, school board decided to investigate in detail, to uphold state-testing standards. Maths and reading scores for Thomas High School are replaced with NaNs while keeping the rest of the data intact. After replacing the math and reading scores, school district analysis is performed to write up a report to describe how these changes affect the overall analysis.
This analysis will be used to make stretegic decisions upon school testing and passing criteria.


# Results
In the following, we will discuss the results of the above analysis; i.e, after removing all the scores for grade 9 students for Thomas High School: 
### How is the district summary affected?
Below are the screenshots of the District summary before and after the analysis was performed. It shows total population, budget, average scores and passing rates for the entire district. By comparing the total students column, we can see that 9th graders from Thomas High are 1.17% of the total student population.
* Average math score dropped by 0.1 points
* Average readinhg score doesnot change
* % Passing math decreased by 0.2 points
* % Passing reading decreased by 0.3 points
* Overall % passing decreased by 0.1 points

Figure-1: Original District Summary![Original District Summary](https://github.com/FatimaJHussain/python_project/blob/main/original_district.png).
Figure-2: Revised District Summary ![Revised District Summary](https://github.com/FatimaJHussain/python_project/blob/main/revised_district.png).

### How is the school summary affected? 
Only Thomas high high school was affected and overall passing was improved from 65% to 90%, as shown below: 
There are a total of 1635 students at Thomas High School. 73% of the students are from grade 10th to 12th. Once we eliminated the grade 9 scores, the percentage of students passing each subject or both together dropped by an average of 26%, since the calculation was still taking the total number students into account.

Figure-3: Original Per School Summary![Original District Summary](https://github.com/FatimaJHussain/python_project/blob/main/original_perschool_summary.png).

However, after recalculating with only the number of students with scores at Thomas High School, the passing percentages was barely impacted by an average of .37%. Below are the screenshot of the summaries with the grade 9 as student count but no scores, and without the grade 9 students completely out of the calculation.

Figure-4: Revised per School Summary without Grade 9 Scores ![Revised District Summary](https://github.com/FatimaJHussain/python_project/blob/main/revised_perschool.png).


Figure-5: Revised per School Summary without Grade 9 Scores ![Revised District Summary](https://github.com/FatimaJHussain/python_project/blob/main/revised+perschool1.png).

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Only Thomas high high school was affected and overall passing was improved from 65% to 90%. After the revised analysis with the 9th grade scores replaced the overall passing percentage for the school was at 65%, it would have placed Thomas High School within the bottom 10 schools, placing them at the 8th position. However once the scores were replaced and taking the grade 9's out of the equation, the school falls within the top 5 performers, placed 2nd on the list as the original analysis.

Figure-6: Top Five School List![Revised District Summary](https://github.com/FatimaJHussain/python_project/blob/main/top_5list.png).


### How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade: The math and reading scores by grade tables didn't change since the grouping was done by each school. Even without grouping, the effect would have been minimal since the 9th graders at Thomas High School amount to less than half a percent of the total 9th grade population in the district.

* Scores by school spending: Changing scores of 9th grade didnot affect the school spending. 
* Scores by school size:It didnot change. 
* Scores by school type: There is no change in scores (by school type), when reassessment is done.

# Summary

Discrepency of the scores have impacted the analysis in a way that Thomas High School has moved to top 5 schools. Although, number of students=461 of 9th grade attending Thomas High is very less compared to the total number of students=39,170. Invidual scores will affect them positively. Following are the major changes in the school district analysis after reading and math scores have been replaced:
1. Thomas High individually get second place in the top 5 schools list. Originally, it was placed in the bottom performing schools.

2. Grade level performance is also affected. Currently the results have the 9th grade per school performing at the same rate. Actual results may show Thomas High's 9th grade performing better or worse than the other schools.

3. Budget allocation will be also affected based on the performance of each school. As this affects the  decision for the school boards funding allocation. Revised analysis have changed the averages and the passing percentages, placing them in the next higher or lower bin of spending.

4. Once the true results from Thomas High's 9th grade is received, and if the averages are low, this may pull the overall passing rate down for the school itself, trickling down and change the results of the School Type summary. We may see District schools out performing the Charter schools.

