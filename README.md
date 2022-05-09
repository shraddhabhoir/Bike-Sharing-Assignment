# Bike Sharing Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is done as part of linear regression assignment.
- Background of project:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- Business probem

They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    -Which variables are significant in predicting the demand for shared bikes.
    -How well those variables describe the bike demands
The requirement was to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

- Used 'day.csv' dataset for this project. 

## Conclusions
- The model with 6 variables [yr, temp, windspeed, season_spring, mnth_Jul, weathersit_C] is finalized.
- Hence, we conclude that these 6 variables are impacting the demand of shared bikes.
- By looking at coefficients top 3 features contributing significantly towards explaining the demand of the shared bikes are
    temp (coef = 0.4279)
    year (coef = 0.2360)
    weathersit_Light Snow, Light Rain (coef = -0.2413)
- This model now can be used further for predictions of the demand of the shared bikes.
## Recommendations
- The demand is more during higher temperatures and clear weather conditions. Hence, company should plan for more demands during these conditions.
- In year 2019, the demand was more. We can interpret that over the time people have got more edcuated towards shared bike rentals. Year on year rise in the demand of shared bikes can be planned.
- During difficult weather conditions like snow and rain, demand of the bikes is going down. Hence, company can plan discounts or any offer to maintain the demand of the bikes.

## Technologies/Libraries Used
- Numpy
- Pandas
- Matplotlib.pyplot
- seaborn
- sklearn
- statsmodels

## Acknowledgements

- This project was inspired by Upgrad's Master of science in Machine Learning and Artificial Intelligence course.
I thank to Subject Matter Expert Mirza Rahim Baig to share his wealth of knowledge. I also thank to other faculty members from IIITB and support team of Upgrad.

- This project was based on Linear Regression.


## Contact
Created by [@shraddhabhoir] - feel free to contact me!
https://github.com/shraddhabhoir



