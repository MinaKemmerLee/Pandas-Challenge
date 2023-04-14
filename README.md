# Pandas-Challenge

Pandas-Challenge.ipynb is located in the PyCitySchools folder 

Analysis: 
- the dataset includes the information of different schools, and lists their characteristics; including the number of students per school, the total budget of each school, the budget per capita, as well as the average testing ranges for both reading and math per grade level.  
- this dataset includes information regarding 15 different high schools, that have an average of 2000 students per school with a range of 427 - 4976 students. The average budget per school is $1,643,295, with a range of $248,000 to $3.1 million . The average budget per capita is $620, with a range of $578 to $652. The average testing range for reading is about 82%, with a range between 80-85%. The average testing range for math is about 80%, with a range between 76-84%.  
- A specific outliar that may cause indiscrepancies, is the student count for Holden High School. This school has a drastically lower amount of student compared to the average number, however the budget per capita(per student) is still within the average range. 
- using the original merged dataset we find the values for and create the following dataframes:  
		-DISTRICT SUMMARY (which includes the total # of schools, the total # of students, the total budget for each school, the average math scores, the average reading scores, % passing math, and % passing reading,and the overall % passing for both math and reading), 
		-SCHOOL SUMMARY (which includes the specific school types, the # of students per school, the total budget per school, the total budget per student per school, the average math scores per school, the average reading scores per school, % passing math per school, and % passing reading per school, and the overall % passing for both math and reading per school), 
		-MATH SCORES BY GRADE (which includes the average math scores for each grade: 9th, 10th, 11th, and 12th, for each school),
		-READING SCORES BY GRADE (which includes the average reading scores for each grade: 9th, 10th, 11th, and 12th, for each school),
		-SCORES BY SCHOOL SPENDING (which includes average math and reading scores, as well as the % passing math, reading and an overall % passing, along with the spending ranges per student compared to the total school budget, and the per captia budgets of each school),
		-SPENDING SUMMARY (which compares the average math and reading scores, as well as the % passing math, reading and an overall % passing, to the specified spending ranges per student),
		-SCORES BY SCHOOL SIZE (which compares the size of the school aka the amount of students per school, to the average math and reading scores, as well as the % passing math, reading and an overall % passing per school),
		-SIZE SUMMARY (which compares the average math and reading scores, as well as the % passing math, reading and an overall % passing, to the specified school sizes),
		-SCORES BY SCHOOL TYPE (which compares the type of school, to the average math and reading scores, as well as the % passing math, reading and an overall % passing per school)
- Overall, the dataset suggests that there is a positive correlation between school budget and student performance on standardized tests. However, this correlation is not very strong, and other factors may also be important. The dataset also highlights the importance of considering budget per capita, as schools with higher budgets may not necessarily have better outcomes if they have a larger student population. Finally, the dataset suggests that more research is needed to fully understand the factors that contribute to student performance in high school.
