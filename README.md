# Student-Mental-Health

![dashboard](https://github.com/user-attachments/assets/e251f88f-5925-44f6-9a4d-679ee15ec525)


## Table of content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data cleaning and preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion and Recommendation](#conclusion-and-recommendation)
- [Limitation](limitation)


# Project Overview

Students sometimes suffer from unseen factors that contributes to their performance. These factors can be summed up as mental health. Studies have shown that the mental health of a student can contribute adversely to their performance. This study is to highlight the effect of each of these mental health attributes and give conclusion and recommendations.

# Data Source:

The dataset was gotten from kaggle.com

# Tools:
- Microsoft Power Bi

# Data cleaning and preparation:

Departments with repeated entries written in different cases were corrected, white spaces removed, data types for some columns were corrected, and columns for the different mental health attributes were unpivoted(cells with "No" were replaced/changed to null before unpivoting).

# Exploratory Data Analysis:

Objective of EDA is to answer particular quesstions or derive insights from the data set. Such Insights cover the reaction of students to various mental health issues.

From the analysis of data, the following can be inferred;
1. Total number of students involved in the study is 101.


2. These students are spread across 35 departments/courses.


3. ⁠Overall students performance is acceptable as 47.5% of them are on the peak cgpa of 3.50 - 4.00, and 42.57% in the range of second best cgpa(3.00 - 3.49). This accounts for about 90% of students performing way above average.

![overall student academic performance](https://github.com/user-attachments/assets/c992f801-974a-4e9a-acf7-5ccb167fbefd)


4. Year one has the record of highest cgpa. Safe to say that year one students perform better than students from other year of study. 

![overall student academic performance by year of study](https://github.com/user-attachments/assets/d6a0d12b-fefb-463a-ae59-735509eb29a4)


5. Year one students have higher panic attack, anxiety and depression level as compared to others, followed by year 2 and year 3. They also sought treatment the most.

![all mental health atributes according to year of study](https://github.com/user-attachments/assets/66bbe366-baf8-4c30-ab03-ae24a2f6a434)

![number of students with mental health issue in each year of study](https://github.com/user-attachments/assets/a4702680-4036-4be2-a597-8f18fc629bdb)



6. Marriage stat is higher for year 2 and year 3. Conclusively, students get married around year 2 and year 3.


7. ⁠Female students dominate the list of married students with a higher stat over married male.

![married students](https://github.com/user-attachments/assets/c1328153-d9c0-4d30-ada6-e188476eff61)


8. Students in some departments perform better than other department. This could be because such department is less demanding or less tough.

# Conclusion and recommendation:


Even though year one students seem to have more mental health issues and sought treatments the most, as compared to others, they still manage to  perform better than others. This could mean that courses are less demanding in year one and becomes tougher as students progress. Orientation and mental support should be provided to students in year one.
It is also recommended that students from higher year of study be given critical tutorship to boost their performance.
 
# Limitation:
Insight from this data set may be unreliable for making realistic conclusions as the survey was carried out over a very limited number of students in  the school. It may not fully portray the true condition of students accross various year of study and departments as total number of record/rows is 101 only.
