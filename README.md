# Bike Sharing Demand Prediction By Multiple Linear Regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A US bike-sharing provider, "BoomBikes" has suffered a loss in their revenues due to the Corona pandemic. A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.


**Business Objective:-**
- The main goal of this assignment is to help the company to understand the factors on which the demand for these shared bikes depends. The company wants to know:
    1. Which variables are significant in predicting the demand for shared bikes.
    2. How well those variables describe the bike demands
- To achieve this, we are required to model the demand for shared bikes with the available independent variables. It will be used by the management to manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
### Comparision between Train and Test dataset:
- Train dataset R-squared          : 0.818
- Test dataset R-squared           : 0.8067
- Train dataset Adjusted R-squared : 0.815    
- Test dataset Adjusted R-squared  : 0.7993

### Significant variables to predict the demand for shared bikes:

- yr (year)
- temp (temperature in Celsius)
- windspeed
- season_summer
- season_winter
- mnth_sep (September Month)
- weathersit_bad (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
- weather_moderate (Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist)



## Technologies Used
- Pandas - version 1.0.5
- Numpy - version 1.19.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.0
- Sklearn - version 0.23.1
- Statsmodels - version 0.11.1


## Acknowledgements
- This project was inspired by the Upgrad Team and IIIT Bangalore and helped me to learn a lot about the Exploratory Data Analysis.
- I would be greatful to the IIIT Bangalore as well as the Upgrad Team for providing opportunity to work on such real-time project.


## Contact
Created by [@Divya10Sodha] - feel free to contact me!
