# Seoul-Bike-Sharing-Demand-Prediction
Seoul Bike Sharing Demand Prediction
We were asked to forecast bike rental demand of bike sharing based on historical usage patterns in relation with weather, time and other data. The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information. Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. Using these Bike Sharing systems, people rent a bike from one location and return it to a different or same place on need basis. People can rent a bike through membership or on demand basis.

Bike sharing systems are a means of renting bicycles where the process of renting bike on the hourly basis is given in this dataset. Certain features will play a major role on Bike Count so by taking care of that we have to make a model that can predict Rental Bike Count by using the independent features present in the dataset.

# Summary

The studied dataset contains weather information which are the features (Temperature, Humidity, Wind speed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall), the target is the number of bikes rented per hour and date information.

In order to implement the model first the data should be prepared, starting with clearing the null values and outliers then log transformation of the variables, removing multicollinearity label and one hot encoding of the categorical variables & more feature engineering processes done and then after that experimented Linear Regression and  Random Forest Regressor.
Dataset used was SoeulBikeSharing.CSV file of 600 kb file consists of 14 columns and 8670 rows.

Functioning day, Temperature are the most influencing feature and temperature is at the second place for Linear Regressor and Random Forest

RMSE Comparisons:

LinearRegressor RMSE: 6.01286448852904

RandomForestRegressor RMSE: 1.476213305948839

GridSearch Cv on Random Forest Regressor RSME: 4.848910689861464


 Random Forest is giving accuracy of 85.07%
 LinearRegressor is giving accuracy of 77%
