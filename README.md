# API-Challenge

## Part I-WeatherPy

A Python script was created to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this task, a Python library and Open Weather Map API was utilized.

A series of scatter plots were created to display the following information:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

![](cloudiness_vs_latitude.png)

A series of scatter plots were created with a linear regression on each relationship. The plots were separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
*	Northern Hemisphere - Temperature (F) vs. Latitude
*	Southern Hemisphere - Temperature (F) vs. Latitude
*	Northern Hemisphere - Humidity (%) vs. Latitude
*	Southern Hemisphere - Humidity (%) vs. Latitude
*	Northern Hemisphere - Cloudiness (%) vs. Latitude
*	Southern Hemisphere - Cloudiness (%) vs. Latitude
*	Northern Hemisphere - Wind Speed (mph) vs. Latitude
*	Southern Hemisphere - Wind Speed (mph) vs. Latitude

## Part II-VacationPy

Jupyter-gmaps, and Google Places API was utilized to create a heat map that displays the humidity for every city from the part I.

![](heat_map_humidity.png)

In addition, a DataFrame was created to identify locations around the world with perfect weather conditions:
*	A max temperature lower than 80 degrees but higher than 70.
*	Wind speed less than 10 mph.
*	Zero cloudiness.

