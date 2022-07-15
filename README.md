# School_District_Analysis
School District Analysis using Pandas and Python
Overview of School District Analysis
Link to project file
https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/PyCitySchools_Challenge.ipynb
###Purpose
Explain the purpose of this analysis.
The purpose of this analyzation of School District funding and standardized test score data was to provide insights about performance trends and patterns in order better inform School officials in their discussions and strategic decisions about each school and wider district priorities. Additionally adjustments were made to the analyzation due to the discovery of academic dishonesty found in the 9th grade class of Thomas High School, therefore we needed to remove this tainted data and re-do our data analysis of the wider data set.

###Results
Using bulleted lists and images of DataFrames as support, address the following questions.

##How is the district summary affected?
The district summary was mainly affected via the passing percentages for math and reading as well as the overall passing percentage.
![PNg 1.districtsum](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Summary%20School%20District%20Analysis-Aff.png)

##How is the school summary affected?
The school summary was mainly affected via the avg math score, avg reading score, % passing math, % passing reading, and % overall passing. 
![PNg 1.Schoolsum](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/SS%20Challenge%20vs%20Reg%20School%20Sum%20Affect.png)

##How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Relative to the other schools Thomas HS's overall performance does not appear to be substantially affected by the removal of the ninth grade scores. Thomas HS remains the second best performing school based on overall passing %.
![PNg 1.Performance](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Screen%20Shot%202022-07-15%20at%208.26.50%20AM.png)

##How does replacing the ninth-grade scores affect the following:
#Math and reading scores by grade
The only affect replacing the ninth-grade scores with "nan"s was that each chart, math and reading in the 9th grade columns, the result was now just a "nan" effectively removing it while keeping the rest of the results the same.

![PNg 1.math](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Math%20scores%20by%20grade-aff.png)
![PNg 1.reading](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Reading%20scores%20by%20grade%20-Aff.png)

#Scores by school spending
![PNg 1.spending](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Scores%20by%20school%20spending-Aff.png)
#Scores by school size
![PNg 1.size](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Scores%20by%20school%20size-Aff.png)
#Scores by school type
![PNg type](https://github.com/MichaelG-B/School_District_Analysis/blob/2cdae83e1c83c010799cc99476215fbe8ddb9f8f/Scores%20by%20school%20type-Aff.png)

The scores via school spending, school size, school type were not affected given the whole numbers presented in the charts. There may have been a slight affect but nothing that would warrant any significance.

###Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- Avg Math Score --> 79 to 78.9
- % Passing Math --> 75 to 74.8
- % Passing Reading --> 86 to 85.7
- % Overall Passing --> 65 to 64.9
