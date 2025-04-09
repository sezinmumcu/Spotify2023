# Spotify Top Songs 2023 Analysis

## Project Overview
This project analyzes the most popular songs on Spotify in 2023. It uses a comprehensive dataset that includes various attributes of songs, such as their popularity, presence on different music platforms, and audio features. The main goal is to predict the total number of times a track has been streamed based on playlist data, chart positions, and musical characteristics.

## Dataset
The dataset used in this project contains information about the top Spotify songs of 2023. It includes the following details for each song:
- Track name and artist(s)
- Release date
- Presence in Spotify playlists and charts
- Streaming statistics
- Presence on Apple Music and Deezer
- Shazam chart positions
- Audio features (BPM, key, mode, danceability, valence, energy, acousticness, instrumentalness, liveness, speechiness)

Dataset source: [Kaggle - Top Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data)

## Tools and Libraries
This project uses Python and the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Analysis Steps
1. Data loading, initial exploration, and data visualisation
2. Data preprocessing and feature selection
3. Model selection and training
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Support Vector Regressor
4. Model evaluation using cross-validation
5. Hyperparameter tuning using GridSearchCV
6. Final model selection and performance evaluation

_Examples from the Exploratory Data Analysis_: 
![Unknown-2](https://github.com/user-attachments/assets/b6164cf2-4d96-48f6-8b09-39cf90c0774c)

![Unknown-1](https://github.com/user-attachments/assets/1fa61e4b-6c91-4e8f-baaf-4e051be158ea)
