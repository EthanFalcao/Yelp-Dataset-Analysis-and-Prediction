﻿<a name="br1"></a>Yelp Dataset Challenge

DS3010 Final Project

Ethan Vaz Falcão, Emre Sabaz, Maanav Iyengar, Nur Fateemah, Sarah

Kogan




<a name="br2"></a>Introduction

` `Online review platforms like Yelp have become increasingly popular as a primary

` `The business file provides information about the establishments listed on Yelp, such

` `The Yelp dataset offers a comprehensive view of user-generated content and

1



<a name="br3"></a>**Task 1**

Objective

` `The objective of this task is to predict the business attributes using review and tip

Data Preprocessing

` `In this study, the most prevalent binary attributes were selected, as these were deemed

Figure 1 - Most Common Attributes

Training & Results

` `The overall accuracy rate achieved for the whole dataset was 0.74. The multi-label

` `As shown in Figure 2, the precision scores for the classes are relatively high, with

0\.93 for class 0, 0.84 for class 1, and 0.85 for class 2. These values indicate that the model

0\.98 for class 2. These scores show that the model had a low rate of false negatives,

0\.91 for class 2. Overall, the model demonstrates a strong performance, particularly for class

2




<a name="br4"></a>F1-score is 0.87, 0.99, and 0.93, respectively, indicating good performance on a per-instance

Figure 2 - Random Forest Model Classification Report For Task 1

` `As shown in Figure 3, The precision scores indicate the proportion of correctly

0\.91 for class 1, and 0.91 for class 2, indicating a balanced performance.

Figure 3 - SVC Classification Report for Task 1

` `The confusion matrix for the results of Task 1 are shown in Figure 4. -4616 true

3




<a name="br5"></a>Figure 4 - Confusion Matrix for Task 1

The workflow for this task is shown in Figure 5.

Figure 5 - Workflow for Task 1

Business Applications

` `There are two primary business applications that can be found when predicting the

4




<a name="br6"></a>**Task 2**

Objective

` `Our objective is to use a machine learning model to help accurately detect fake

Data Preprocessing

` `The initial phase of this project involved preprocessing and cleaning the data. A data

` `In the feature engineering phase, crucial features for detecting fake reviews were

` `We used the data first through supervised learning, the models we used were a random

5




<a name="br7"></a>Training & Results

` `Figure 6 shows the different models that use simple upsampling behavioral data, the

Figure 6 - Graph Showing Different Models using Smoted Upsampling Behavioral

Data

` `Figure 7 shows the ROC curve for the fake review classification, both Smote and

6




<a name="br8"></a>Figure 7 - ROC curve for Fake

Review Classification

` `Figure 8 shows the feature importance, and the model focused more on the stars rather

Figure 8 - Feature Importance

` `Figure 9 shows the confusion matrix of gradient boosting, it shows that the model has

7




<a name="br9"></a>Figure 9 - Confusion Matrix of Gradient Boosting

Figure 10 - Task 2 Workflow

` `When using ADASYN (a technique for handling imbalanced datasets), the model's

8




<a name="br10"></a>Figure 9 - Graph Showing Different Models using Adasyn Upsampling Behavioral

Data

Business Applications

` `Four primary business applications can be found when predicting the business

9




<a name="br11"></a>**Conclusion**

Challenges

` `For Task 1 and Task 2, there was a notable challenge due to the large volume of data,

` `Task 1 posed another obstacle, particularly in the division of attributes into separate

` `Similarly, Task 2 presented its own set of difficulties, particularly in determining the

` `To achieve the goal of developing a highly accurate machine capable of detecting all

` `SMOTE works by generating synthetic samples of the minority class by interpolating

` `By applying both SMOTE and ADASYN analyses, the team was able to create

Future Work

` `Future directions for this project encompass a range of potential improvements and

10




<a name="br12"></a>algorithms, as well as the systematic adjustment of hyperparameters such as epoch and batch

Team Member Contributions:

Team Member Names Team Member Contributions

Ethan Vaz Falcão Contributed significantly to task 1 and task

methods and code and researched feature engineering methods. I also assisted with task 1 and used my PC to run both task 1 and task 2 fully. Additionally, I helped with

Emre Sabaz I worked on improving the task 1 methods

Maanav Iyengar Set up meetings. Researched and assisted in

the report and presentation.

Nur Fateemah Worked on task 1 methods and code, did

Sarah Kogan

11