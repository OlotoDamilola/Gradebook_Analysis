# Gradebook_Analysis
# Analyzing data in Excel and visualizing with Power BI
# Introduction
This is a personal related project. I conducted an analysis on a dataset that I generated to monitor S.S 1 students progress in technical drawing from the first to the third term of the session in Ijebu Ode Grammar School (JOGS). The dataset contained 153 rows and 26 columns. The following variables are included in the data;

a) Student Name: The name of the student

b) Class: The class each student belong, either science 1 or science 2

c) CA_1a: The score of the first continous assessment in first term

d) Total_CA2: The total score of continous assessment in second term

e) Total_Score3: The sum of score in continous assessment and exam in third term

f) Weighted Average: The average of total scores in first, second and third term. 

The aim of the research is to derive significant insights that will guide teaching improvement on the basics of technical drawing.

# Data Collection and Data Wrangling
I entered the information into my Excel software to gather the data. After making sure there were no miissing values and that the columns were in the correct data type, I transformed the data into a table format. To compute the Weighted Average, Average CA and Average Exam score, columns were added. After importing the data into Power Query, I checked for the validity of my data using column distribution, quality and profiling. The Switch DAX function was used to group the weighted average into score grade of five categories. 

# Data Analysis and Data Visualization
![image](https://github.com/user-attachments/assets/a4857fb8-7e7b-4096-af43-253b3b9d93e7)

Students in science 1 dominated the top 7 students. With an average of 87, science 1 student, Quadri Ibrahim Temitope received the highest mark. Ogunleye Adewure Aduragbemi, the lone student from science 2 in the top 7, comes in second place with a score of 78. Other students include, Hassan Abdul-Afeez Adeiza (75), Oniuku Odafe Akorede (72), Olunuga Toluwalase Babafeni (70), Ogunnusi Olusola Emmanuel (70) and Odulaja Yusuf Olamide (69).

![image](https://github.com/user-attachments/assets/c786da41-9b84-4110-a998-3aef8a30589e)

The highest rank student, Quadri Ibrahim Temitope, generally scores 91 in the first term of the session, decreasing by 7% in the second term and then scoring 87 in the third term. This pattern of higher scores in the first term was seen while analysing the results of the top students. 

![image](https://github.com/user-attachments/assets/da45f388-3d89-45ad-b470-6d9c7801c609)

In both classes, students often score between 50 and 59 which is considered Good. This demonstrates that most of the students in the session achieved higher than average score. Due to missing at least one term of the session, the students who were placed in the Poor category has a score of less than 40. For example, Harun Nasirullahi Goodluck from science 1 missed the first term, scored 49 in the second term and 66 in the third term and then with weighted average of 38.

![image](https://github.com/user-attachments/assets/03514c60-2afb-4c33-b2b2-4e3b1d05ea6c)

This displays the weighted average distribution between the two classes. In Science 1, 30 students scored between 50 and 59, 22 students scored between 40 and 49, 20 students between 60 and 69 and 5 students scored the most, placing them in the Excellent category. The Interquartile Range (IQR) provided more information about the scores distribution and variability. 

Science 1:

IQR = Q3 - Q1

IQR = 63 - 48 = 15

To get the high Outliers;

Q3 + 1.5 x 15

63 + 1.5 x 15 = 86

To get the low outliers;

48 - 1.5 x 15 = 26

This shows that a student score in Science 1 will most likely fall between 26 - 86

Science 2:

60 + 1.5 x 15 = 70

53 - 1.5 x 15 = 43

This shows that a student score in science 2 will most likely fall between 43 - 70

# Conclusion
a) 100% pass rate excluding the 21 students who at least missed a term

b) With a lower population, Science 2 has more students score more than 49, weighted average.

# Recommendation
Teacher should work harder throughout the second and third term and students should take responsibility for raising their own performance in those terms.






