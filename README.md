# School_District_Analysis
Utilizing Python, Jupyter Notebook, Anaconda and the Pandas library to examine School District Data and showcase trends in school performance

## Overview of Project

This project regarding Module 4: PycitySchools, working with Anaconda and one of its items, Jupyter Notebook, using Python and Pandas library. We work with raw data information from CSV documents, examine and clean information, blend datasets, perform mathematical calculations and apply the groupby function to a DataFrame. This assignment is related to the Bootcamp Data Analytics from the University of Toronto.

We need to import two files [schools_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/students_complete.csv) into Jupyter Notebook using Python and to work with two primary goals for this module:

1) The first objective is to develop a data analysis generating the school and district summary, containing some key metrics, such as top-five and top-bottom performing schools, based on the overall passing rate, math media and reading of each grade level of each school and finally the scores by school spending per student, by school size, and by school type.
two) 

2) The educational committee has advised Maria and her chief that the students_complete.csv record shows proof of scholarly untrustworthiness; explicitly, perusing and math grades for Thomas High School 9th graders seem to have been modified. Although the educational committee doesn’t know about the full degree of scholastic untruthfulness, they need to maintain state-testing norms. We need to supplant the math and perusing scores for Thomas High School with NaNs while keeping the remainder of the information unblemished. We need to rehash the school district analysis and review a report to depict what these changes affected the overall analysis.

## Resources

* Data Source: [PyCitySchools_Challenge_testing.ipynb](https://github.com/DougUOT/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)
* Database and files used: [schools_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/students_complete.csv)
* Software: Python 3.8.8, Jupyter Notebook 6.4.6, Pandas 1.3.4, Anaconda 4.11.0

## School District Results

Follow below are the results related to the data analyzed before: 

* Average Math Score = 79
* Average Reading Score	= 81.9
* % Passing Math = 75%	
* % Passing Reading	= 86%
* % Overall Passing = 65%

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/School_District_before%20data%20reviewed%20.PNG)

Follow below are the results related to the new data analyzed after requested by the school board:

* Average Math Score = 78.9
* Average Reading Score	= 81.9
* % Passing Math = 74.8%	
* % Passing Reading	= 85.7%
* % Overall Passing = 64.9%

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/School_District_before%20data%20reviewed%20%20(2).PNG)

Follow below the comparison between previous data vs newly analyzed data 

* Average Math Score = 79.0 vs 78.9 = Difference of 0.1
* Average Reading Score	= 81.9 vs 81.9 = No Difference
* % Passing Math = 75% vs 74.8% = Difference of 0.2%
* % Passing Reading	= 86% vs 85.7% = Difference of 0.3%
* % Overall Passing = 65% vs 64.9% = Difference of 0.1%

###  How is the district summary affected?

After analyzing the previous data vs new analyzed and corrected data, it is noted that key indicators such as Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing were negatively affected, as all results showed a reduction between 0.1 to 0.3 points. Although the impact and change in the results were slightly different, if the student base within the School District is large, any percentage may impact or represent several students corresponding to the revision of the data.

### How is the school summary affected?

The impact was much more significant regarding data analysis considering the school summary, as substantial differences were found after data revisions related to Thomas High School. Follow below the results and findings. Before the investigation, the Thomas high school had the effect of an overall passing percentage of 90.63%, occupying a second place among the other schools in the district. After reviewing the data and correcting the results, Thomas high school had 65.07%, with the eighth position concerning the 15 schools. 

Before data analysis (Thomas High School)

* % Overall Passing = 90.63%. Second best results compared to 15 schools.

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/School%20summary_before%20data%20reviewed.PNG)

After review of data analysis (Thomas High School)

* % Overall Passing = 65.07%. Eighth place compared to 15 schools. 

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/School%20summary_after%20data%20reviewed.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Follow below the results and findings. Before the data review, the Thomas high school occupied the third best place concerning the percentage of passing reading with 97.01 and about the rate of passing Math, it was in seventh place. After data revisions, the Thomas High School had 69.66% passing reading, occupying the last position in the ranking. Regarding the percentage of passing math, the Thomas High School had 69.91%, occupying the tenth position compared to other schools.

Before data analysis (Thomas High School)

