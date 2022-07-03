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

<img width="587" alt="image" src="https://user-images.githubusercontent.com/104729703/177032365-1bd14dff-403c-47d3-9559-8c73a6e3393a.png">
<img width="703" alt="image" src="https://user-images.githubusercontent.com/104729703/177032716-9b8413f2-0688-4643-8bbf-76d7e726a53a.png">

- The tables above represent the two school district summaries, the first with the Thomas High School ninth grade scores included, the second without. The comparison reveals that the omission of Thomas High School ninth grade math and reading scores affects the overall district data hardly at all. The size of the student population is affected, but the overall passing grades in math and reading decline by only a tenth of a percent. 


RIGHT HERE
- While the impact of the omission of Thomas High School ninth graders' math and reading scores from the overall school district data is slight, omission of Thomas High School ninth grade math and reading scores significantly improves Thomas High School's overall performance, relative to other schools. 

- Math and reading scores by grade

<img width="626" alt="Scores_By_Spending_Per_Student_original" src="https://user-images.githubusercontent.com/104729703/177033739-1f554b24-61cd-4f93-9691-f77778fe0bf9.png">
<img width="498" alt="Scores_By_Spending_Per_Student" src="https://user-images.githubusercontent.com/104729703/177033731-7a279a66-7d96-4ac4-a61f-03c568f207e0.png">
- Scores by school spending

<img width="637" alt="Scores_By_School_Size_Initial" src="https://user-images.githubusercontent.com/104729703/177033727-09920145-d42e-417b-8a5c-d9a6dd49736b.png">
<img width="449" alt="Scores_By_School_Size" src="https://user-images.githubusercontent.com/104729703/177033721-d355f2a5-f5bc-41f9-ab2a-e2da974ef970.png">
- Scores by school size


<img width="428" alt="Scores_By_School_Type" src="https://user-images.githubusercontent.com/104729703/177033748-d54db703-9725-4cc4-aba8-d3486db89ab1.png">
- Scores by school type


# Summary: 
Four changes that have become evident since the replacement of the data are: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Deliverable 3 Requirements
Structure, Organization, and Formatting (7 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt).
Each section has a heading and subheading (3 pt).
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis (18 points)
The written analysis has the following:

Overview of the school district analysis:
The purpose of this analysis is well defined (3 pt).
Results:
There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).
Summary:
There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).



Upload the following to your School_District_Analysis GitHub repository:

The PyCitySchools_Challenge.ipynb file.
The Resources folder with the schools_complete.csv and students_complete.csv files.
An updated README.md that has your written analysis.
