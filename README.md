# BoomBikes: Bike-Sharing Demand Prediction with Linear Regression
The project aims to predict the demand for shared bikes in the US market to assist BoomBikes in optimizing their business strategy. The company seeks to understand the factors influencing demand and build a predictive model to anticipate future trends.

## Table of Contents
* [General Information](#general-information)
* [Problem Statement](#problem-statement)
* [Methodology](#methodology)
* [Key Factors and Insights](#key-factors-and-insights)
* [Practical Implications and Recommendations](#practical-implications-and-recommendations)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This model provides a reliable tool for predicting bike sharing demand, accounting for various temporal, environmental, and operational factors. It offers valuable insights for operational planning, resource allocation, and marketing strategies in the bike sharing system. The model highlights the importance of weather conditions, seasonal trends, and yearly growth, providing a solid foundation for business decision-making and expansion strategies for BoomBikes.
- BoomBikes Dataset provided by upGrad is used here.

## Problem Statement
BoomBikes, a US-based bike-sharing provider, has been negatively impacted by the COVID-19 pandemic. To prepare for post-pandemic recovery and gain a competitive edge, they aim to:

Identify key factors influencing bike-sharing demand in the post-COVID scenario.
- Develop a data-driven model to estimate daily bike rental demand.
- Quantify the impact of various factors on bike-sharing usage.
- Provide actionable insights to optimize operations and marketing strategies.

This analysis leverages a comprehensive dataset containing daily bike demand data, meteorological information, and other relevant factors to achieve these objectives.

## Methodology
### 1. Exploratory Data Analysis (EDA):
- Understand patterns and relationships in the data through visualization and statistical analysis.
- Identify potential data quality issues and address them accordingly (missing values, outliers, etc.).

### 2. Data Preprocessing:
- Prepare the data for modeling by encoding categorical variables, handling missing values, and potentially creating new features if necessary.

### 3. Model Selection and Training:
- Build a multiple linear regression model to predict bike-sharing demand based on significant features identified in the EDA.
Train the model on a portion of the data using appropriate methods like train-test split.

### 4. Model Evaluation:
- Evaluate the model's performance on unseen data using metrics like R-squared, Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

### 5. Feature Importance:
- Analyze the relative importance of different features in predicting demand. This guides resource allocation and marketing strategies.

## Key Factors and Insights
- Most influential factors:
    * Temperature (coef: 0.4384)
    * Year trend (coef: 0.2342)
    * Working day (coef: 0.0543)
- Negative impacts:
    * Light Rain/Snow (coef: -0.2964)
    * Windspeed (coef: -0.1650)
    * Mist (coef: -0.0835)
- Seasonal effects:
    * Winter (coef: 0.1339)
    * Summer (coef: 0.0766)
- Monthly patterns:
    * Higher demand: September (coef: 0.0974), August (coef: 0.0446)
    * Lower demand: January, December, February, November
- Day of week effect:
    * Saturday shows higher demand (coef: 0.0647)
    * Indication of higher use on Wednesday, Thursday, and holidays

## Practical Implications and Recommendations
- Weather and seasonal factors crucial for demand prediction
- BoomBikes popularity is growing year-over-year (2019 > 2018)
- Operational adjustments:
    * Increase capacity during favorable weather conditions
    * Implement strategies for low-demand periods (e.g., rainy days)
- Marketing strategies:
    * Aggressive marketing in summer and spring
    * Strong push in the first 6 months of the year
    * Develop incentives for less favorable weather conditions
- Customer retention:
    * Analyze and implement strategies to retain repeat customers
    * Capitalize on growing popularity and exposure


## Technologies Used
- [Python - Version 3.11.7](https://www.python.org/)
- [Numpy - Version 1.26.4](https://numpy.org/)
- [Pandas - Version 2.1.4](https://pandas.pydata.org/)
- [matplotlib - Version 3.8.0](https://matplotlib.org/stable/)
- [seaborn - Version 0.12.2](https://seaborn.pydata.org/index.html)
- [Jupyter Notebook - Version 7.0.8](https://jupyter.org/)
- [JupyterLab - Version 4.0.11](https://jupyter.org/)
- [Anaconda Navigator - Version 2.5.2](https://www.anaconda.com/products/navigator)
- [sklearn](https://scikit-learn.org/stable/)
- [statsmodels](https://www.statsmodels.org/stable/index.html)

## Conclusions
- The developed linear regression model demonstrates strong predictive power in forecasting bike-sharing demand, accurately capturing the influence of various factors such as weather, seasonality, and day-of-week effects. The model's performance is robust, with consistent results on both training and testing data, indicating its reliability in real-world applications. Key insights derived from the model include the significant impact of temperature and year-over-year growth on demand, as well as the negative influence of adverse weather conditions. These findings offer valuable guidance for BoomBikes to optimize their operations, marketing strategies, and resource allocation. By leveraging the model's predictions and recommendations, BoomBikes can effectively anticipate and meet customer demand, enhance operational efficiency, and capitalize on the growing popularity of bike-sharing services.

## Acknowledgements
- This project was inspired by Live Presentation given by `Raghuram Bharadwaj` and Live Coding Session on LR taken by `Dr. DARSHAN INGLE`.
- This project is based on upGrad course material on [Linear Regression](https://learn.upgrad.com/course/5803/segment/54603/325204/984745/4919622).


## Contact
Created by [@Arif1234](https://github.com/Arif1234) - feel free to contact me!
