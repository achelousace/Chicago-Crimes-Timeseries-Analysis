# Chicago Crimes Timeseries Analysis/Modeling
### This project is a data cleaning, wrangling, Timeseries analysis, and Timeseries Modeling for a Chicago Crimes Analysis/Forecasting
#### By: Mohammad Abu Ayyash (Sep 2024)
#### This project aims to analyze and investigate patterns to understand the properties of Chicago Crimes Timeseries that play crucial roles in forecasting and further analyze crimes in chicago city.
#### Data:
dtypes: bool(2), float64(4), int64(2), object(4), 7713109 entries, (total 12 columns), memory usage: 603.2+ MB

#### In this summary you'll find :

![a1](https://github.com/user-attachments/assets/a7efb253-bd5f-413c-8331-d7298badaf35)

* This is the crimes general distribution across the years.

![a2](https://github.com/user-attachments/assets/b6df94c7-9de4-4b08-af49-afb98736301f)

* This is the total crimes general distribution per hour (AM/PM).

![A3](https://github.com/user-attachments/assets/d159b3e7-c1fb-4ff0-895e-2ce84fa9ff29)

* This is crimes distribtion in hourly scale with emphasis on rush hours (AM/PM).

#### Models used with their metrics:

Theft Modleing:
* Model 1:
------------------------------------------------------------
Regression Metrics: 
------------------------------------------------------------
- MAE = 380.619
- MSE = 230,520.402
- RMSE = 480.125
- R^2 = -0.306
- MAPE = 7.79%

* Model 2:
------------------------------------------------------------
Regression Metrics: 
------------------------------------------------------------
- MAE = 211.160
- MSE = 72,805.923
- RMSE = 269.826
- R^2 = 0.587
- MAPE = 4.27%

Narcotics Modeling:
* Model 1
------------------------------------------------------------
Regression Metrics: 
------------------------------------------------------------
- MAE = 48.602
- MSE = 3,063.779
- RMSE = 55.351
- R^2 = -2.300
- MAPE = 12.93%

* Model 2:
------------------------------------------------------------
Regression Metrics: 
------------------------------------------------------------
- MAE = 34.565
- MSE = 1,829.463
- RMSE = 42.772
- R^2 = -0.970
- MAPE = 9.88%

#### Recommendations: 

I would Recommend using Theft Model for theft cirmes forecasting into the future since it has about 96% rate of prediction success as shown below with the metrics.

------------------------------------------------------------
Regression Metrics: 
------------------------------------------------------------
- MAE = 211.160
- MSE = 72,805.923
- RMSE = 269.826
- R^2 = 0.587
- MAPE = 4.27%

![a4](https://github.com/user-attachments/assets/1194bdd2-5738-4f14-b8d2-96e0f5be8aeb)

![a5](https://github.com/user-attachments/assets/4e684687-25f6-4ba6-b980-e04c9c9f6f86)

#### Much more useful information regarding this project is included in the ipynb.
