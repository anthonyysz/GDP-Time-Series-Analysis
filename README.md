# GDP per Capita Time Series Analysis

## 1. Introduction
&nbsp;&nbsp;&nbsp;&nbsp; In my final capstone, it was important to me that I try something new, while still applying many of the skills that I had learned throughout my time at Springboard. I wanted to do a time series analysis in order to incorperate my existing skills in python as well as try out new ways to performing a time series analysis. I intended to use data on both population size and GDP per capita from 1952 to 2019 to predict the rate at which the population of the United States would grow as well as it's coresponding GDP per capita.

## 2. Data Analysis
&nbsp;&nbsp;&nbsp;&nbsp; In my initial data analysis phase, I began with setting the dates of each to begin in on the first day of 1952 and end on the last day of 2019. After setting the frequency to the beginning of each quarter, I needed to detrend each dataset for stationarity. After using statsmodels' STL method to determine both datasets contained increasing means, I used differencing to make each dataset stationary.

## 3. Modeling
&nbsp;&nbsp;&nbsp;&nbsp; When modeling, I wanted to try a few different modeling methods to see which one I liked the best. I decided to use an ARIMA model, a Linear Regression model, a Support Vector Regression model, and an XGBoost Regressor. With the creation of all 4 models for each of the 2 datasets, I was able to determine that the ARIMA model would be best suited for making predictions on both datasets. However, I was interested in seeing how the XGBoost Regressor would perform on the GDP per capita data, so I decided that I would test that model out for my forecasting step. 

## 4. Model Analysis
&nbsp;&nbsp;&nbsp;&nbsp; I felt very comfortable using ARIMA models for this data since the raw data was already very linear. I would like to try some type of autoregressive model out on some more complex data to see how it fairs sometime in the future. I also felt very confident in my ability to create multiple different models for forecasting and I feel that I now have a larger repertoire in forecasting circumstances.
