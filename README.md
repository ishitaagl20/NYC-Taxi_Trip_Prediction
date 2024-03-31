# Taxi Trip Duration Prediction

Predicting taxi trip durations using machine learning algorithms on the NYC Taxi Trip dataset.

# Certificate
![image](https://github.com/ishitaagl20/NYC-Taxi_Trip_Prediction/assets/90683051/00178bfc-9797-4081-b788-50a272ae29cd)

## Introduction

This project focuses on predicting the duration of taxi trips in New York City using machine learning techniques. The analysis involves exploring the NYC Taxi Trip dataset, preprocessing the data, building predictive models, and evaluating their performance. The goal is to develop accurate prediction models that can contribute to optimizing transportation logistics and enhancing passenger experiences.

## Data Overview

The NYC Taxi Trip dataset contains essential information such as pickup time, geographic coordinates, passenger counts, and other relevant attributes. The data is sourced from the NYC Taxi and Limousine Commission (TLC) and offers insights into the dynamic taxi ecosystem of New York City.

## Data Preprocessing

Data preprocessing involves essential steps like feature engineering, handling outliers, and formatting date and time attributes for analysis. Attributes like distance and speed are computed using geographical coordinates, and outlier removal is performed to enhance data quality.

## Exploratory Data Analysis

Exploratory data analysis (EDA) is conducted to gain insights into attribute distributions, correlations, and patterns within the data. EDA helps identify trends and relationships that inform feature selection and model building.

## Model Building

Multiple machine learning algorithms, including Linear Regression, Decision Trees, Gradient Boosting, XGBoost, and Random Forest, are employed to build predictive models. Features are selected based on their anticipated influence on trip duration, and the models are trained using preprocessed data.

## Model Evaluation

The models are evaluated based on accuracy metrics and training times. Accuracy is measured using the coefficient of determination (R-squared) score. The computational efficiency of each algorithm is also documented.

## Conclusion

The project concludes that Decision Tree and XGBoost are standout choices for accurate trip duration prediction. Decision Tree demonstrates efficient execution and high accuracy, while XGBoost offers a balance of accuracy and training time. The models provide insights into travel patterns and contribute to optimizing transportation logistics.

#### This project was done as a part of a simulated summer internship with capabl.


## Getting Started

To run this project locally, follow these steps:

1. Clone this repository.
2. Install the required dependencies (see Dependencies section below).
3. Run the provided Jupyter Notebook or Python scripts for data preprocessing, exploratory data analysis, and model building.

## Dependencies

This project requires the following dependencies:

- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

Install the dependencies using the following command:

```bash

pip install pandas scikit-learn matplotlib seaborn xgboost


