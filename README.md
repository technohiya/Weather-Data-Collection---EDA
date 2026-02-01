# Weather-Data-Collection - EDA
Weather Data Collection Using OpenWeatherMap API


## Table of Contents
- [Overview](#Overview)
- [Prerequisits](#Prerequisits)
- [Work Flow](#Work_Flow)
- [Limitations](#Limitations)
- [Future Work](#Future_Work)

## Overview

The aim of the project is to collect daily weather data from a API and performing exploratory data analysis followed by building a predictive model to predict weather conditions. Daily weather data is collected by API call using OpenWeatherMap API
for the month of November (11th to 20Th). The collected data has been consolidated in a single CSV file for further data cleaning. 
Steps like adding a new column, deleting null rows, finding outliers have been performed to enrich the data for firther exploratory analysis. Finally machine learning models like Decission Tree Classifier and random Forest Classifier have been build to predict weather condition.

## Prerequisits
Following Python Libraries have been used:
- pandas
- numpy
- matplotlib
- sklearn
- seaborn
Install dependencies using:
- pip install pandas numpy matplotlib sklearn seaborn


## Work Flow
1. ***Data Collection:*** Data is collected for multiple days for the month of November and saved in CSV files. These CSV files have been imported into a data frame and combined. This combined data is then saved in 'combined_weather_data.csv' file.
2. ***Data Cleaning:*** As part of data cleaning, differnt approaches have been implemented like elliminating rows with missing key information, renaming column names for consistancy, converting timezone to hours for easy understanding, finding outliers and adding additional column for continents.
3. ***Exploratory Data Analysis:*** Examining weather trends in Asia and Europe using different visualization techniques
and exploring correlational analysis.
4. ***Building Predictive Models:*** Training models like 'Decision Tree' and 'Random Forest' to predict weather conditions and reasoning the limitations of the models.


## Limitations

Main limitaion here is the small dataset. The accuracy level of the predictive models are low due to this reason. A larger data set will help the model train better and have better accuracy. The data set can also have more features as there are multiple factors effecting the weather condition.


## Future Work

The project can be expanded with a larger dataset by collecting data over a larger period of time and taking more cities across the globe into account. EDA can be expanded this way and can be done on other continents also. A larger data set can also help in bulding better predictive models.
