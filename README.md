# Bike Demand Prediction

> This project involves building a multiple linear regression model to predict the demand for shared bikes based on various independent variables.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Background:** This project focuses on predicting bike-sharing demand to help BoomBikes, a US bike-sharing provider, prepare for increased demand post-pandemic. The goal is to understand which factors affect bike demand and to use this insight to inform business strategies.
- **Business Problem:** BoomBikes is experiencing reduced revenue due to the pandemic and aims to develop a model to forecast bike demand to optimize their operations and increase profitability once the market recovers.
- **Dataset:** The dataset includes daily records of bike rentals, including variables such as weather conditions, season, year, and counts of casual and registered users. The target variable for the model is 'cnt,' which represents the total number of bike rentals.

## Conclusions
- **Conclusion 1:** Significant predictors of bike demand include weather conditions (light snow most negatively affects ridership), temperature, and year. These variables have a meaningful impact on the number of bike rentals.
- **Conclusion 2:** The multiple linear regression model provides a good fit for predicting bike demand, with an R-squared score of 0.8 on the test data.

## Technologies Used
- Python - version 3.11.7
- pandas - version 2.1.4
- numpy - version 1.26.4
- scikit-learn - version 1.2.2
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
- statsmodels - version 0.14.0

## Acknowledgements
- This project was done as part of the IIITB Executive PG Diploma in Machine Learning and Artificial Intelligence course assignment.

## Contact
Created by [@skelkar8] - feel free to contact me!
