# School_District_Analysis

## Overview:

The purpose of this project was to analyze standardized test scores in a school district. This analysis will inform discussions and strategic decisions within schools and the district. 

Data from 15 schools and 39,170 students was provided. School data included school names, sizes and budgets. Student data included student names, grade levels, school attended, and reading and math scores. The data was analyzed using python and the pandas library in jupyter notebook.

District workers desired the following output tables:
- district key metrics
- key metrics for each school
- top and bottom 5 performing schools
- average math and reading scores by students in each grade level at each school
- school performance based on budget per student
- school performance based on school size
- school performance based on type of school 

After performing the initial analysis, 9th grade reading and math scores from Thomas High School were determined to be altered and were thrown out. The analysis was again performed, and the results below describe how the data was affected after removing Thomas High School 9th grade reading and math scores. The number of students removed from the analysis was 461, which was 1.18% of the total student population (39,170 students). 

## Results:

1. How was the district summary affected?
    
    Reading and math scores went down very slightly in the district summary. For example, the percent of students passing both reading and math (% overall passing) went from 65.0 to 64.9. Differences in other scores were between 0.0-0.2. 

    Before District Analysis:

    ![before district summary](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/before_district_summary.png)

    After District Analysis:

    ![after district summary](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/after_district_summary.png)

2. How was the school summary affected?
    
    The only difference in this table was the scores in the row for Thomas High School. In this row, all scores but one (average reading score) decreased slightly. For example, the percent of students passing both reading and math went from 90.94 to 90.63. Average reading score did increase slightly, from 83.85 to 83.90. 

    Before School Summary:

    ![before school summary](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/before_school_summary.png)

    After School Summary:

    ![after school summary](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/after_school_summary.png)

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    
    Thomas High School's performance relative to other schools did not change by removing 9th grade scores. They remained 2nd out of the 15 schools when comparing the percent of students passing both reading and math. 

    Top 5 Schools:

    ![top 5 schools](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/top_5_schools.png)

4. How does replacing the ninth-grade scores affect math and reading scores by grade
    
    These scores were not impacted at all. The only difference in these tables were the missing values in the Thomas High School 9th grade cells. 
    
    Math Scores:

    ![after math scores](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/after_math_scores.png)

5. How does replacing the ninth-grade scores affect scores by school spending
    
    Scores in this table remained the same. Scores were only divided up between four spending range categories and were rounded, so there was likely not enough of a difference to change the scores. 

    School Spending:

    ![before school spending](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/before_school_spending.png)

6. How does replacing the ninth-grade scores affect scores by school size
    
    Scores in this table remained the same. Scores were only divided up between three categories (small, medium, and large schools) and were rounded, so there was likely not enough of a difference to change the scores. 

    School Size:

    ![before school size](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/before_school_size.png)

7. How does replacing the ninth-grade scores affect scores by school type
    
    Scores in this table remained the same. Scores were only divided up between two categories (charter and district schools) and were rounded, so there was likely not enough of a difference to change the scores. 

    School Type:
    
    ![before school type](https://github.com/emariecovey/School_District_Analysis/blob/main/Resources/Analysis%20Tables/before_school_type.png)

## Summary: 

Some things did not change when the 9th grade Thomas High School scores were removed from the analysis:
 1. Thomas High School's standing compared to other schools did not change. 
 2. Tables comparing scores and school spending, scores and school size, and scores and school type were not affected. 
 3. Scores by grade were not impacted, with the exception of the Thomas 9th grade scores being missing values. 

Some scores did change when 9th grade Thomas High School scores were removed from the analysis: 
1. Overall passing percentage at Thomas High School dropped from 90.95 to 90.63%
2. Average math score at Thomas High School dropped from 83.4 to 83.35
3. The school district summary overall passing percentage went from 65 to 64.9%
4. The school district summary average math score went from 79.0 to 78.9.