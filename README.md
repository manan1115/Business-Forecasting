# Business-Forecasting

# Project Overview
This project focuses on business forecasting using machine learning techniques. The goal is to predict the order demand for different product categories over the next three years. We utilized historical data spanning from 2011 to 2017 to train our models. Also founded the best product category over the 7 years and which warehouse has provided the maximum sales , in order that the organization can take further action regarding their prouduct sales.

# Dataset Description
The dataset contains the following columns:

Product ID: A unique identifier for each and every product.
Category: The category to which the product belongs.
Warehouse: The location where the product is stored.
Order Demand: The quantity of each product ordered.
The data includes records from a seven-year period (2011-2017), providing a robust basis for trend analysis and forecasting.

# Objectives
Analyzing the historical order demand: Understand the patterns and trends in order demand over the past seven years.
Forecast future demand: Predict order demand for each product category for the next three years.
Improve inventory management: Help businesses optimize their inventory levels based on forecasted demand and to judge whethe to stop the sales from some warehouses which has lead to less sales of the the product as it proves to be un effective area/region for the product.

# Methodology
Data Preprocessing:
Cleaning the data to handle missing values and outliers also handling the order sales demand from string to numeric data.
Aggregating order demand data on a month basis
Encoding categorical variables such as product category and warehouse.

Exploratory Data Analysis (EDA):
Visualizing historical trends in order demand.
Identifying seasonal patterns and trends.
Visualize the trends of sales for each product category also about the warehouses too.

Model Selection and Training:
Implementing time series forecasting models such as ARIMA.
Evaluating model performance using metrics like RMSE and MAE.
Selecting the best-performing model for forecasting future demand.

Forecasting:
Using the selected model to predict order demand for each product category from 2017 to 2023.
Visualizing the forecasted demand to provide actionable insights.


# Results
The forecasted demand for each product category over the next few years was predicted from our model. These forecasts can help businesses plan their inventory, manage supply chains, and make informed decisions about production and launnching of new products in the region where it can be optimized and can sell in more numbers.

# How to Use
1) Clone the repository
2) Navigate to the project directory
3) Install the required dependencies
4) Run the jupyter file 
