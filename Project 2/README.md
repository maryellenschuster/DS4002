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
data.csv: the cleaned weather dataset<br>
<br>
<br>
<br>
packages.txt: packages needed for installation<br>
<br>

## Instructions for reproduction
To reproduce our results: <br>
- Read in and clean barbie review data set until you have two columns: written review and number rating<br>
- Use spacy to extract and identify most common adjectives in the reviews<br>
- Apply VADER sentiment analysis to the reviews and add the VADER score as a column to the dataset<br>
- Apply a linear regression model to the data to see if the VADER scores correlate to the user's number rating<br>
- Use the R^2 and Mean Squared Error values to determine the efficacy of the model <br>
