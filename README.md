# WeatherPY
A Python script is created to visualize the weather of 500+ cities across the world using the OpenWeatherMap API
A series of scatter plots was created to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Linear regression on each relationship was graphed. The plots were separated into Northern Hemisphere and Southern Hemisphere:
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

# VacationPY
Created a Python script that:
* Created a heat map that displays the humidity for every city from WeatherPY
* Narrowed down the data frame to specifically search for cities that fit the criteria for being in ideal weather locations
* used the Google Places API to find hotels in those cities, and placed a marker on top of the heatmap that included the name of hte hotel, and the city and country it is located in.
