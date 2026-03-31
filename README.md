# Sales Data Analysis and Demand Forecasting

## Project Overview

This project analyzes Adidas Retail sales data in 2020 and 2021 in the US to extract meaningful insights and predict future demand. The objective is not only to build forecasting models but also to understand underlying patterns, trends, and drivers of sales performance.
By combining data analysis, visualization, and predictive modeling, the project provides a comprehensive view of demand behavior, supporting better decision-making in areas such as inventory planning, resource allocation, and supply chain management.

## Objective

The main objective of this project is to analyze Adidas sales data and develop predictive models to support demand forecasting.
The project focuses on:
- Identifying trends and patterns in sales data
- Generating business insights through exploratory data analysis
- Visualizing key metrics and demand evolution
- Applying forecasting and machine learning models
  
This integrated approach allows both descriptive and predictive analysis.

## Dataset
The database contains 9,648 observations (rows) and 13 variables (columns). Each observation represents a transaction recorded in Adidas retail operations.
The dataset includes a mix of categorical variables (e.g., retailer, product, region), numerical variables (e.g., sales, units sold, price), and date/time variables (invoice date), enabling both descriptive and predictive analyses.

## Methodology
### 1. Data Preparation and Cleaning

The data was cleaned and preprocessed to ensure consistency and reliability. This included handling missing values, correcting data types, and removing irrelevant variables. The Invoice Date variable was converted into datetime format to enable time-based analysis.

### 2. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand the structure and behavior of the data. Summary statistics and aggregations were used to identify key patterns in sales.

This step allowed the identification of trends, variability, and potential anomalies, providing a foundation for further analysis.

### 3. Data Visualization

Visualization techniques were used to explore and communicate insights effectively. Time series plots were created to observe the evolution of sales over time.

These visualizations helped identify trends, seasonality, and fluctuations in demand, supporting both analysis and decision-making.

### 4. Forecasting Models

Time series forecasting models were applied to predict future demand:

- SARIMA: Captures trend and seasonality using statistical methods
- Prophet: Decomposes the series into trend, seasonality, and residual components
- Moving Average

### 5. Machine Learning Model

A Random Forest regression model was implemented as an alternative predictive approach.


### 6. Model Evaluation

Model performance was evaluated using:
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)

These metrics allow objective comparison of predictive accuracy.

## Technologies Used
- Python
- Google Colab

### Libraries:
- pandas
- numpy
- matplotlib
- statsmodels
- prophet
- scikit-learn
