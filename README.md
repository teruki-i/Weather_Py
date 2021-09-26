# Weather Analysis and Vacation Itinerary
## Overview

In this analysis, I created a randomly generated set of cities, and used data from OpenWeather to create a Pandas DataFrame containing the cities and their weather data. Cities were left out of this DataFrame if they could not be found in the data from OpenWeather. 

I then filtered this DataFrame for a desired temperature range and searched for hotels using the Google Places API. Cities were removed from the DataFrame if a hotel couldn't be found. Then using Google Maps, I generated a map with markers that show the hotel name, city name, country code, and weather information.

I then selected four cities in this data (Santa Isabel, Brazil; Imbituba, Brazil; Rioja, Argentina; Cordoba, Argentina) to create a trip itinerary. Using Google Maps again, I then generated two maps. One map shows the driving route starting in Santa Isabel, stopping in Imbituba, Rioja, and Cordoba, and then ending back in Santa Isabel. The second map has markers that the show hotel name, city name, country code, and weather information for these four cities.