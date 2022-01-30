# School District Analysis

## Project Overview
The school board has requested analysis to be done on the city schools standardized test scores for reading and math. They will use this analysis to make decisions regarding the school budgets and priorities.

The calculations required included:
1. Average math and reading scores
2. The percentage of students passing math
3. The percentage of students passing reading
4. The overall percentage of students passing both math and reading

These metrics were presented in the following ways:
1. Summarized at the district level with the count of schools, total students, and total budget
2. Calculated at a per school level with the addition of a per student budget

Using these calculations and presentations, the data was sorted to provide the best and worst performing schools based on overall passing rate.  The scores were also analyzed by grade level for each school, grouped by spending, grouped by school size, and by school type.

The school board notified us that there was evidence of academic dishonesty specifically in the Thomas High School 9th grade students.  These scores were replaced and the analysis was redone to analyze the difference.

## Resources
- Data source: students_complete.csv, schools_complete
- Software: Python 3.7.11, Jupyter notebook 6.4.6

## School District Results
- District Summary: The school district summary wasn't materially affected, but changes did occur as seen in the screenshots below. All score related metrics did trend lower, except for Average Reading Score, across the district.
    - Original analysis ![Original](/Resources/district_summary_original.png)
    - Updated analysis ![Updated](/Resources/district_summary_new.png)
- School Summary: At the individual school level the scores only change for Thomas High School.  The average math scores decreased slightly while the average reading scores increase by roughly the same margin.  The percentage passing scores for math, reading, and overall each decreased, but the decreases were minor at less than 0.5% for each.  Details are in the following screenshots.
    - Original analysis ![Original](/Resources/thomas_summary_original.png)
    - Updated analysis ![Updated](/Resources/thomas_summary_new.png) 
- School Comparison:  Replacing the scores didn't impact the ranking of the schools within the district.  Thomas High School was the 2nd best performing school in the district before and after the change when being ranked by overall passing percentage.
- Math and Reading scores by grade: Math and reading scores by grade was not impacted other than replacing the number in Thomas High School 9th grade with NaN.  All other schools and grade levels remained the same.
- Scores by School Spending:
    - Original analysis ![Original](/Resources/spending_original.png)
    - Updated analysis ![Updated](/Resources/spending_new.png) 
- Scores by School Size
    - Original analysis ![Original](/Resources/size_original.png)
    - Updated analysis ![Updated](/Resources/size_new.png) 
- Scores by School Type
    - Original analysis ![Original](/Resources/type_original.png)
    - Updated analysis ![Updated](/Resources/type_new.png) 

## School District Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.