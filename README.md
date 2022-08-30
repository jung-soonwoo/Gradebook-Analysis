# Gradebook-Analysis

Using Python, SQL, and Pandas, I attempt to dive behind the numbers using my own personal gradebook to form conclusions.

## Background

The data being analyzed is comprised of gradebooks spanning 5 different classes over the course of 2 years. The classes were personally taught by me during my graduate degree. The class was designed for preservice undergraduate students planning to become mathematics teachers. There are ~200 students for the entire database.

## Questions Ventured

- What type of grade distribution is observed?
- Have grades improved over time?
- Are there any observable equity dimensions/racial inequities?
- What type of correlations can be observed with final scores?

## Grade Distribution

![Grade Distribution #1](https://user-images.githubusercontent.com/112305152/187067060-0055acd9-e893-4be1-8631-aa83a4211f76.png)
![Grade Distribution #2](https://user-images.githubusercontent.com/112305152/187234133-7549ba3d-dc47-4dea-8e69-df96a90a31ba.png)

Both of the charts show the distribution of grades over all 5 classes. In "Number of Final Grades", it can be observed that the majority of students scored a B- or higher with the final score of B containing the most amount of students. In "Histogram of Final Grades with Kernel Density Estimation", a histogram shows the distribution of grades over the numerical score between 0-100%. The histogram also includes the Kernal Density Estimate(KDE) which peaks between a score of 80-90%. In this case, the KDE tells where the majority of students held their final grades. An interesting inflection point in the KDE lies right before the passing grade cutoff between 65-69%.

## Grades VS. Time

![Grade VS  Time](https://user-images.githubusercontent.com/112305152/187067375-cedf2264-82ca-4f4b-8cd3-34384afc5c7f.png)

In this box plot it can be concluded that over time, the final grades of students improved every semester. This can be due to a couple of factors:
- Teacher's curriculum and quality improved over time.
- The syllabus of the course changed more favorably for students over time.
- Prerequisite classes better prepared students for sequential courses.

Furthermore, the course was first taught during the peak of COVID-19 forcing the adaptability of professors to the use of new and unfamiliar education technology such as Zoom, Desmos, and other online learning resources. This is a possible explanation for the rising trend in the final grades as professors became more comfortable using such technology. 

## Equity Dimensions

![Equity Dimension](https://user-images.githubusercontent.com/112305152/187149434-88179a61-536f-44c0-961a-a8f0fd033331.png)

To preface, race and gender were on the top of my list for equitable dimensions to observe during the data analysis. However, since the classes were comprised of 97% females, I felt the results produced from the gender dimension would be negligible/inconclusive. 

In this bar chart, I brought in the race element to identify any potential implicit biases I might have held as an instructor. To preface, data analysis such as this example can hold biases in themselves through multiple means. Some of these biases can be held in the data collector, the method of data analysis, or the data itself.

In this example, students are divided by race and compared with their final grades in the class. In theory, the bar chart should appear similar to the diagram titled "Number of Final Grades" to imply equitable grade distributions. 

Starting with the biggest group, the final grades with Caucasian students were found to be aligned with the overall grade distribution. This can be seen with the biggest density of grades around 'B' with a smaller peak in 'A'. This can imply equitable practices from the instructor towards the caucasian group. The next biggest group, Hispanic/Latinx students had their most amount of final grades in 'B+'. A significant finding was that Hispanic/Latinx students had significantly more 'B+' and 'A-' compared to Caucasians but significantly less 'A' (2.74% vs 15.38%).

In the third biggest group, Asian students had the most amount of 'A' grades out of any other race. This can imply that myself as an instructor had biases towards my own ethnic group. While alarming, this aligns with the stereotype that "Asians are good at math" or "Asians are good at school". Finally, Black students had an even distribution of grades in the class. However, it is important to note that there were only 4 Black students throughout the entire 5 classes of instruction. This explains why each of the 4 final grades had a distribution of 25% each. Due to the lack of data points, more Black students must be taught to see conclusive data or the current result with Black students must be negligible in this case.


## Correlations between Homework, Midterm, and Final Exam Scores

![Homework vs Final Exam](https://user-images.githubusercontent.com/112305152/187068018-89e4aaf7-f84b-4724-afaa-4ba66bc758cb.png)
![Midterm vs Final Exam](https://user-images.githubusercontent.com/112305152/187068040-48a9c156-abf2-4d44-a0f5-041227aaf7eb.png)
![Homework vs Midterm](https://user-images.githubusercontent.com/112305152/187125080-ca578603-2bb2-46c7-86f8-221655147885.png)

In the final data analysis, I wanted to explore the correlation between homework, midterm, and final exam scores. This was done through 3 scatter plots while overlaying the regression line. Overall, homework, midterm, and final exam scores all produced a positive correlation with each other. This means that students who did well on homework also produced good results on the midterms and final exams. The same can be said for midterms to homework and final exam scores.

The weakest regression line (the line with the smallest slope) was represented in the "Homework Score vs Final Exam Score" plot. This means that in comparison to the 2 other scatter plots, the "Homework Score vs Final Exam Score" plot had the weakest positive correlation. Thus, while positive, homework scores were less likely to improve final exam scores.

## Final Thoughts

Throughout this personal project, meaningful results have been found through indicative evidence through the means of Python, Pandas, and SQL. The use of data analytics in combination with gradebooks show the potential areas of improvement for a typical college course. For example, professors can use this framework to understand where their weaknesses lie in regards to their lecture-style, curriculum, or various other factors that go into a successful classroom. However, it is important to note that the data analysis presented in this project can be improved significantly by several factors. The increase in the amount of semesters, an increase in the number of Black students, and a variety of different courses taught could all potentially improve the conclusiveness of the data analysis. 









