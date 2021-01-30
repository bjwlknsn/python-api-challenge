# python-api-challenge

## Part I - WeatherPy

A Python script was used to visualize the weather of 500+ randomly selected cities across the world of varying distance from the equator.

A series of scatter plots were created to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Then linear regression was run on each relationship seperated into plots by Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

An obervable trend is that from the equator, the max temperature decreases as the latitude increases.

### Part II - VacationPy

Use jupyter-gmaps and the Google Places API to work with the weather data created in Part I to plan future vacations.

A heat map was created that displays the humidity for every city from Part I.

Then the DataFrame was narrowed down to find ideal weather conditions, and the Google Places API was used to find the first hotel for each city located within 5,000 meters of the coordinates. These hotels were then plotted on top of the humidity heatmap.