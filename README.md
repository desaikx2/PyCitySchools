# PyCitySchools

Here is written report for district summary for this classwork. I am utilizing panda library from Python to analyze two csv files called as Resources/schools_complete.csv and Resources/students_complete.csv .

After Reading two CSV files,I am utilizing panda merge functionality to merge those data sets and then I am printing first 5 lines using head function of panda. I can also count unique values for schools using unique library and I could also used set library but i dont want to use later so i choose unique library. I also counted stundents and also average of math score and reading score using mean library of pandas.

I can also count reading_score and math_score which has above 70 and also created high level key metrics in a DataFrame and printed it using jupyter notebook.

I also found out school budget and also printed average test scores per school using groupby function for reading_score and match_score. I also printed students passing math above 70 and found out school which school has highest passing score. I also done same exercise for reading_score and printed same.

I did individual report for reading_score and math_score but I combined using and function and it gives good data and printed per_school_summary for review and also printed Highest-Performing Schools (by % Overall Passing) and also Bottom Performing Schools (By % Overall Passing) and also Math Scores by Grade and also Reading Score by Grade.

There was ask to establish spending and gave lables and i utilized cut methods to find out Scores by School Spending and printed Spending Ranges (Per Student). I think, I got various errors for given panda library and I can downgrade library and I could have avoided errors but that code was given already and it was not able to convert for ranges.

I am able to print per_school_summary for Total students for given labels and categorized it for this Scores by School Size then i got again errors for data type conversion.

**Summary :**
There are 15 schools and with total students of 39,170 with budget $24,649,428.00.

Bailey High school has maximum students in district and it is 4976 hence it is Large school size in district and Holden High School is very less students in district and it has 427 students only and it is very small size.

There are various schools spending more 680 labels and Griffin High School has highest average math score and overall passing winner is Bailey High School with 2,719.00%.

There are various schools and some schools has highest grade in math and it is Thomas High School for 9th grade and for 12 th grade, it was Shelton High School with 83.778976%.

For reading,Highest grade in 12 th grade school is Pena High School and it has 84.591160%.

There are bottom schools which has low passing schools such as Ford High School,Figueroa High School etc and high performing schools are Pena High School,Bailey High School etc.

