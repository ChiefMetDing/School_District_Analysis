# School_District_Analysis
Data Analytics M4
## Overview
This School District Analysis provides:

- A high-level summary of the district’s key metrics and overview for each school;
 
- Top 5 and bottom 5 performing schools by overall passing rate;

- Average math and reading scores received by students in each grade level at each school;

- School performance based on the budget per student, the school size and the type of school.

Please keep note: reading and math grades for Thomas High School ninth graders are not considered in this analysis due to evidence of academic dishonesty. Passing score for math and reading is 70.

The result of the analysis shows that:

- The top three best performing schools in terms of overall passing rate are: Cabrera High school, Thomas High school and Griffin High school.

- Schools with lower budget per student, having fewer students and in charter type have an overall better performance.

## Results
### Data Acquisition
The data used in this analysis is read from file “schools_complete.csv”. Prior to analysis, students’ name data has been cleaned by removing unnecessary prefixes and suffixes. The removal list is: `["Dr. ", "Mr. ","Ms. ", "Mrs. ", "Miss ", " MD", " DDS", " DVM", " PhD"]`.

All ninth grades’ math and reading scores are replaced by `NaN` to facilitate analysis. 

In this analysis, total number of students count includes the number of ninth graders in Thomas High school. However, when calculating Thomas High school average math and reading average scores and passing rates, these students are not included in the calculations.

### District Summary and School Summary
As shown in the table below, data of 39,170 students from 15 schools in the district is analyzed. The total budget for the entire district is around $24.65 million. The average math score is 78.9 with 74.8% passing rate, and reading score is averaged at 81.9 with 85.7% passing rate. The overall passing rate is 64.9%.

Top 5 and bottom 5 performing schools are listed below. Cabrera High school is the best performing school among all 15 schools in terms of students overall passing on both math and reading. At Cabrera High school, students’ average math score is 83.1 with 94.1% passing rate, and average reading score is at 84.0 with 97.0% passing rate. The overall passing rate is at as high as 91.3%.

Without counting students’ scores in ninth grade at Thomas High school, the overall performance of Thomas High school still ranks the second place in the district. The overall passing rate is at 90.6%. More specifically, the average math score is 83.4 and reading score is 83.9.

The worst performing school in the district is Rodriguez High School, at which students only have a 53.0% overall passing rate. The average math score from Rodriguez school is 76.8% with only 66.4% passing rate. The average reading score is 80.7 with 80.2% passing rate.

### Students’ Scores in Each Grade Level at Each School
The table below summarized students’ average math and reading scores at each school. No clear trend is observed on neither math nor reading as a function of grades. More data interpretation could be done, but is not covered in this analysis.

### School Performance Review
#### Budget per Student
As shown in the table, with the increase of spending per student, the overall passing decreases with the decreasing of average scores and passing rates on math and reading. For schools having $645-775 budget per student, the overall passing rate is as low as 53.5%.
#### School Size 
The table below shows that, overall, smaller size schools perform better than larger size schools. More specifically, schools with less than 2000 students, the overall passing rate is passing 90%, while students in schools larger than 3000, only have 53.7% passing rate.
#### School Type
Clearly shown in the table, charter schools performs better than district schools. The average overall passing rate at charter schools is higher than 90%, but the average overall passing rate at district schools is at 53.7%
## Summary
The analysis shows that the top three best performing schools in terms of overall passing rate are: Cabrera High school, Thomas High school and Griffin High school. The worst performing school is Rodriguez High school. 

Further analysis on the schools performance as a function of budget per student, school size and school type shows that, schools with lower budget per student, having fewer students and in charter type have an overall better performance. 

In terms of changes caused by replacing Thomas High school’s ninth graders’ math and reading scores, the overall passing rate in Thomas High school decreased from 91.0% to 90.6%. More specifically, the average math score decreased from 83.42 to 83.35 with a passing rate decrease from 93.3% to 93.2%. However, the average reading score increased from 83.85 to 83.90, but reading passing rate decreased from 97.31% to 97.02%. In general, the overall performance rating for Thomas High school is barely affected. Thomas High school still ranks the second best performing school in terms of overall passing rate.










