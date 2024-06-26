# Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Below are the predictor variables:
1. workingday
2. weekday 
3. hum  
4. temp 
5. month  
6. weathersit    
7. windspeed  
8. yr 
----------
1. Humidity coefficient comes out to be -0.29 indicating that a unit increase in humidity decreases the bike hire numbers by 0.29 units.
2. Coefficient of temperature comes out to be 0.56 indicating that a unit increase in temp variable increases the bike hire numbers by 0.56 units. 
3. Bike hire numbers seems to be more in the month of august and september.
4. Coefficient of year comes out to be 0.23 which means a unit increase in year increases the bike hire numbers by 0.23 nits means people might prefer to rent a bike post covid instead of travelling via public transport.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
sklearn: '1.2.2'
pandas: '1.5.3'
numpy: '1.24.3'
seaborn: '0.12.2'
statsmodel: '0.13.5'

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad IITB Programme
- This project was based on Machine learning and Artificial Intelligence Linear Regression concepts.


## Contact
Created by [@Prashaliverma] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
