#Data Science Task: Predictive Model and Report

###This project covers distint areas such as:
*Data Prepartion and Cleaning
*Exploratory Data Analysis
*Model Building - Linear Regression, KNN (K-Nearest Neighbour Model)
*Model Evaluation

This project is a report on Student Attendence Rates. This project had recieved a 86.25% score (HD), and creates, analyses and assses predictive models based on the provided data set. 
The project utilizes historical data of Student Attence Rates to predict a student's attendence by factors of holidays, academic schedules and weather. 

The dataset within this report has been cleansed to remove any outliers or missing data values to make sure the predictions are accurate, creating summaries to be able to enhance understanding of the dataset.
Graphs have also been created such as Bar Plots, Correllations Matrixes, and Line Graphs to display monthly trends. 

Within the project two Models were selected to be compared and analysed, Linear Regression and K-Nearest Neighbour Model (KNN). 
The Linear Regression Model was trained using variables;  Enrolled, Present, Day, Month, Year against the target variable, Absent.
The model performed poorly at a Mean Squared Error of 729, which are too high for baseline. Although the R^2 value did perform reasonably better, it was not the desired result.

KNN performed very well achieving a lower MSE of 97 and a R^2 value of 0.96. 
Due to this result, the KNN was evaluated further creating a graph but also finding the best "K" for the model.

The project ends with a summary comparing the two models, and suggests that student attendence may be affected by factors of weather, academic schedules or holidays.

