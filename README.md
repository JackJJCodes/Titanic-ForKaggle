# Titanic-ForKaggle
This is my attempt on a classic ML problem on Kaggle, Titanic Survival Prediction

## Motivation for the Project:
The reason why I chose this project, is that I wanted to get started with Kaggle competitions since I ever found out about them, which was like 6 months ago.
After hours digging on the Internet, I found out that "Titanic Prediction" is the best way for a beginner like me to understand how "Kaggle Competitions" work, and how to put a submission for the competition.
So, after my end-semester exams finished, I put this project as my number 1 priority, and did it!

## Algorithm Used:
I have used Logistic Regression for this project, because:
1. It is beginner friendly.
2. It is the most basic algorithm for binary classification.

For a more comprehensive understanding of Logistic Regression, check out this awesome blog by christophm: https://christophm.github.io/interpretable-ml-book/logistic.html

This repository contains the following files:

1. third_draft.csv: Consists of the .csv file needed to be put as a submission, for the Kaggle competition.
                    Consists of the people who did, or did not survive.
2. titanic_comp.ipynb: Consists of the Jupyter Notebook, which consists all the code for the project.
3. titanic-test.csv: Consists of the testing dataset, which will be used further in the project.
4. titanic_train.csv: Consists of the training dataset, which we will feed in to our algorithm.

## What have I done in this project?
1. Cleaned the dataset, eliminated null and missing values.
2. Visualized graphically different features and their correlation with each other.
3. Converted various categorical features into numerical features using OneHotEncoding.
