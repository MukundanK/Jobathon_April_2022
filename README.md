# Jobathon April 2022
by [Analytics Vidhya](https://www.analyticsvidhya.com)

# Demand Forecasting
Can you forecast the demand of the car rentals on an hourly basis?

## Problem Statement
ABC is a car rental company based out of Bangalore. It rents cars for both in and out stations at affordable prices. The users can rent different types of cars like Sedans, Hatchbacks, SUVs and MUVs, Minivans and so on. In recent times, the demand for cars is on the rise. As a result, the company would like to tackle the problem of supply and demand. The ultimate goal of the company is to strike the balance between the supply and demand inorder to meet the user expectations. The company has collected the details of each rental. Based on the past data, the company would like to forecast the demand of car rentals on an hourly basis. 

## Objective
The main objective of the problem is to develop the machine learning approach to forecast the demand of car rentals on an hourly basis.

# Data description
## train
train.csv contains the hourly demand of car rentals from *August 2018* to *February 2021*.

|Variable|	Description|
|--------|-------------|
|date	|Date (yyyy-mm-dd)|
|hour|	Hour of the day|
|demand|	No. of car rentals in a hour|

## Test set
test.csv contains only 2 variables: date and hour. You need to predict the hourly demand of car rentals for the next 1 year i.e. from *March 2021* to *March 2022*.

|Variable|	Description|
|--------|-------------|
|date|	Date (yyyy-mm-dd)|
|hour	|Hour of the day|

# Evaluation metric
The evaluation metric for this hackathon is RMSE score.


