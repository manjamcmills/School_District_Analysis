# School District Analysis 

## Overview of School District Analysis
The purpose of this investigation was to analyze school district data of math and reading standardized test scores to showcase trends in school performance. The data for the analysis contains over 39000 students from 15 different schools. This information will be used to help inform the school district in making decisions concerning budget and other priorities. 

After the initial analysis was completed, it was found that the students_complete.csv file show evidence of academic dishonestly by ninth graders in their math and reading scores from Thomas High School.  To uphold state-testing standards, the analysis needed to be completed again without counting the ninth graders from Thomas High School.   To do this change, all of the 9th grade scores from Thomas High School had to be replaced with “NaN”.  In turn, all the of the calculations had to be re-calculated without including these scores. 

## Results

### How is the district summary affected?

1.	The average math score dropped from 78.99 to 78.93.

2.	The average reading score dropped from 81.88 to 81.86.

3.	The passing math percentage went from 74.98% to 74.76%.

4.	The passing reading percentage went from 85.81% to 85.66%.

5.	The percentage of students who passed both math and reading went from 65.17% to 64.86%.

### How is the school summary affected?
•	The school summary was not affected except for Thomas High School.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

•	MATH AVERAGE: Thomas High School went from having  4th highest math average (83.41) to the 6th highest math average (83.35).

•	READING AVERAGE: Thomas High School STAYED at  the 5th highest reading average.  It just dropped from  83.85 to 83.90. 

•	% PASSING MATH:  Thomas High School STAYED at  the 7th highest percentage of students passing math. It just dropped from  93.27%to 93.19%.


•	% PASSING READING:  Thomas High School went from having the 1st highest percentage of students passing reading (97.31%) to  the 3rd highest percentage of students passing reading (97.02%).

•	% PASSING OVERALL: Thomas High School STAYED at  the 2nd  highest percentage overall. It just dropped from  90.95% to  90.63%. 

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade
•	Replacing the 9th graders scores from Thomas High School only affected the 9th grade only affected Thomas High School. They no longer have average scores in 9th grade, just “NaN”.  It didn’t affect any other scores.

#### Scores by school spending
•	Since Thomas High School was in the “$631-$645” spending category, this was the only category affected.  However, it was not affected that much.  

o	Average Math Score went from 78.52 to 78.50.

o	Average Reading Score went from 81.62 to 81.64

o	% Passing Math went from 73.48 to 73.46

o	% Passing Reading went from 84.39 to 84.32

o	% Overall Passing went from 62.86 to 62.78

#### Scores by school size
•	Since Thomas High school was in the “Medium” (1000-1999) size school category , this was the only category affected. Again, it was not affected that much.

o	Average Math Score went from 83.37 to 83.36.

o	Average Reading Score went from 83.86 to 83.87.

o	% Passing Math went from 93.60 to 93.58.

o	% Passing Reading went from 96.79 to 96.73.

o	% Overall Passing went from 90.62 to 90.56

#### Scores by school type 
•	Since Thomas High school is a Charter school , this was the only category affected. Yet again, it was not affected that much.

o	Average Math Score went from 83.474 to 83.465.

o	Average Reading Score went from 83.896 to 83.902.

o	% Passing Math went from 93.621 to 93.610.

o	% Passing Reading went from 96.586 to 96.550.

o	% Overall Passing went from 90.432 to 90.393. 


## Summary:

Overall, the school district analysis was not affected that much by dropping the 9th grade scores from Thomas High School.  While still small, the most significant changes were the following: 
1.	The passing math percentage for the ENTIRE DISTRICT went from 74.98% to 74.76%.
2.	The percentage of students in the ENTIRE DISTRICT who passed both math and reading went from 65.17% to 64.86%.
3.	Thomas High School went from having  4th highest math average (83.41) in the district to the 6th highest math average (83.35).
4.	Thomas High School went from having the 1st highest percentage of students passing reading in the district (97.31%) to  the 3rd highest percentage of students passing reading (97.02%).
