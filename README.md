# BoomBikes LR Case Study
> The project aims to predict the demand for shared bikes in the US market to assist BoomBikes in optimizing their business strategy. The company seeks to understand the factors influencing demand and build a predictive model to anticipate future trends.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This model provides a reliable tool for predicting bike sharing demand, accounting for various temporal, environmental, and operational factors. It offers valuable insights for operational planning, resource allocation, and marketing strategies in the bike sharing system. The model highlights the importance of weather conditions, seasonal trends, and yearly growth, providing a solid foundation for business decision-making and expansion strategies for BoomBikes.
- BoomBikes Dataset provided by upGrad is used here.

## Conclusions
### Key Factors and Insights
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

### Practical Implications and Recommendations
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

## Acknowledgements
- This project was inspired by Live Presentation given by Raghuram Bharadwaj and Live Coding Session on LR taken by Dr. DARSHAN INGLE.
- This project is based on upGrad course material on [Linear Regression](https://learn.upgrad.com/course/5803/segment/54603/325204/984745/4919622).


## Contact
Created by [@Arif1234](https://github.com/Arif1234) - feel free to contact me!
