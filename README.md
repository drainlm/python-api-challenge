# Python API Challenge README

WeatherPy and VacationPy scripts visualize weather for cities around the world using data from OpenWeatherMap API and Geoapify API.


WeatherPy 

This code uses citipy to generate a random list of cities and OpenWeatherMap API for current weather data (max temp, humidity, cloudiness, and windspeed). This data is then visualized in a series of scatter plots and linear regression plots to understand the relationship between latitude and weather (temperature, humidity, cloudiness, and wind speed).


VacationPy

This code uses data from WeatherPy (cities.csv) to find possible vacation destinations with ideal weather (18-26C highs with a windspeed less than 3m/s and cloudiness less than 10%). It then uses Geoapify to find the nearest hotel for each city that meets the ideal weather criteria. Using GeoViews, a dynamic map is then created where there are points on the map that you can hover over to gather additional details (longitude, latitude, humidity, city, hotel name, and country).
