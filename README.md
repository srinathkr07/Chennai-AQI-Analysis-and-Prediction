# Analysis and Prediction of Daily AQI of Chennai

This repository contains the code for analysing and predicting the daily Air Quality Index (AQI) of Chennai, India using historical data from May 2015 to December 2023.

The dataset was downloaded from UrbanEmissions.Info and can be found here: https://urbanemissions.info/india-air-quality/india-ncap-aqi-indian-cities-2015-2023

Analyses performed:

i) Visualising the average AQI for each month across different years as a heatmap.

ii) Visualising the daily AQI values as a calendar plot.

iii) Visualising the number of days each air quality category ('Good', 'Satisfactory', 'Moderate', 'Poor', 'Very Poor') occurred per year as a heatmap.

(iv) Finding the number of days a pollutant was a prominent pollutant for each month across different years. 

Prediction:

Used a sequential neural network model with two **LSTM** layers followed by two dense layers.

Obtained a root mean squared error of 6.207 on the test split (20% of the overall data). 
