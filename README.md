# employee-absenteeism-analysis
I got the data from Udemy. The aim of this model is to predict whether employees will be absent for an excessive amount of time on a particular day of the week.
This model's main inputs or features are reasons for absence, education, number of pets and children, age, and distance between office and house.
The Target of this model is absenteeism in hours, if a person is absent for more than 3(median) hours then they are considered absent.
I preprocessed the data by dropping unwanted variables like ID, and mapping and scaling education, and reasons of absence.
Split the model into train and test with 80 percent of training.
Scaled the inputs and used Logistic regression for predicting the output.
Got an accuracy of 63.34 percent because of less data and taking only 3 hours as a limit.
