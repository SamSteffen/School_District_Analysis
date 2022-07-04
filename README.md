# School_District_Analysis
An analysis of student funding and the relationship to standardized test score outcomes using Python, Jupyter Notebooks and Pandas.

# Overview 
The purpose of this analysis is to determine the relationship between funding and student performance outcomes in math and reading for a school district containing 15 high schools. 

Upon completion of an initial analysis of the school district data, the findings were as follows:

- Total number of students : 39,170
- Total number of schools : 15
- Total budget : $24,649,428
- Average math score : 79.0
- Average reading score : 81.9
- Percentage of students who passed math : 75%
- Percentage of students who passed reading : 86% 
- Overall passing percentage : 65%

- The initial analysis performed upon each school in the district showed that the top five highest-performing schools based on the highest % Overall Passing grades in math and reading were charter schools with a low student population. Conversely, the lowest-performing schools were those with a high student population.

- The initial analysis also found that for test scores based on funding per student, schools with the least amount of funding performed consistently better than those with more funding.

- The initial analysis of test scores based on school size revealed that medium-sized schools performed best of the school population sizes, and did better than schools with small populations by a very narrow margin.

Following the discovery that reading and math scores by ninth graders at Thomas High School were to be discounted due to academic dishonesty, the school district analysis was repeated, with these scores omitted from the data. The results of this second analysis are explained below.

# Results: 
The second anaylsis of the school district data with the math and reading scores of 9th graders at Thomas High School omitted affected our data in the following ways:

<img width="566" alt="image" src="https://user-images.githubusercontent.com/104729703/177062469-140d9cfc-09fc-402d-836e-a9018ac6a436.png">

<img width="563" alt="Refactored_District_Summary" src="https://user-images.githubusercontent.com/104729703/177062406-2d7c48af-bce4-407e-82fb-58a40380b30a.png">
- The tables above represent the two school district summaries, the first with the Thomas High School ninth grade scores included, the second without. The comparison reveals that the omission of Thomas High School ninth grade math and reading scores affects the overall district data hardly at all. The size of the student population remains the same becuase the students are still included despite their scores being omitted, but the overall passing grades in math and reading decline by only a tenth of a percent. 

<img width="193" alt="image" src="https://user-images.githubusercontent.com/104729703/177065453-6de9d14e-29a1-4715-b5a6-5bd2a4e93dd9.png"> <img width="194" alt="image" src="https://user-images.githubusercontent.com/104729703/177067184-7d7cdd52-7aad-4ddd-a145-6cf8e30334ae.png">

- The impact of the omission of Thomas High School ninth graders' math and reading scores from the school data is more dramatic, especially for the math scores. While the original school comparison (pictured above, left) showed a 97% passing grade for Thomas High School students in reading, the new average for Thomas High School with the freshman scores omitted (pictured above, right) is roughly 70%, a considerable decrease. Math scores also decrease with the omission of the freshman data, from 93% passing to 66% passing, as the overall passing percentage for both math and reading decreases 91% to 65%.

<img width="186" alt="image" src="https://user-images.githubusercontent.com/104729703/177063503-f74e85e2-2384-404e-9e5c-e3f776c3b592.png"><img width="185" alt="image" src="https://user-images.githubusercontent.com/104729703/177063776-eb93780f-4416-4bc2-95ac-174e659677d6.png">

- In the ranking of math and reading scores by grade (shown above) the refactored analysis reveals a data hole for the ninth graders at Thomas High School. This could present issues for the school if the data were sorted by grade and funding determined by performance outcomes. The absence of data could be interpreted as a zero in a ranking, and so would place the school last for freshman scoring outcomes.

<img width="499" alt="image" src="https://user-images.githubusercontent.com/104729703/177068131-469f044f-72be-4dec-9c40-e9673676300f.png">

<img width="498" alt="Scores_By_Spending_Per_Student" src="https://user-images.githubusercontent.com/104729703/177068184-f07fe4db-0528-4e8a-a659-21649eaeb1ab.png">

-The omission of freshman grades has no impact on the score outcomes by spending per student. The above tables are identical and represent the same analysis run before and after the omission of Thomas High School freshman data. Because the freshman are still counted in the total number of students, the outcome remains the same. If the freshman were omitted from this count, the data could be skewed to imply that Thomas High School spends more per student than it actually does.

<img width="637" alt="Scores_By_School_Size_Initial" src="https://user-images.githubusercontent.com/104729703/177033727-09920145-d42e-417b-8a5c-d9a6dd49736b.png">
<img width="449" alt="Scores_By_School_Size" src="https://user-images.githubusercontent.com/104729703/177033721-d355f2a5-f5bc-41f9-ab2a-e2da974ef970.png">

- Scores by school size are also not impacted. The above tables depict score outcomes by school size, first with the Thomas High School freshman data included, and then without. The data is unchanged because the freshman are included in the total school district population count. Removing them from this count would pontially move Thomas high school into a "smaller" school size bracket and further skew the analysis.

<img width="577" alt="image" src="https://user-images.githubusercontent.com/104729703/177069044-82f210f3-777b-4b62-b7a0-4332afe70421.png">
<img width="428" alt="Scores_By_School_Type" src="https://user-images.githubusercontent.com/104729703/177033748-d54db703-9725-4cc4-aba8-d3486db89ab1.png">

- Scores by school type also remain un-impacted by the omission of Thomas High School freshman math and reading scores, as they are calculated using the total student count

# Summary: 
Four changes that have become evident since the replacement of the Thomas High School freshman grade outcomes with "Not a Number" signifiers are as follows:

1. Scoring by grade level has the potential to rank Thomas High School last for 9th graders.
2. The math score percentages within the school data comparison decrease for Thomas High School as a whole when their ninth graders are counted as individuals with non-numeric data for their scores.
3. The reading score percentages within the school data comparison decrease for Thomas High School as a whole when their ninth graders are counted as individuals with non-numeric data for their scores.
4. The combined math and reading score percentages within the school data comparison decrease for Thomas High School as a whole when their ninth graders are counted as individuals with non-numeric data for their scores. 
