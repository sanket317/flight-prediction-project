# Flight Fare Prediction Project

## Overview

This project aims to predict flight fares based on various features such as airline, source, destination, date of journey, duration, and more. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and building a machine learning model to predict flight fares.

## Dataset

The dataset used in this project contains information about flight fares, including features such as:

- **Airline**: The airline company.
- **Date_of_Journey**: The date of the flight.
- **Source**: The departure city.
- **Destination**: The arrival city.
- **Route**: The route taken by the flight.
- **Dep_Time**: Departure time.
- **Arrival_Time**: Arrival time.
- **Duration**: Total duration of the flight.
- **Total_Stops**: Number of stops in the flight.
- **Additional_Info**: Additional information about the flight.
- **Price**: The target variable, representing the flight fare.



## Data Preprocessing

The data preprocessing steps include:

1. **Handling Missing Values**: Dropping rows with missing values.
2. **Feature Engineering**: Creating new features such as journey day, journey month, departure hour, departure minute, arrival hour, arrival minute, duration hours, and duration minutes.
3. **Encoding Categorical Variables**: Converting categorical variables into numerical format using one-hot encoding.
4. **Splitting the Data**: Splitting the dataset into training and testing sets.

## Exploratory Data Analysis (EDA)

The EDA involves:
- **Summary Statistics**: Understanding the distribution of numerical features.
- **Visualizations**: Using seaborn and matplotlib to visualize relationships between features and the target variable.
- **Correlation Analysis**: Identifying correlations between features.

## Model Building

The machine learning model is built using the following steps:

1. **Feature Selection**: Selecting relevant features for the model.
2. **Model Training**: Training a regression model (e.g., Linear Regression, Random Forest) on the training data.
3. **Model Evaluation**: Evaluating the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Results
The model's performance is evaluated on the test set, and the results are summarized. The best-performing model is selected based on the evaluation metrics.
