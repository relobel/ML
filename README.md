# Practical Machine Learning
## R.E.Lobel - March 2016
###Course Assignment

The assignment can be accessed as a HTML page at GH_PAGES:
using the following link:   http://relobel.github.io/ML/

The goal of this assignment is to use the sensors data to build a model able to predict how well the Weight Lifting Exercises (WLE) was done and verify its accuracy by testing the built model against 20 provided cases. Two datasets were provided. The first one (pml-training.csv) contains the data from the sensors (predictors) and an output variable (classe), with five factors (A to E), each level defining how well the exercise was done. The second file (pml-testing.csv) has twenty cases, to be used with the model generated from the train dataset to check the accuracy of the chosen model.

The problem was configured as a supervised classification machine learning problem. Two classification methods: "RPART" and "Random Forest" were used to generate the predicting models. 

RPART generated a poor model, with an accuracy of 50% on the out of sample data. Random Forest generated a very good predictive model, with an accuracy over 99% on the out of sample data. 

Therefore we used, with success, the model generated from the Random Forest method to predict the 20 test cases of the testing data set.
