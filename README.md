
# **School_District_Analysis**

## *Project Overview*
 Our objective is to help Maria to analyze schools funding insights and students' standardized test scores. These performance trends and patterns analysis; will be used for strategic discussions and decisions at the school district level.  I need to aggregate the Data and showcase trends in school performance. The analysis will assist the school board superintendent in making decisions regards schools' budgets and priorities. For this purpose, I will write code using Pandas and Jupyter notebook Python to import and read CSV  Data, inspect the data, clean the data and re-organize and present the data in a readable format to covey the analysis outcome and the message.     
   
                  
## *Analysis & Results*
### Analysis
For this analysis, I will be given access to every student's math and reading scores as well as various information on the schools they attend. Need to aggregate the data and conduct analysis, to help the board for the School District to make Required decisions. Based on the board's ask, I need to examine and analyze the evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. To do so, I will exclude the 9th-grade scores in Thomas High school and create the district and school summary matrix, Then I will Relace the 9th Grade math and reading scores in Thomas High school and Recalculate the district, school summary matrix to examine the impact of the alleged dishonesty. Based on this we will get the conclusions ... to conduct the analysis I will have to follow the following analysis process.

1) 1st step in the analysis process is reading the data from the CSV file, clean the Data (remove prefix and suffix from students Names), and then organize the data in a readable table format, i.e. Date frame (df).

![insert image 1]

 2) Once we have a clean table; Named "student_Data_df"; I Will use the Loc. method on this Dataframe to select all the reading & math scores from the 9th grade at Thomas High School and replace them with null value "NaN". 
 
  ![insert image 2]
 
3)  After we replaced the math and reading scores for Thomas High school 9th Grade students in the "Student_Data_df" table, I will merge this table with the "school_data_df" table (using school Name as index), to create a combined "school_data_complete_df" table to repeat the school district and school analysis and summary.   

![insert image 2]

4) Next I need to create a Datatables to present a district summary and school summary 

![insert image 4]
![insert image 5]

5) Next, Need to use the Loc. Method to recalculate Average Math Score, Average reading score,"% passing reading", "% passing math", and "% overall passing". then we will create a "cleaned" Dataframe table that includes the recalculated values. 

![insert image 6]


6) once we recalculated the new Parameters, we will use the refactored values to create a new DataFrame table to recalculate the district and school summary tables. 

![insert image 6]

7) Once we created the data frame table with the refactored values, the next step to reuse the Code to aggregate, Format, and sort the data into the following summary tables:
a. High and Low Performing Schools
b. Math and Reading Scores by Grade
c. Scores by School Spending
d. Scores by School Size
e. Scores by School Type



          
### Results
There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data
The analysis shows the following impact of Thomas High School 9th Garde. 
a) At the district level, The impact of Thomas High School 9th Grade is negligible.
b) Although, % overall passing increased from 65.076% to 90.630% , % of passing reading increased from 69.66% to 97.018% & % of passing math increased from 66.911% to 93.185%. Yet, The average Math & Reading score wasn't changed significantly.      

    
## *Summary*
### Advantages
 Using Pandas and Jupyter Notebook is a powerful tool for Data Mongoing, it's useful for reading CSV files, cleaning Data, and performing Data manipulations to enable the data analysis. we easily could re Use this code to enable Data analysis for different districts, schools, or any other analysis. we could scale this code to analyze other school districts ... The  Impact of Thomas High School 9th Grade on the district/schools is not significant. 
