# World_weather_analysis
## Overview:<br/>

Analyze the weather and build a itinerary for customers
About cities around the world and collect, analyze and visualize weather data across cities and provide travelers with a tool that allows them to determine their travel destination based on weather conditions.
### Resources used for analysis:

CSV Files: Weather_Database.csv, WeatherPy_vacation.csv

Jupyter Notebook Files:: Weather_Database.ipynb, Vacation_Search.ipynb, Vacation_Itinerary.ipynb

Python: Python v3.7.6, Dependencies: Pandas, Matplotlib, CitiPy, SciPy, Python Requests, APIs, JSON Traversals.

#### Weather Database:

A random set of 2,000 latitudes and longitudes were generated, and an API call was made on current weather data for the nearest corresponding cities.Also, Weather Map API to collection weather information on over 720 different cities around the world.

The following data was retrieved from the API call:

Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Current Weather description

### Vacation Search :

This folder takes information from the weather database and uses the Google Maps API to map different travel destinations with hotel in each location. Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels and show that with pop-up markers on a marker layer-map.

![pic.png](/Vacation_Search/pic.png)<br/>


### Vacation Itinerary:

Using the Google Directions API, a sample itinerary was created that shows the route between four cities in the United States.

<br/>
![pic1.PNG](/vacation_itinerary/pic1.PNG)<br/>

<br/>
![pic4.PNG](/vacation_itinerary/pic4.PNG)<br/>
<br/>
![pic2.png](/vacation_itinerary/pic2.png)<br/>

<br/>
