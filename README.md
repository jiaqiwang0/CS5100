# CS5100 Final Project

## Targeted Environment -- Demonstrate the software resources necessary to build and maintain the product  

We use models in the [statsmodels.tsa] library to perform time series analysis and prediction on the dataset.

## PEAS Environment -- Demonstrating PEAS Environment in the project
1. Agent Type: Internet Covid Forecasting Agent
2. Performance Measure: Provide users with accurate data forecasting 
3. Environment: Internet
4. Actuators: Follow link, choose the data in fields, display to user
5. Sensors: Web page, user requests

## UI page Repository
https://github.com/jiaqiwang0/COVID_Forecasting

## Introduction  

Our goal of this project is to predict the cumulative number of confirmed COVID19 cases in various locations across the world, 
as well as the number of resulting fatalities, for future dates.  

## Dataset  

We use the COVID19 time series data from [John Hopkins CSSE]. This repository is updated once a day.   

At the time we started our project, the data is updated to 17/10/22. Therefore, the visualization and model training are based on the data before that date.  

This link contains the datasets we use.  
https://github.com/CSSEGISandData/COVID-19/tree/2e705aa73ac775b52fa456c090f27b0a39c196b0/csse_covid_19_data/csse_covid_19_time_series  

Because the recovered dataset is not updated after 5/8/21, we use the confirmed and deaths dataset before that date as well for data visualization.  


## How to read the files in our repo

1. data_preprocessiong.ipynb combines the confirmed, deaths, and recovered data, and clean the data. 
2. CS5100_covid_forcasting_visualization.ipynb provides data visualization.
3. CS5100_covid_forcasting_modeling_confirmed.ipynb trains different models for forecasting.
4. CS5100_covid_forcasting_deaths_recovery.ipynb trains different models for death and recovery status.




[statsmodels.tsa]: <https://www.statsmodels.org/stable/tsa.html#module-statsmodels.tsa>
[John Hopkins CSSE]: <https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series>
