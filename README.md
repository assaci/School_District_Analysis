# School_District_Analysis

## Overview 

The PyCity school board wants to repeat analysis of the district information to support their decision of upholding state-testing standards after finding out that the grades from Thomas High School 9th graders were altered. 
The purpose of this project is to analysis information, student funding and standardized testing scores of all schools in the district and create a report to provide insight to schools’ trends and performance and assist school board and superintendent in making decision regarding schools’ budgets and priorities. 

Analysis

To help with the analysis we used data school district data below

| District' s Schools data | District Students' Data |
|--------------|---------------|                
|school_name   | Student ID    |
| type         | student_name  |
| size         | gender        |
| budget       | school_name   |
|              |reading_score  | 
|              | math_score    |

To provide a better inshight for the analysis and ensure data accuracy, we fisrt, replaced the 9th grade reading and math scores at Thomas High School with NaN while keeping the rest of the data intact. then we updated the following metrics:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type
- The scores by school size
- The scores by school size
- The scores by school type

## Results

### School District Analysis
PyCity school district is constituted of 2 schools's types : district and charter schools. It has 39,170 high school students. The total budget of the district is $24,649,428.00 , which are distributed between 15 high schools.  

![dist_summary_before](https://github.com/assaci/School_District_Analysis/blob/main/dist_summary_before.PNG?raw=true)

### District Summary

#### Before Replacing the 9th Grade scores

![dist_data](https://github.com/assaci/School_District_Analysis/blob/main/dist_data.PNG?raw=true)

### School Summary

#### After Replacing the 9th Grade scores


[dist_After](https://github.com/assaci/School_District_Analysis/blob/main/dist_After.PNG?raw=true)


When comparing the 2 data from District Summary, we see that Thomas High School the percentage for passing match score was 93.27% , the passing reading score was 97.30%, and overall passing was 90.94. The passing math score percentage for the entire district 75%,  reading score were 86% while overall passing percentage was 65%.

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

#### Before Replacing the 9th Grade scores

##### Math Scores Per Grade

![math_scores_bef](https://github.com/assaci/School_District_Analysis/blob/main/math_scores_bef.PNG?raw=true)

##### Reading Scores Per Grade

![reading_sco_bef](https://github.com/assaci/School_District_Analysis/blob/main/reading_sco_bef.PNG?raw=true)

#### After Replacing the 9th Grade scores

##### Math Scores Per Grade

![match_sc_after1](https://github.com/assaci/School_District_Analysis/blob/main/match_sc_after1.PNG?raw=true)

##### Reading Scores Per Grade

![math_scores_after](https://github.com/assaci/School_District_Analysis/blob/main/math_scores_after.PNG?raw=true)


### High and Low Performing Schools

#### Before Replacing the 9th Grade scores

![top_school](https://github.com/assaci/School_District_Analysis/blob/main/top_school.PNG?raw=true)

![bottom_schools](https://github.com/assaci/School_District_Analysis/blob/main/bottom_schools.PNG?raw=true)

#### After Replacing the 9th Grade scores

![top_schools_after](https://github.com/assaci/School_District_Analysis/blob/main/top_schools_after.PNG?raw=true)

![bottom_schools_after](https://github.com/assaci/School_District_Analysis/blob/main/bottom_schools_after.PNG?raw=true)

### Scores by school spending

#### Before Replacing the 9th Grade scores

![Spending_bef](https://github.com/assaci/School_District_Analysis/blob/main/Spending_bef.PNG?raw=true)

#### After Replacing the 9th Grade scores

![spen_after](https://github.com/assaci/School_District_Analysis/blob/main/spen_after.PNG?raw=true)


### Scores by school size

#### Before Replacing the 9th Grade scores

![size_bef](https://github.com/assaci/School_District_Analysis/blob/main/size_bef.PNG?raw=true)

#### After Replacing the 9th Grade scores

![size_after](https://github.com/assaci/School_District_Analysis/blob/main/size_after.PNG?raw=true)

### Scores by school type

There was no significant change to the scores by school types

#### Before Replacing the 9th Grade scores

![type_after](https://github.com/assaci/School_District_Analysis/blob/main/type_after.PNG?raw=true)

#### After Replacing the 9th Grade scores

![Type_bef](https://github.com/assaci/School_District_Analysis/blob/main/Type_bef.PNG?raw=true)

## Summary: 

Our Repors shows that after replacing Thomas High School 9th graters scores for math and reading, there was no significant change to the District Summary data.Even after updating the dataframe with new metrics from the school. The math and reading scores per school were not impacted with big margin  well as scores by spending, school size or type. 








