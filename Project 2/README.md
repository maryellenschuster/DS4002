# Project name and introduction
Forecasting the Future: Charlottesville Weather in the Next 500 Years<br>
Mary Ellen Schuster, Sarah Menchavez, Elizabeth Peterson<br>
DS 4002 Project 2<br>

## Software and platform
To perform this analysis, we used a python environment in Virtual Studio code.<br>
The platform used was MacOS.<br>
The add-on packages needed are: 
- import pandas as pd
- from sklearn.preprocessing import MinMaxScaler
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import LSTM, Dense
- from sklearn.metrics import mean_squared_error
- import matplotlib.pyplot as plt
- import datetime
- import seaborn as sns<br>

## Documentation map
LICENSE: gives instructions on how to use and cite this repository<br>
<br>
README.md: guidebook for navigating this repository<br>
<br>
weather.ipynb: all of our data inputting, cleaning, analyzing, and visualizing for this project<br>
<br>
weather_data.csv: the raw weather dataset<br>
<br>
testSet.ipynb: data used to test the LSTM model<br>

<br>

## Instructions for reproduction
To reproduce our results: <br>
- Read in and clean weather_data.csv until all columns are recognizable and do not contain NaN values<br>
- Group by year and calculate the maximum, minimum and average temperature, and precipitation for each year<br>
- Perform LSTM model and get predictions for yearly average temperatures for future years<br>
- Plot actual and predicted yearly average temperature <br>
- Plot yearly average temperatures for the future years <br>
