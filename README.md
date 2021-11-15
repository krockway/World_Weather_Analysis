# World Weather Analysis

## Purpose

The purpose of this exercise is to gather and analyze weather data across the world to generate a trip itinerary based on user input temperature ranges.

## Process

In the Weather_Database.ipynb file, I started by generating 2000 random latitudes and longitudes to identify the nearest city, then used an API to collect weather data for those cities. From there, I exported the data into WeatherPy_Database.csv, which was used in the next Jupyter Notebook.

In the Vacation_Search.ipynb file, I prompted the user to input their ideal minimum and maximum temperatures, which generated a new list of preferred cities.

From there, I used the Google Maps API to search for hotels within 5,000 meters of the latitude and longitude. This left me with 229 viable cities that matched the user criteria, which were exported to WeatherPy_vacation.csv and displayed on a map, along with hotel and weather information.

Finally, in the Vacation_Itinerary.ipynb file, I narrowed the list to 4 cities and an itinerary map with driving directions and current weather details was produced.

## Tools & Languages

* Jupyter Notebook
* Python
* APIs - Google Maps & Open Weather
* JSON

## Analysis & Results

The maps

![Map with City Options](https://github.com/krockway/World_Weather_Analysis/blob/main/images/WeatherPy_vacation_map.png)
<i>Map with City Options</i>

![Map with Itinerary Driving Directions](https://github.com/krockway/World_Weather_Analysis/blob/main/images/WeatherPy_travel_map.png)

<i>Map with Itinerary Driving Directions</i>

![Map with Itinerary City and Weather](https://github.com/krockway/World_Weather_Analysis/blob/main/images/WeatherPy_travel_map_markers.png)

<i>Map with Itinerary City and Weather</i>

## Challenges & Next Steps

With more time, I would opt to include more map layers to show interesting landmarks, museums, points of interest and popular restaurants.
