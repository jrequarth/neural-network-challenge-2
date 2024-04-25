# neural-network-challenge-2

This is the Week 19 challenge.

the object of the task is to use a neural network branching program to determine whether an employee is going to stay at the firm or leave and whether the employee will be better served by moving to a different division of the firm.

The seed file is attrition.ipynb
The target values are objects: attrition and department in the y_df.
There are 25 additional columns of information such as age, travel, performance review, ect. These are collected as X_df.
The data is split
then encoded with OneHotEncoder
then scaled with StandardScaler

There are 2 shared layers for each target.
Department: One hidden layer and one output layer.
Attrition: One hidden layer and one output layer.

A model is created, compiled, and summarized

The model is trained on the post-processed data
The model is then evaluated in the testing data.
The accuracy for both the department and attrition columns are printed.
