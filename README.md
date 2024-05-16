# Project-Data-Analysis

This project analyzes song data from song_data.csv and performs various statistical analyses and machine learning techniques, including linear regression, multiple regression, and Random Forest regression, to predict song popularity. The project also includes data preprocessing steps like handling missing values, removing duplicates, and identifying outliers. Additionally, it covers the visualization of categorical data and the assessment of multicollinearity.

# Project Overview

This project performs the following tasks:

- Loads song data from `song_data.csv`.
- Preprocesses the data by removing duplicates and handling missing values.
- Computes various statistical measures like mean, median, standard deviation, and quartiles.
- Visualizes categorical variables.
- Identifies and removes outliers.
- Encodes categorical variables.
- Calculates correlation coefficients and visualizes them.
- Trains and evaluates linear regression and multiple regression models.
- Trains and evaluates a Random Forest regression model.
- Assesses multicollinearity using Variance Inflation Factor (VIF).
- Performs clustering using KMeans.

# Data Preprocessing

- **Removing Duplicates:** The script identifies and removes duplicate rows from the data.
- **Handling Missing Values:** Checks for and displays columns with missing values.
- **Outlier Detection:** Identifies and removes outliers using the Interquartile Range (IQR) method.

# Exploratory Data Analysis

- **Statistical Measures:** Computes means, quartiles, standard deviations, and medians for numerical columns.
- **Visualization:** Uses Seaborn and Matplotlib to create count plots for categorical variables and scatter plots for regression results.

# Model Training and Evaluation

- **Linear Regression:** Trains a simple linear regression model to predict song popularity based on danceability.
- **Multiple Regression:** Trains a multiple regression model using various features to predict song popularity.
- **Random Forest Regression:** Uses a Random Forest model to predict song popularity and assesses feature importance.
- **Multicollinearity Assessment:** Uses VIF to identify multicollinearity among features and resolves it by removing highly correlated variables.

# Clustering

- **KMeans Clustering:** Applies KMeans clustering to group songs based on their attributes and visualizes the clusters.

Clustering
KMeans Clustering: Applies KMeans clustering to group songs based on their attributes and visualizes the clusters.
