# Time-Series-Analysis
Time Series Analysis of relationship between inflation rate and unemployment rate  over 5 years and forecast ( Philips Cureve Model).

## Table of contents
* [General info](#general-info)
* [Packages](#technologies)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
 Time Series Analysis has been used to analyse relationship between inflation rate and unemployment rate ( Philips Cureve Model). Philips Curve Model is a model which reveals that inflation and unemployment rates are negatively correlated. Data compares 60 period of USA inflation and unemployment rate. With the help of ARIMA model I have forecasted last 10 periods by the use last 50 periods.
 
 ## Result
  I found a huge gap between forecast and real values of last 10 months of 2020. The reason is crisis of pandemic (COVID-19). It is clearly seen from our model that forecasting do not consider crisis in economy. At the final I have tested inflation and unemployed rate with the 'Granger casuality test' if these two variables are dependend on each other. For the high value (0.978) of p-value, we rejected Null hyphothesis.


## Packages
* numpy
* pandas
* matplotlib.pyplot
* matplotlib.mlab
* statsmodels.tsa.stattools
* statsmodels.api
* statsmodels.tsa.arima_model
* seaborn



## Inspiration
Project inspired by the effects of pandemic on the economy.

## Contact
Created by [Kanan Gulmammadli](kenan.gulmemmedli@gmail.com) (kenan.gulmemmedli@gmail.com)  - feel free to contact me!
