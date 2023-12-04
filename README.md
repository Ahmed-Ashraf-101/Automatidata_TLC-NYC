# Automatidata_TLC-NYC
The first end-of-course workplace scenario in Google Advanced Data Analytics Certificate.
Predicting Taxi Fares in New York City

Project goal:
In this fictional scenario, the New York City Taxi and Limousine Commission (TLC) has approached the data consulting firm Automatidata to develop an app that enables TLC riders to estimate the taxi fares in advance of their ride.

Background:
Since 1971, TLC has been regulating and overseeing the licensing of New York City's taxi cabs, for-hire vehicles, commuter vans, and paratransit vehicles. New York City TLC stakeholders have been impressed with the data analytical work completed by the Automatidata. As a result, they have reached out once again for assistance in creating a machine learning model that can help predict the taxi fares in advance.

Business Understanding 
The goal of this project was to create a multiple linear regression, random forest model and extreme gradient boost model to predict taxi fares in advance. This project utilized yellow taxi trips taken in New York City during 2017. The final random forest model performed with determination coefficient (R^2) of  87% determining what features were most important in predicting taxi fares. Based on the model, the mean duration and mean distance were most influential in determining the taxi fares in advance. 

Data Understanding
The NYC Taxi and Limousine Commission data came from NYC.gov. The data consisted of approximately 23k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type.In connection to this, a feature was engineered to represent if a ride was taken during rush hour or not. Multiple redundant columns were dropped and reformatted into the proper data type.

Modeling and Evaluation 
A random forest model comprising 200 decision trees was used to determine feature importance in predicting taxi fares. The overall model performed with 87% R_squared, 2.13 Mean absolute error, 15.32 Mean squared error and 3.91 Root mean squared error on the testing data.

Conclusion
This model can benefit Taxi Riders in knowing how much they will pay for the ride in advance; however, running a parametric model to determine how much each variable will influence the actual price of the trip, we observed that the mean distance of the trip is the most influential factor in estimating the taxi fares in advance with relative importance of 92.58%. In the future, adding more information on a rider’s past behavior may also be beneficial in helping the stakeholder address their business problem.
