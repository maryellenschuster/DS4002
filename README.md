# Project name and introduction
Data Science Barbie: Chick Flicks and Data Tricks<br>
Mary Ellen Schuster, Sarah Menchavez, Elizabeth Peterson

## Software and platform
To perform this analysis, we used a python environment in Virtual Studio code.<br>
The add-on packages needed are: 
- import pandas as pd
- import nltk
- from sklearn.model_selection import train_test_split
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import mean_squared_error, r2_score
- from nltk.sentiment.vader import SentimentIntensityAnalyzer
- from nltk.corpus import stopwords<br>
The platform used was MacOS.

## Documentation map
LICENSE: gives instructions on how to use and cite this repository<br>
<br>
README.md: guidebook for navigating this repository<br>
<br>
assignment_1.ipynb: all of our data inputting, cleaning, analyzing, and visualizing for this project<br>
<br>
barbie_Cleaned.csv: the cleaned barbie review dataset<br>
<br>
packages.txt: packages needed for installation<br>
<br>
words.txt: dictionary of words used for training <br>

## Instructions for reproduction
To reproduce our results: <br>
- read in and clean barbie review data set until you have two columns: written review and number rating
- use spacy to extract and identify most common
