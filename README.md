# Multiple linear regression project for Bike Share data
Task is to build a multiple linear regression model for the prediction of demand for shared bikes.

## Dataset:
The available original dataset has 730 unique entries with 16 features. 
dataset shape (730,16)

## Target Column:
After analysing the dataset we came to know that, **cnt** will be the target column
its a numerical column variable indicates the total number of bike rentals.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Prepare data, remove non feature columns and clean data as required.
- Mapping and scaling categorial variables **season** and **wathersit**
- Performing Exploratory Data Ananlysis on the dataset to find correlation and other details about the dataset.
- Spliting data into train and test sets (70-30)
- Model building using statistics model library.
- Evaluating model using residual analysis and check R-squared score on the test set

## Technologies Used
- numpy library - version 1.26.4
- pandas library - version 2.1.4
- matplotlib library - version 3.8.0
- seaborn library - version 0.13.2
- statsmodels - version 0.14.0

## Conclusions
- **weathersit** count of total bikes rented is higher when weather is clear and low when it’s cloudy or have light rain that particular day.
- **temp** variable has highest correlation with target variable **cnt** among the numerical variables.
- After model is built **atemp** and **mnth** features has p-value higher than 0.05.They have low significance and will be dropped one by one.
- Variables **temp** has highest correlation, **light_rain has negative correlation and is followed by **yr**.
- Model holds our assumptions and model fits well with test set.


## Acknowledgements
- This is my small project in journey to explore the vast world of data science.
- The dataset and study material are provided by UpGrad
- This project of upgrad program [Case study](https://www.upgrad.com).


## Contact
Created by [@sumitag07 @harshdeep] - feel free to contact me!

