# World_Weather_Analysis
## Overview of Analysis:
Challenged requested three deliverables:
- Obtain current weather information for a list of randomly generated cities. 
- Create a travel destination map that displays a hotel name and the current weather for all the cities on your list.
- Create an Itinerary with a travel map for a circuit of four cities from your cities list. 

## Resources
- API used: OpenWeatherMap API
- Google Specific API used: Direction API, Geocoding API, Maps JavaScript API, Places API
- Software: Python 3.10 (64-bit), Jupyter Notebook 6.4.8

## Summary

Deliverable 1:
- Random list of 2000 latitude and longitude pairs generated using np.random
- Library citipy used to obtain the closest city to each lat and lng pair
- OpenWeatherMap API used to obtain weather info for each city. See table below:

<p align="center">
  <img src="https://github.com/justinkirk8/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database_Example.png" width="700" />
</p>

Deliverable 2:
- Min and Max Temp range requested from user in order to filter data provided in Deliverable 1.
- Google Places API used to find hotel for each city in the filtered list
- Hotel list used to create a map using the library gmaps. Example in image below:

<p align="center">
  <img src="https://github.com/justinkirk8/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png" width="1000" />
</p>

Deliverable 3:
- Four "nearby" cities were chosen
- gmaps.directions was used to create a directions layer map with a circut of the four cities. See image below:

<p align="center">
  <img src="https://github.com/justinkirk8/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png" width="1000" />
</p>

- Finally, gmaps was used to create a map with the hotel and weather info of the four selected cities. See image below:

<p align="center">
  <img src="https://github.com/justinkirk8/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png" width="1000" />
</p>

