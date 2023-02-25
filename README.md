# asgn.
Assignment and workload management

## Problem Statement
Assignment dumps in a limited span are quite taxing on students. The less transparency between teachers and untracked progress are the main reasons for this issue, leading to workflow conflicts and a hit on efficiency.

## Domain
Ed-tech + machine learning

## The Solution
Asgn. aims to solve both of these problems in the following ways:

1.Increasing cross-subject transparency by introducing a global calendar for teachers with ML generated deadline suggestions based on students data sets and other      subject workloads.

2.Tracking and improving student progess by model-generated assessments that are purely for improving core knowledge of the subject.

## Overview
Asgn. consists of both a student and teacher side

### The teacher side

-Teachers may create and upload marked assignments
-Teachers may have a look at the global calendar
-A home feed to see latest posted assessments along with ML generated ones.

![image](https://github.com/SHAY2407/asgn/blob/main/images/site1.jpg)

### The student side

-A student home feed to see latest posted assessments with a due date and estimated completion time
-Deadline notifications
-Distinct colour coded subject calendar

![image](https://github.com/SHAY2407/asgn/blob/main/images/site2.jpg)

## Tech Stack
1.Backend Development: 

`flask` `node.js`

2.Frontend Development:

`HTML` `CSS`

3.ML model:

`python` `Spyder` `Jupyter Notebook`

## Models Used
1.Random Forest Regression
2.Linear Regression
We used a useful library called 'lazy predict', which helped us to find appropriate ML models which will give a decent accuracy with respect to the data available

![image](https://github.com/SHAY2407/asgn/blob/main/images/LazyPredict.jpg)

## Accuracy 

|                                             | Accuracy in % (on testing data) |
|:-------------------------------------------:|:-------------:|
| Accuracy                                    |76.4           |
| Cross Validation Score                      |0.6            |
