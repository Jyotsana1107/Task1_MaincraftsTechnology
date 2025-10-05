# Task1_MaincraftsTechnology

***OVERVIEW:-***

This is Task 1 of Maincrafts Technology. In this task, I had to analyze and explore Student Performance dataset in Subjects- Maths and Porteguese. 
This Jupyter Notebook analyzes students’ academic performance in Mathematics and Portuguese using the Student Performance dataset.

***STEPS:-***
1. I have imported Pandas and matplotlib libraries for cleaning, analyzing and visualizing the data.
2. I have merged the data and added a subject column having maths/porteguese and handled the null values and removed the duplicate values.
3. I had also renamed the Grades (G1,G2,G3) of Maths to MG1.MG2,MG3 and of Porteguese dataset to PG1,PG2,PG3. So we can have a detailed overview of the data.
4. Then I have made some calculations for the Analysis.
5. Then based on the modified data we create the charts to understand the data in a glance.

***ANALYSIS:-***
 - Average Final Grade i.e., average of G3
 - Number of students scoring above 15
 - Correlation between studytime and performance (G3)
 - Average performance by gender
   *We have did this analysis on Maths, Porteguese and combined data set.*

***VISUALIZATION:-***
- Histogram of Final Grades
- Scatterplot for Correlation of StudyTime vs Performance
- Barchart for Average Gender Performance

***Main Points (points to note)-***
- To get Average Final grade just use mean() func.
- To get no. of students scoring above 15, my code "clean_df1["MG3"]>15" checks the value of MG3 if its greater than 15 it gives true else false and as we know 1 is for true and 0 for false. So, when we sum it we get the sum of these 1 and 0's i.e, count of the students who scored above 15 points. (This same goes for porteguese and for both subjects together also)
- To find StudyTime correlation with performance we can use corr() function.
  (positive correlation means as study time increases performance also increases and as negative correlation means as study time increases performance decreases)
- Can find Average Gender Performance by using G3 score and grouping it on basis of gender
