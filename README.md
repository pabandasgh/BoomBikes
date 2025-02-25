# Project Name
BoomBikes Bike Sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

The company wants to know:
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
- The Most Signficant features(Top 5) to understand rental bike demands are temp, Light Snow/Rain, yr, windspeed and humidity.
- Final Model built on training data set explains 83.9% of the variability and achieves 80.70% on test data.
- The equation of best fitted line of the final model is :
cnt=0.1712+ 0.2286x yr+ 0.0524x workingday+ 0.5960x temp-0.1709 x hum-0.1888 x windspeed+0.0827 x summer+0.1355 xwinter-0.0439 x July+0.0928 x September+0.0625 x Saturday-0.0536 x Cloudy-0.2391 x Light Snow/Rain 
where temp ,hum and windspeed are normalized.
- The demand appears to rise on on good weather days with high temperature. Therefore, the company should consider offering promotions or discounts during during those days. This strategy will help maximize the number of rental bike transactions.


## Technologies Used
Python 		- Version 3.11.9
numpy	 	- Version 2.1.3
pandas 		- Version 2.2.3
seaborn 	- Version 0.13.2
scikit-learn - Version 1.6.1
statsmodels - Version 0.14.4
jupyterlab	 - Version 4.3.2
matplotlib 	- Version 3.10.0


## Acknowledgements

- This project was based on...Upgrad Machine Learning Linear Regression Assignment 


## Contact
Created by [@pabandasgh] - feel free to contact me!