* % Passing Reading = 97.01%. Third best results compared to 15 schools. 
* % Passing Math = 93.18%. Seventh best results compared to 15 schools.

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/School%20summary_before%20data%20reviewed.PNG)

After review of data analysis (Thomas High School)

* % Passing Reading = 69.66%. Last place compared to 15 schools.
* % Passing Math = 66.91%. 10th place compared to 15 schools.

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/School%20summary_after%20data%20reviewed.PNG)

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade

After the School board notified the evidence of academic dishonesty to the math and reading grades of 9th graders at the Thomas High School, the grades were replaced with NaNs. Changing the grades to NaNs is equivalent to zero; it means that the students failed. The results of the data analysis reviewed presented minimal difference concerning the results of the School District, as already mentioned above.

  * Student count() Before data analysis was: 1635

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Thomas%20High%20School_THS%20count_BEFORE.PNG)

  * Student count() After data analysis was: 1174

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Thomas%20High%20School_THS%20count_AFTER%20cleanup.PNG)

#### Score by school spending

The Thomas High School has $628 per student and is in the spending range from $630 to $ 644. After reviewing the data analysis at Thomas High School, and with the changes in the passing in math percentage results, reading and overall passing, the School board can review the total school budget, better distributing financial resources to other similar schools with better results.

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Scores%20by%20school%20spending.PNG)

Example:
  Shelton High School
  * Total of students 1761 vs 1635 of Thomas High School
  * Total of Budget $ 1,056,600.00 vs 1,043,130.00 of Thomas High School
  * % Overall Passing 89.89% vs 65.07% related to Thomas High School

  Wright High School
  * Total of students 1800 vs 1635 of Thomas High School
  * Total of Budget $ 1,049,400.00 vs 1,043,130.00 of Thomas High School
  * % Overall Passing 90.33% vs 65.07% related to Thomas High School

Comparing the results of Thomas High School versus other schools' results, with the same spending ranges (per student), the Thomas High School school presents much lower results after having the grades revised. This low performance could reflect on the results of average in this category in the data analysis. 

Comparative between Schools, with the same spending ranges (per student) vs Thomas High School
 * % Passing Math = 73% vs 66.91% = Difference of 6.09%
 * % Passing Reading	= 84% vs 69.66% = Difference of 14.34%

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Spending%20Ranges%20per%20student%20vs%20score.PNG)

#### Scores by school size

The Thomas High School is classified as medium in the size bin between 1000 and 2000. With the results revised Thomas High School, it was with results much lower than the other schools classified as medium.

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size.PNG)

Comparative between Schools, with the same size (Medium) vs Thomas High School
 * % Passing Math = 94% vs 66.91 = Difference of 27.09%
 * % Passing Reading	= 97% vs 69.66% = Difference of 27.34%
 * % Overall Passing = 91% vs 65.07% = Difference of 25.93%

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Size%20summary%20range.PNG)

#### Scores by school type

Thomas High School is a school-type Charter. Thomas High School is underperforming vs other Charter-rated schools. 

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Scores%20by%20school%20type_Thomas%20High%20School.PNG)

Comparative between Schools, with the same type (Charter) vs Thomas High School
 * % Passing Math = 94% vs 66.91 = Difference of 27.09%
 * % Passing Reading	= 97% vs 69.66% = Difference of 27.34%
 * % Overall Passing = 90% vs 65.07% = Difference of 24.93%

![](https://github.com/DougUOT/School_District_Analysis/blob/main/Resources/Scores%20by%20School%20Type.PNG)

## Summary

Abstract: Due to changes in math and reading grades, in 9th at Thomas High School, performed at the request of the School Board, applying data analysis, using Python, Jupyter Notebook, Anaconda and the Pandas library. These changes affected the school summary, math and reading score, also because the scores changed, there was a direct or indirect impact on other scores such as spending, size and type. Last but not least, changes in the number of students per school can affect the distribution of funding by schools and the budget per student. 

For example, in the case analyzed above, Thomas High School had 1635 students, and after the investigation, 1174 students. Considering the budget of $1,043,130.00, divided by total students before the analysis, we had a budget of $638; with the revision after the analysis, this budget per student would be $888, in other words, a difference of $250 in the funding per student. With all this data analysis and findings, the School Board will have a wide variety of information helping in decision-making and budget distribution strategy, among other academic plans related to schools' performance.
