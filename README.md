# Spotify Hit Song Predictor

## Project Overview
This project aims to develop a machine learning model capable of predicting whether a song will enter top 10 after entering the top 200 songs on Spotify based on its song features alone. These song featues include danceability, energy, key, loudness, and more.

The task was condensed into a binary classification problem and also explored class imbalance techniques.


## Installation
Before running the notebook, ensure you have Python installed on your system. Then, install the required libraries using the following command:
pip install -r requirements.txt

## Dataset overview
This is a complete dataset of all the "Top 200" playlist published globally by Spotify. Spotify introduces a new playlist each day. This dataset contains all the playlists since January 1, 2017 to May 29, 2023.
It contains more than 650k rows, which comprises 467800 songs.This dataset has been collected from Spotify's regional chart data. In addition, this dataset has been substantially enriched with supplementary information.
The dataset used in this project consists of various features extracted from songs on Spotify. 

Dataset link: https://www.kaggle.com/datasets/brunoalarcon123/top-200-spotify-songs-dataset/data


## Features and Model
The project explores different feature engineering techniques and compares multiple machine learning models, including Logistic Regression, Decison tree and Random Forest, to predict song popularity. Special attention is given to addressing class imbalance using random oversampling.

## Evaluation
The model's performance is evaluated using metrics suitable for binary classification tasks, such as accuracy, precision, recall, F1 score, and the ROC-AUC curve.
