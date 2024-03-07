# Predicting the Sale Price of Bulldozers using Machine Learning

This project focuses on constructing a machine learning model aimed at predicting the sale price of bulldozers by analyzing historical data. The goal is to enable stakeholders to make informed decisions based on future sale price projections.

## Project Overview
### 1. Problem Definition
The main question we seek to answer through this project is, "How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?"

### 2. Data
The data for this project is sourced from the Kaggle Bluebook for Bulldozers competition, accessible here. The dataset is split into three main subsets:

* Train.csv: Training data, covering up until the end of 2011.
* Valid.csv: Validation data, from January 1, 2012, to April 30, 2012. This set is used for ongoing prediction and leaderboard ranking.
* Test.csv: Test data, available in the final competition week, spanning May 1, 2012, to November 2012. Performance here determines the final rank.
Due to GitHub's limitations on file sizes, the env and data folders, which include the datasets and environment setup files, are not part of this repository. Participants are encouraged to download the data directly from the provided Kaggle link: https://www.kaggle.com/c/bluebook-for-bulldozers/data

### 3. Evaluation
The project uses the Root Mean Squared Log Error (RMSLE) between the actual and predicted auction prices as the evaluation metric, aiming to minimize this error for improved model accuracy.

More details on the project's evaluation can be found on the competition's evaluation page: https://www.kaggle.com/c/bluebook-for-bulldozers/overview

### 4. Features
A comprehensive list of features within the dataset, such as model details, usage statistics, and physical characteristics, is documented in the data dictionary available on Google Sheets.

### 5. Modelling
After conducting extensive Exploratory Data Analysis (EDA), we progress to model-driven EDA to further understand our dataset and refine our predictions.
To predict the sale price of bulldozers, we employ a RandomForestRegressor, a powerful ensemble learning method suited for regression tasks.

## Key Insights and Model Performance:

* Predictions are stored in the df_preds variable.
* Feature importance analysis indicates significant predictors, including ProductSize, saleYear, and Enclosure.
* These insights open avenues for further model enhancement through advanced feature engineering and parameter optimization.

## Usage Instructions
Given GitHub's file size restrictions, it's necessary to download the data directly from Kaggle and set up the environment accordingly. Follow the steps outlined in the provided Jupyter Notebook for detailed instructions and explanations.
