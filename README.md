# Student Grade Prediction

## Problem Statement
As per the data reported by **National Crime Records Burueau (NCRB), every hour one student commit suicide in India, with about 28 students commiting suicide everyday**. Some of the major reasons, students commiting suicide are **Stress, anxiety, disorder, depression, personality disorder**. These issues occur with students if they are not able to perform as per their expectation or they are not able to achieve some goal or marks due to some disturbance or personal issue or no awareness or no mentor to guide. **The main point is once any person or student went into stress, anxiety, etc then it severly affects the physical health as well as mental health**. So, my idea of choosing this data set and applying **linear regression** algorithm is to predict the chances of student getting good grades by analyzing his/her data. In today's time we all are also stuck at home due to pandemic and that is also affecting every student from kindergarten class students to graduation students. 

Getting good marks and learning concepts and new topics does not completely depends on how much time we do self-study, it also depends on our mental state, our environment of study, extra curriculur activities, activities at home, mentorship, etc. So, if some how, by using the data of the students such as age, family size, study time, activities, mother and father job time (basically to get an estimation of how much time they are with their child) etc if we can predict which students would be good and identify students who find it difficult to score good marks in the examination, so that people like teachers, parents, and friends can help him work on week aspects and try to make some improvement.

So, I have used this date set or 400 students and applied **linear regression** on this data. So, after creating a model we can input the student data and find out that he/she is working on right path and is not affected by some factors. If yes then we can guide him/her so that he/she can perform nicely.

## What I have done?
1. First I imported the dataset into colab and analyze and understood the data set properly by going through some of the info like columns, info, etc.
2. After analyzing, I found correlation between all colums and plotted the graph to find out relation between different columns using heatmap.
3. Then I spillted the data set into train set and test set. I will use train set to create and train the model and test test to further test and found the accuracy at the end.
4. I applied Linear Regression and fitted the data set and then did the prediction on the test set.
5. I scatter the prediction of Y (student condition) as per the input X_test using matplot library and then plotted using seaborn library.
6. At last I found the accuracy of the prediction.
