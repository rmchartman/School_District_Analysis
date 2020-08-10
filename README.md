# School District Analysis
## Overview
The school board has determined that there is evidence of academic dishonesty in the students_complete.csv file with specific concerns about the 9th grade math and reading scores for Thomas High School. To determine the full extent of the impact on the data analysis the academic dishonesty may have had, the school district requested a comparison analysis between the data as is, and with the suspicious scores changed to NaN as to remove impact from the analysis. The resulst and summary below detail the difference the academic dishonesty had on the various summaries for the school district. 

## Results

### District Summary
Below is the District Summary, the first without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. The academic dishonesty was significant enough to raise the passing percentages by one percent for math, reading, and overall. There was also a slight increase in the average reading score. However, the effects of the adjustment for Thomas High School will be more evident when looking at more specific analyses, as detiled below.

Original District Summary without adjustment to 9th grade Thomas High School scores.
![District_Analysis_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/District_Analysis_module.png)

Updated District Summary with adjustment to 9th grade Thomas High School scores.
![District_Analysis_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/District_Analysis_challenge.png)

### School Summary
Below is the School Summary, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. The academic dishonesty was significant enough to raise the passing percentages by 26 percent for math, 27 percent for reading, and 26 percent for overall passing. There was also a slight decrease in the average reading score. This is the largest disparity between the two comparision tables out of all of the sections of analysis.

Original School Summary without adjustment to 9th grade Thomas High School scores.
![School_Summary_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/School_Summary_module.png)

Updated School Summary with adjustment to 9th grade Thomas High School scores.
![School_Summary_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/School_Summary_challenge.png)

### Top Five Performing Schools
Below are the Top Five Performing Schools, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. The academic dishonesty was significant enough to move Thomas High School into 4th place due to the overall passing rate increasing to 91% with the 9th grade scores included.

Based on overall passing rate, these are the top five schools in the district.

Original Top Five Performing Schools without adjustment to 9th grade Thomas High School scores.
![Top_5_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Top_5_module.png)

Updated Top Five Performing Schools with adjustment to 9th grade Thomas High School scores.
![Top_5_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Top_5_challenge.png)

### Bottom Five Performing Schools
Below are the Bottom Five Performing Schools, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. There is no change between the two tables as Thomas High School is still ranked 7th without the 9th grade scores, excluding the school from the bottom five. 

Based on overall passing rate, these are the bottom five schools in the district.

Original Bottom Five Performing Schools without adjustment to 9th grade Thomas High School scores.
![Bottom_5_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Bottom_5_module.png)

Updated Bottom Five Performing Schools with adjustment to 9th grade Thomas High School scores.
![Bottom_5_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Bottom_5_challenge.png)

### Avergage Math Score by School and Grade Level
Below is the Avergage Math Score by School and Grade Level, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. In order to adjust the scores for Thomas High School, the scores for 9th grade math were replaced with NaN (null) to be excluded from the analysis. This can be seen as there is no average score for 9th grade at Thomas High School in the second table.

![Avg_Math_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Avg_Math_module.png)  ![Avg_Math_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Avg_Math_challenge.png)

### Avergage Reading Score by School and Grade Level
Below is the Avergage Reading Score by School and Grade Level, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. In order to adjust the scores for Thomas High School, the scores for 9th grade reading were replaced with NaN (null) to be excluded from the analysis. This can be seen as there is no average score for 9th grade at Thomas High School in the second table.

![Avg_Reading_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Avg_Reading_module.png)  ![Avg_Reading_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Avg_Reading_challenge.png)

### Scores by School Spending Per Student
Below is the Scores by School Spending Per Student, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. The academic dishonesty was significant enough to raise the passing percentages by 6 percent for math, 7 percent for reading, and 7 percent for overall passing for the schools who have the budget to spend $630-644 per student.

Original Scores by School Spending Per Student without adjustment for 9th grade Thomas High School scores.
![Score_by_Spending_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Score_by_Spending_module.png)

Updated Scores by School Spending Per Student with adjustment to 9th grade Thomas High School scores.
![Score_by_Spending_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Score_by_Spending_challenge.png)

### Scores by School Size
Below is the Scores by School Size, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. The academic dishonesty was significant enough to raise the passing percentages by 8 percent for math, 6 percent for reading, and 6 percent for overall passing for medium sized schools.

Original Scores by School Size without adjustment for 9th grade Thomas High School scores.
![Score_by_Size_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Score_by_Size_module.png)

Updated Scores by School Size with adjustment to 9th grade Thomas High School scores.
![Score_by_Size_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Score_by_Size_challenge.png)

### Scores by School Type
Below is the Scores by School Type, the first table is without adjustment, the second with adjustment to the 9th grade scores at Thomas High School. The academic dishonesty was significant enough to raise the passing percentages by 4 percent for math, 4 percent for reading, and 3 percent for overall passing for charter schools.

Original Scores by School Type without adjustment for 9th grade Thomas High School scores.
![Score_by_Type_module.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Score_by_Type_module.png)

Updated Scores by School Type with adjustment to 9th grade Thomas High School scores.
![Score_by_Type_challenge.png](https://github.com/rmchartman/School_District_Analysis/blob/master/Resources/Score_by_Type_challenge.png)


## Summary
After the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, there were four major changes. The most noticible was that Thomas High School was no longer in the Top 5 Performing Schools based on overall passing percentage and pushed down to 7th place. The next was the change in percent of students at Thomas High School who passed reading, math, or both as these percentages decreased by over 25% each. Additionally, the comparision between charter schools and disctrict schools was altered to make charter schools look more on par to the the performance of other schools in the district. Last, the scores for budgets per student descreased, showing a more linear relationship between the more monney a school had and the average scores. Between the two, the correction to Thomas High School should be used as the primary analysis as the academic dishonesty largely skewed the data and results.  
