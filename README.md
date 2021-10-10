# School District Analysis

## Analysis Overview 
We were asked by the district chief data scientist to analyze standardized test data and funding for her school district. The goal being to review trends and identify patterns to help drive decisions for the district and individual schools. After our initial analysis, it was brought to our attention that there was some academic dishonesty from one of the schools within the district. To account for that and keep our analysis accurate, we needed to adjust the data provided for the 9th grade at Thomas High School, and rerun our analysis. 

We kept the student count and funding the same for Thomas school district so as to not affect the amount of funding per student and other related data, but we removed all of their testing scores, to eliminate the impact on the average and counts of those tests for the school. The following are the results of our analysis. 


## Analysis Results

These results represent the district and school data, with the 9th grade reading and math scores removed from the data set. What we discovered from removing those results was: 


* At the District level we saw a slight decrease in the average math score, average percent passing math, average percent passing reading and % overall passing as shown below. 

<br>

Original District Summary
![Original District Summary](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Original_District_Summary.png) 

Revised District Summary
![Revised District Summary](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Revised_District_Summary.png)


* At the school summary level for Thomas High School - we saw a slight decrease in the same areas as thes district saw, lower average math score, average percent passing math, average percent passing reading and % overall passing as shown below. 

<br>
**Original School Summary**
![Original School Summary](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Original_THS_School_Summary.png) 

**Revised School Summary**
![Revised School Summary](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Revised_THS_School_Summary.png)


* In relation to other schools testing performance, removing the altered scores for Thomas High School had very little effect on the results as far as how they compared to other schools. They remained as the second top performing school based on overall passing score even after removing the ninth grade results. Below I've analyzed specifically how removing the altered grades affected Scores by grade, school spending, school size and school type. 

<br>

* **Math and reading scores by grade** - Overall the scores by grade were not affected, with the exception of removing the 9th grade reading and math scores for Thomas High School students as shown below. 

<br>
Revised Math Scores By Grade
![Revised Math Scores](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Revised_Math_Scores_Grade.png)

Revised Reading Scores By Grade 
![Revised Reading Scores](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Scores_Reading_Grade.png)

* **Scores by school spending** - Replacing the scores did not affect the per capita spending per school as evidenced by comparing the original analysis results with the revised analysis results. 
<br>

Original Scores by Per Capita Spending ![Original Scores by Spending](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Original_PerCapita_Spending.png)
Revised Scores by Per Capita Spending ![Revised Scores by Spending](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Revised_PerCapita_Spending.png)

* **Scores by school size** - Similar to the scores by school spending, the school size results were not affected by the removal of the reading & math scores for the Thomas High School 9th graders. 
<br>

Original Scores by School Size ![Original Scores by School Size](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Original_Scores_Size.png)
Revised Scores by School Size ![Revised Scores by School Size](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Revised_Scores_Size.png)

* **Scores by school type**
Scores by school type also was not affected by the grade removal and re-analysis. 

<br>
Original Scores by School Type ![Original Scores by School Type](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Original_Scores_Type.png)
Revised Scores by School Type ![Revised Scores by School Type](https://github.com/jmmadson/School_District_Analysis/blob/master/Resources/Revised_Scores_Type.png)


## Analysis Summary 
After we replaced the math and reading scores for the ninth graders at Thomas High School, we saw very little change in the results of our analysis. The things that changed were that the average reading and math score went down slightly, as did the percentage passing for math, reading and overall for both the school and the school and at the district level. 

While there were changes, the results having moved so little by removing the altered scores, means that the school district can continue forward with decisions based on the data provided. Those results showed that 
* Charter schools performed higher in reading, math and overall percentage of passing students than district schools
* Small and Medium sized schools also performed higher than the larger schools in all areas
* Spending more per student did not correlate to higher test results. In fact the schools with the smallest per capita spending performed the highest. 

