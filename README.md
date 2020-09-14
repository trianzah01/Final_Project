# Predict Hotel Reservation Cancelation with Machine Learning

## This project is for Final Project on Purwadhika Data Science Course

### The aim of this project is to predict whether this hotel reservation will be canceled or not

Data set is from https://www.kaggle.com/jessemostipak/hotel-booking-demand

It consist of 31 independent variable (categorical and numerical) and 1 dependent variable ('is_canceled' -> 0 = not cancel, 1 = cancel)

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, 
length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

The description of all feature can be read on https://www.sciencedirect.com/science/article/pii/S2352340918315191

## Business Problem


### Workflow of Project:

![Workflow](https://github.com/trianzah01/Final_Project/blob/master/Workflow.png)


## Data Cleaning
a. Checking and Handling Missing Values

b. Checking and Handling Wrong Values

c. Find Outliers

## Exploratory Data Analysis
a. Bookings Trend

b. Repeated Guest on Cancelation

c. Lead Time and Deposit Type on Cancelation

d. Customer Type on Cancelation

## Model Building 

a. __Feature Selection__ : Correlation Matrix, SelectKBest (Chi2 on Categorical Feature, ANOVA on Numerical Feature)

b. __Scalling Data__ : Scalling data on numerical feature that has outliers using RobustScaller

c. __Model__
  * `Logistic Regression`
  * `Decision Tree Classifier`
  * `Random Forest Calssifier`

**Model Flow**

![Model Flow](https://github.com/trianzah01/Final_Project/blob/master/Model%20Flow.png)


**Model Result**

![Model Result](https://github.com/trianzah01/Final_Project/blob/master/Model%20Result.png)

d. __Model Evaluation__

The evaluation metrics that I use are:
1. Classification Report (Accuracy, Recall, Precision, and F1 Score)
2. Confussion Matrix

**Model Evaluation**

![Model Evaluation](https://github.com/trianzah01/Final_Project/blob/master/Model%20Evaluation.png)


## Dashboard

### Home

![Home](https://github.com/trianzah01/Final_Project/blob/master/Home.png)

### Dataset

![Dataset](https://github.com/trianzah01/Final_Project/blob/master/Dataset.png)

### Visualization

![Visualization](https://github.com/trianzah01/Final_Project/blob/master/Visualization.png)

### Predict

![Predict](https://github.com/trianzah01/Final_Project/blob/master/Predict.png)

### Result

![Result](https://github.com/trianzah01/Final_Project/blob/master/Result.png)
