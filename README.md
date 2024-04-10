# Linear Regression Model on Bike Sharing
> Created a multi-linear regression model on bike-rental dataset to predict the count of shared bike rentals on basis of independent features.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This is a multiple linear regression model for the prediction of demand for shared bikes.
- By this model we can understand the factors affecting the demand for the shared bikes in the American market.
- The business probem that project is trying to solve are
    1. Which variables are significant in predicting the demand for shared bikes.
    2. How well those variables describe the bike demands
- Dataset contain different columns like - 
    dteday, season, yr, mnth, holiday, weekday, workingday, weathersit, temp, atemp, hum, windspeed, cnt etc.


## Conclusions

From the analysis we can conclude that cnt has a linear relationship with few independent variables. I have creadted the model by selecting features using RFE and then manually checked the p-value and VIF of the features and removed the unnecessary features.

From the model we have selected 8 features which help to predict the shared bike count. The model has R-squared value 0.82 and adjusted R-squared value of 0.81 on training data set.
The model is able to successfully predict target value on test data set with accuracy of 80% (R-squared value .80).



## Technologies Used

- Python - version 3.12
- matplotlib - version 3.8.3
- ipython - version 8.21.0
- pandas - version 2.2.0
- seaborn - version 0.13.2
- Scikit-Learn - version 1.4.1
- Statsmodel - version 0.14.1


## Acknowledgements
Give credit here.
- This project was based on www.learn.upgrad.com


## Contact
Created by [@rajashree3] - feel free to contact me!

