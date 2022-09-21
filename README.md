# Bike Sharing Linear Regression Assignment
> This project is part of the Linear Regression Assignment Module 2 under course 3 Machine Learning 1

**Problem Statement**

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The requirement is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.


## Table of Contents
* [Jupiter Notebook](https://github.com/thenamankumar/bike-sharing-linear-regression-assignment/blob/main/assignment.ipynb)
* [Subjective Questions](https://github.com/thenamankumar/bike-sharing-linear-regression-assignment/blob/main/Subjective%20Questions.pdf)
* [Dataset](https://github.com/thenamankumar/bike-sharing-linear-regression-assignment/blob/main/day.csv)
* [Definitions](https://github.com/thenamankumar/bike-sharing-linear-regression-assignment/blob/main/definitions.txt)

## Conclusions
- r-square for train data set is 0.84
- r-square for test data set is 0.81
- list of features used for the prediction are:
    - holiday
    - temp
    - windspeed
    - 2019_year
    - spring_season
    - summer_season
    - winter_season
    - jul_mnth
    - sep_mnth
    - mon_day
    - light_snow_weather
    - misty_weather
-  `cnt = 1814.9912 - 919.0795 * holiday + 4269.1786 * temp - 1285.6615 * windspeed + 2028.4443 * 2019_year - 567.6582 * spring_season - 403.0375 * summer_season - 748.0932 * winter_season - 430.8521 * jul_mnth + 659.3979 * sep_mnth - 421.3808 * mon_day - 2524.2332 * light_snow_weather - 726.0744 * misty_weather`
