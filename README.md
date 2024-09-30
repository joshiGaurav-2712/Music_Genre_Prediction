# 🎵 Music Genre Prediction Model 🎶

## Overview

This project aims to predict the genre of a song using a Decision Tree Classifier based on various features. It serves as a simple implementation of machine learning principles applied to the music industry, where user data like age and gender is used to predict musical preferences.

## Features

Genre Prediction: Given the user's age and gender, the model predicts the music genre they are most likely to enjoy.

Visualization: Decision tree structure can be visualized for a better understanding of the model's decisions.

## Data

The dataset used for this project is a CSV file (music.csv), containing the following attributes:

Age: Age of the listener.

Gender: 1 for male, 0 for female.

Genre: The target genre label, which is to be predicted.

## Tech Stack

Languages: Python

Libraries:

Pandas: For data manipulation and analysis.

Scikit-learn: For machine learning model implementation.

Matplotlib/Graphviz: For visualizing the decision tree.

## Model

The model used is a Decision Tree Classifier. The following steps are followed:

Data Preparation: Input features (age, gender) are separated from the target label (genre).

Model Training: A decision tree is trained to predict the genre based on the input features.

Model Testing: Sample predictions are made for new user data, and the model's structure can be visualized.
