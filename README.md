# **python-api-challenge**

API interactions and analysis of weather data

## **Overview**

This project involves analysis of weather data of about 500 random cities. The weather data was extracted via API interactions and then plotted. The following API's were used for the analysis:

- OpenWeatherMap API
- Google Place and Maps API

The projet is divided into two parts:

1. **Weather Analysis**

Please see **new_weather.ipynb**

 **Tasks**

 The following tasks were completed:

 Create a series of scatter plots to show relationship between the following:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Run linear regression models for the following relationships:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

2. **Plotting weather cities on geo-maps**

Please see **new_vacation.ipynb**

The following tasks were completed:

* Create a heat map that displays the humidity for every city from the part I of the homework.
* Narrow down the DataFrame to find your ideal weather condition:

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

## **Set Up, environment and Installations**

- Jupyter notebook
- Python Environment: Python 3.6

## **Modules, libraries and Packages**

* citipy
* pandas
* numpy
* json 
* requests
* gmaps
* matplotlib
* scipy
