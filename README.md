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
- District Summary: The school district summary wasn't materially affected, but changes did occur as seen in the screenshots below.
    - Original analysis ![Original](/Resources/district_summary_original.png)
    - Updated analysis ![Updated](/Resources/district_summary_new.png)
- school summary
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
    - Math and Reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type

## School District Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.