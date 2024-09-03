Student Performance Analysis

This project focuses on analyzing the factors that influence student exam scores, using a dataset containing various attributes such as hours studied, attendance, parental involvement, motivation levels, and more. The goal of the analysis is to identify key factors that significantly impact academic performance and to uncover interesting patterns within the data.

Project Overview

The dataset comprises multiple features related to student performance, including:

	•	Hours Studied: Weekly hours spent on studying.
	•	Attendance: Percentage of classes attended.
	•	Parental Involvement: Level of involvement from parents in the student’s education.
	•	Motivation Level: Self-reported motivation level of the students.
	•	Access to Resources: Availability of educational resources.
	•	Exam Score: The final score achieved in the exam.

Key Insights
Attendance and Exam Scores:

A clear positive correlation exists between attendance and exam scores. 
Students who attended more classes consistently achieved higher scores, highlighting the importance of regular attendance in academic success.

Hours Studied and Exam Scores:
The relationship between hours studied and exam scores is not linear. The analysis revealed that students who studied between 5 to 30 hours per week scored the highest marks. Interestingly, students who studied more than 35+ hours per week generally scored lower, with none of them achieving exceptionally high scores. This suggests a potential diminishing return or even a negative impact of excessive study hours on performance.

Exceptional Case:
A unique case was identified where a student scored 92 marks despite studying only 1 hour per week. Further investigation indicated that this student excelled in other aspects of life, possibly contributing to their high performance despite minimal study hours.

Other Factors:
Other factors such as parental involvement, motivation level, and access to resources showed minimal impact on the final exam scores when compared to hours studied and attendance.

Methodology

The project involved the following steps:

Data Cleaning and Preprocessing:
Handled missing values and converted categorical variables into numerical formats where necessary.

Exploratory Data Analysis (EDA):
Performed descriptive statistics and visualizations to understand the distribution and relationships between different features.

Visualizations:
Generated various plots, including bar charts and scatter plots, to visualize the relationships between factors like attendance, hours studied, and exam scores.

Conclusion

This analysis suggests that while factors like attendance and hours studied are critical to academic performance, more study hours do not always equate to better scores. In fact, overstudying may lead to decreased performance, highlighting the importance of balanced study habits.

Files in the Repository

	•	StudentPerformanceAnalysis.ipynb: Jupyter Notebook containing the full analysis, 
                including code, visualizations, and insights.
	•	StudentPerformanceFactors.csv: The dataset used for analysis.
	•	README.md: Detailed description of the project.

How to Use

	1.	Clone the repository to your local machine.
	2.	Open the Jupyter Notebook file (StudentPerformanceAnalysis.ipynb) to explore the analysis.
	3.	Review the insights and visualizations to understand the key findings.
