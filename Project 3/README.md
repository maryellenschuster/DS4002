# Project name and introduction
Faces of Feelings: Predicting Emotions using Facial Recognition<br>
Mary Ellen Schuster, Sarah Menchavez, Elizabeth Peterson<br>
DS 4002 Project 3<br>

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
face_data.ipynb: all of our data inputting, cleaning, analyzing, and visualizing for this project<br>
<br>
DATA->Images: the raw facial image dataset<br>

<br>

## Instructions for reproduction
To reproduce our results: <br>
- Read in the Images folder into training, testing, and validation datasets<br>
- Normalize images for training using tensorflow imageGenerator<br>
- Generate and compile CNN model and get accuracy for each emotion prediction <br>
