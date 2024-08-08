# Predicting Popular Recipes #

## Overview

This project involves scraping recipe data from Kitchen Stories, processing and analyzing the data, and building predictive models to identify popular recipes based on various features. The analysis includes data extraction, cleaning, feature engineering, and modeling using various machine learning algorithms.

## Features

* **Data Scraping**: Extracts recipe links from different categories on Kitchen Stories.
* **Data Collection**: Gathers detailed information from each recipe page.
* **Data Cleaning**: Handles missing values, converts textual data to numerical, and processes tags.
* **Feature Engineering**: Creates new features and flags for analysis.
* **Exploratory Data Analysis (EDA)**: Visualizes data to understand trends and relationships.
* **Machine Learning**: Applies classification algorithms to predict popular recipes.

## Requirements

* Python 3.x
* Selenium
* BeautifulSoup4
* Requests
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* WordCloud
* Jupyter Notebook (optional for running notebooks)

## Visualizations
* Pie charts for popular recipes and most popular tags.
* Bar charts for mean watchings by author and occurrences of popular words.
* Scatter plots and box plots to analyze relationships between features and recipe watchings.
* Word Cloud to visualize common words in recipe titles.

![image](https://github.com/user-attachments/assets/783986a3-7683-4ba7-b34e-ac077ef2341a)


## Machine Learning Models

**Random Forest Classifier**: Identifies the most important features and predicts popular recipes.

**Decision Tree Classifier**: Determines key features and makes predictions.

**Logistic Regression**: Predicts recipe popularity and identifies significant features.

**Support Vector Machine (SVM)**: Optimizes hyperparameters and classifies recipes.

## Hyperparameter Tuning

Hyperparameter tuning is performed using GridSearchCV to optimize the performance of the machine learning models.
