# School_District_Analysis
Utilizing Python, Jupyter Notebook, Anaconda and the Pandas library and to examine School District Data and showcase trends in school performance

## Overview of Project

This project regarding Module 4: PycitySchools, working with Anaconda and one of its items, Jupyter Notebook, using Python and Pandas library. We work with raw data information from CSV documents, examine and clean information, blend datasets, perform mathematical calculations and apply the groupby function to a DataFrame. This assignment is related to the Bootcamp Data Analytics from the University of Toronto.

We need to import two files [schools_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/students_complete.csv) into Jupyter Notebook using Python and working with two main goals for this module:

1) The first objective is to develop a data analysis generating the school and district summary, containing some key metrics, such as: top five and top bottom performing schools, based on the overall passing rate, math media and reading of each grade level of each school and finally the scores by school spending per student, by school size, and by school type.
two) 

2) The educational committee has advised Maria and her chief that the students_complete.csv record shows proof of scholarly untrustworthiness; explicitly, perusing and math grades for Thomas High School 9th graders seem to have been modified. Albeit the educational committee doesn't have a clue about the full degree of scholastic untruthfulness, they need to maintain state-testing norms. We need to supplant the math and perusing scores for Thomas High School with NaNs while keeping the remainder of the information unblemished. We need to rehash the school district analysis and review a report to depict what these changes affected the overall analysis.

# Resources

* Data Source: [schools_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/students_complete.csv)
* Software: Python 3.8.8, Jupyter Notebook 6.4.6, Pandas 1.3.4, Anaconda 4.11.0

# School District Results

Follow below are the results related to the data analyzed before: 

* Average Math Score = 79
* Average Reading Score	= 81.9
* % Passing Math = 75%	
* % Passing Reading	= 86%
* % Overall Passing = 65%

Follow below are the results related to the new data analyzed after requested by the school board:

* Average Math Score = 78.9
* Average Reading Score	= 81.9
* % Passing Math = 74.8%	
* % Passing Reading	= 85.7%
* % Overall Passing = 64.9%

Follow below the comparison between previous data vs new analyzed data 

* Average Math Score = 79.0 vs 78.9 = Difference of 0.1
* Average Reading Score	= 81.9 vs 81.9 = No Difference
* % Passing Math = 75% vs 74.8% = Difference of 0.2%
* % Passing Reading	= 86% vs 85.7% = Difference of 0.3%
* % Overall Passing = 65% vs 64.9% = Difference of 0.1%

##  How is the district summary affected?

After analyzing the previous data vs new analyzed and corrected data, it is noted that key indicators such as Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing were negatively affected, as all results showed a reduction between 0.1 to 0.3 points. Although the impact and change in the results were slightly different, if the student base within the School District is large, any percentage may impact or represent several students corresponding to the revision of the data.

Although the impact and change in the results slightly decreased, the difference of 0.2% in the percentage of passing Math could represent around 58 students, compared to 29370 who passed in Mathematics. Regarding the passing reading percentage indicator, where the difference was 0.3%, this represents about 100 students. In other words, considering only the differences observed in the percentage of passing Math and Reading, we would already have about 150 students who had differences after reviewing the data.

## How is the school summary affected?

Regarding data analysis considering the school summary, the impact was much greater, as significant differences were found after data revisions related to Thomas High School. Follow below the results and findings. The Thomas high school before the analysis, it had the result of an overall passing percentage of 90.63% occupying the second place in relation to the other schools in the district. After reviewing the data and correcting the results, Thomas high school had a result of 65.07%, with the eighth position in relation to the 15 schools. 

Before data analysis (Thomas High School)

* % Overall Passing = 90.63%. Second best results compared to 15 schools.

After review of data analysis (Thomas High School)

* % Overall Passing = 65.07%. Eighth place compared to 15 schools. 

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Follow below the results and findings. Before the data review, the Thomas high school occupied the third best place concerning the percentage of passing reading with 97.01 and about the percentage of passing Math, it was in seventh place. After data revisions, the Thomas High School had 69.66% for passing reading, occupying the last position in the ranking. Regarding the percentage of passing math, the Thomas High School had 69.91%, occupying the tenth position compared to other schools.

Before data analysis (Thomas High School)

* % Passing Reading = 97.01%. Third best results compared to 15 schools. 
* % Passing Math = 93.18%. Seventh best results compared to 15 schools.


After review of data analysis (Thomas High School)

* % Passing Reading = 69.66%. Last place compared to 15 schools.
* % Passing Math = 66.91%. 10th place compared to 15 schools.

## How does replacing the ninth-grade scores affect the following:

* Math and reading scores by grade

After the School board notified the evidence of academic dishonesty to the math and reading grades of 9th graders at the Thomas High School, the grades were replaced with NaNs. Changing the grades to NaNs is equivalent to zero; it means that the students failed. The results of the data analysis reviewed presented minimal difference concerning the results of the School District, as already mentioned above.

  * Student count() Before data analysis was: 1635
  * Student count() After data analysis was: 1174

* Score by school spending



* Scores by school size


* Scores by school type


 
 





