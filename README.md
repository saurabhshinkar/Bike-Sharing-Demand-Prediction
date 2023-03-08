# Bike Sharing Demand Prediction
## Abstract

Bike sharing as we know is a transport service primary focus to lend conventional or electrical bikes to an individual or a group of individuals in order to let them travel in city or outskirt in rent for an hour, a day or for a month depending on the needs.

In market share we can see that Bike Sharing system has a global market share which was valued around 3.39 billion Dollars in 2019 and is projected to grow to 6.98 Billion Dollars by 2027 with a compound annual growth rate of around 14% indicatively from 2020 to 2027.

Several factors such as low bike rent, increase in capital investments,introduction of e-bikes in the market, technological advancement and government schemes for development of several bike-sharing infrastructure has increased the overall market share and led to the introduction of several opportunities during the forecasted year. However, rise in bike theft and huge initial investment are some of the key factors in order to hinder expected market growth.

Keywords: Bike-Sharing, Data Mining, Predictive Analysis, Linear Regression, Machine Learning.

## Introduction
Bike sharing system demand nowadays is increasing in proportional manners globally. This system has gained a lot of attention with its cost effective system and easy to use nature. This system has already attracted a huge customer base globally like in South Korea, São Paulo ,China and Australia. Bike sharing system generally rents bikes on an hour, day and month basis and is generally based on static pricing inclusive of hour,days or month. Because of its affordability and easy renting system anyone can commute on arrival. According to our problem our main aim is to build a predictive model so as to find the number of bikes rented based on the given dataset.

## Problem Description:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

### Data Description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

#### Attribute Information:
- Date : year-month-day
- Rented Bike count - Count of bikes rented at each hour
- Hour - Hour of he day
- Temperature-Temperature in Celsius
- Humidity - %
- Windspeed - m/s
- Visibility - 10m
- Dew point temperature - Celsius
- Solar radiation - MJ/m2
- Rainfall - mm
- Snowfall - cm
- Seasons - Winter, Spring, Summer, Autumn
- Holiday - Holiday/No holiday
- Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## Conclusions
1. Linear Regression Model Has Accuracy Of 65%.

2. Decision Tree Has Accuracy Of 82%.

3. Decision Tree With Hyperparameter Tuning Has Accuracy Of 80%.

4. Random Forest Has Accuracy Of 91%.

5. Random Forest With Hyperparameter Tuning Has Accuracy Of 84%

6. Gradient Boosting Has Accuracy Of 87%.

7. Gradient Boosting With Hyperparameter Tuning Has Accuracy Of 73%.

8. XG Boost Has Accuracy Of 87%.

9. XG Boost With Hyperparameter Tuning Has Accuracy Of 92%.

10. From Above We Can Conclude That XG Boost With Hyperparameter Tuning Is The Best Fitted Model To Our Data.
XG Boost With Hyperparameter Tuning Gives About 97% Accuracy In Training Data And 92% Accuracy In Test Data. Also XG Boost Has Lowest Mean Squared Error In Test Data.

11. Seasons, Temperature, Hour, Functioning Day, Humidity are the most important features which affects our Target variable.

## References
1. GeekforGeeks
2. Kaggle
3. Analytics Vidya
