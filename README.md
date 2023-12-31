# Stedin Grid Congestion Forecast: A Data Science Approach to Predictive Grid Management 🌐⚡️
This repository is the home of an innovative solution developed to optimize the electricity grid managed by Stedin, ensuring over 2 million households in the Netherlands have reliable and efficient energy distribution. By leveraging data science and machine learning, we're on a mission to predict and prevent grid congestion before it occurs.

## Problem Statement 📢
In the face of ever-increasing energy demands and the integration of renewable energy sources, our electricity grids are pushed to their limits. Congestion can lead to outages and the need for costly infrastructure upgrades. This project addresses these critical challenges by creating a predictive model capable of forecasting electrical load peaks, allowing for proactive measures to mitigate potential congestion issues. 

## Project Aim 🎯
The primary goal of this project is to build a predictive model that not only forecasts the grid load 48 hours into the future but also serves as a decision-support tool for the operators at Stedin. With this model, we aim to:

- **Predict Load Peaks:** Identify the times when the grid is likely to experience peak loads.
- **Prevent Congestion:** Provide actionable insights to avoid grid congestion.
- **Support Decision Making:** Aid operators in making informed decisions to manage the grid efficiently. 

## Proposed Solution 💡
Our strategy involves short-term probabilistic forecasting using LightGBM for Quantile Regression. This method doesn't just offer a single-point forecast, it provides a detailed distribution of possible outcomes at different probabilities. With this information, Stedin operators can gauge the certainty of various load scenarios, allowing for strategic decisions to effectively manage and prevent grid congestion.

## Project Structure 📁
The project is structured as follows:
1. `01_Data_Analysis.ipynb`: This notebook is dedicated to a thorough examination of the dataset by performing data cleaning, feature engineering, and data visualizations.
2. `02_Predictive_Modelling.ipynb`: Training and evaluation of the LightGBM predictive model. The evaluation of the model includes performance metrics, feature importance analysis, and error analysis.
3. `03_Forecasting.ipynb`: Short-term Forecasting of grid load for the next 48 hours. This notebook emphasizes the practical application of the predictive model in grid management.
