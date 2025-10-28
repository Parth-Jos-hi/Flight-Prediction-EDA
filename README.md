# Flight-Prediction-EDA
Flight prices vary significantly depending on multiple factors such as airline, route, travel date, and stops.
In this project, we perform a detailed exploratory data analysis (EDA) to identify important features and trends that can later be used for building a predictive machine learning model.

This analysis helps in visualizing relationships, handling categorical features, and preparing the data for regression modeling.

🎯 Objectives

Understand how different features influence flight prices

Perform data cleaning and feature extraction from date and time columns

Analyze categorical variables such as airline, source, and destination

Visualize price distributions across various flight routes

Identify outliers and correlations among key features

🛠️ Tech Stack

Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, plotly

Environment: Jupyter Notebook / Google Colab

Dataset Source: Krish Naik’s Flight Price Prediction dataset (Kaggle)

📂 Workflow

Data Import & Overview

Load the dataset and check for null values, datatypes, and duplicates.

Data Cleaning

Handle missing values, format dates, extract day, month, and duration.

Feature Engineering

Split “Duration” into hours and minutes.

Convert categorical features using encoding techniques.

Exploratory Data Analysis

Visualize flight price variations across airlines, sources, and stops.

Detect and understand outliers in pricing.

Insights & Conclusions

Summarize key patterns and relationships for model readiness.

📈 Visualizations

Airline vs Average Ticket Price

Source & Destination Impact on Price

Total Stops vs Price Trend

Duration vs Price Correlation

Boxplots and Violin plots for price distributions

(You can add screenshots later in your images folder.)

💡 Key Insights (Examples)

Airline plays the most significant role in determining price.

Flights with more stops generally cost less, but take much longer.

Evening flights tend to be slightly more expensive.

Travel month and duration are strong predictors of price.

(You can replace these with your exact findings.)

🧠 What I Learned

Real-world data preprocessing and feature extraction

Handling datetime and categorical data efficiently

Using visualization tools to interpret pricing trends

Preparing data for machine learning models
