# Boombikes Case Study
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
> Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  - This project focusses on BoomBikes aspiring to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.
  - They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends
- What is the business problem that your project is trying to solve?
  - Which variables are significant in predicting the demand for shared bikes?
  - How well those variables describe the bike demands
- What is the dataset that is being used?
  - Fictitious Boom Bikes dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The variables significant in predicting the demand for shared bikes are
  - Year - Demand increases with years
  - Temperature - With increase in Temparature, the demand increases. 
  - Weather (Lightsnow)  - During snow, demand is less, where as clear weather has high demand
- R2 square for train dataset is 0.841 where as for test dataset is 0.805
- Residuals follow a normal distribution with mean centered around zero.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy, pandas
- matplotlib, seaborn-0.13.2
- datetime
- sklearn
- statsmodel
