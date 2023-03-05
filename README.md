# World_Weather_Analysis

## Overview

This is a visualization analysis for PlanMyTrip. Their new product intends to reccoment cities depending on weather preferences of users.
Through this analysis Google maps and Geoapify Routing was used.  

Real data was used out of Open Weather, Google Maps. 

### Resources
- Open Weather
- Google maps
- Geoapify Routing API
- Python

## Results

The first step was to retrive data form Open Weather to get

- The latitude and longitude
- The Max temperature
- The % humidity
- The % cloudiness
- The Wind speed
- The Weather description, i.e., cloudy, fog, light rain, clear sky, etc.

The data was organized as follows and exported as WeatherPy_Database.csv

<img width="762" alt="Screen Shot 2023-03-05 at 16 52 48" src="https://user-images.githubusercontent.com/114015620/222990532-2b8d3672-eece-496f-b29c-13dd6be54737.png">

The second step was to create a Customer Travel Destinations Map. The input of the user was asked as an example: 

<img width="529" alt="Screen Shot 2023-03-05 at 16 57 23" src="https://user-images.githubusercontent.com/114015620/222990714-16d23db8-9883-409f-aae6-334d1f3f21ed.png">

Temperatures between 75°F and 90°F where used to filter the cities for temperature criteria collected and using google api near hotels were retrived.

The map is presented below using google maps the map was formed.

<img width="975" alt="Screen Shot 2023-03-05 at 16 55 01" src="https://user-images.githubusercontent.com/114015620/222990615-dec97919-9e75-498b-9e4d-3217b4d7c7a2.png">

The last step was to create a Travel Itinerary Map. In this step, Geoapify Routing API was used.

Four cities in Mexico where selected for this itineraty 
<img width="596" alt="Screen Shot 2023-03-05 at 17 00 43" src="https://user-images.githubusercontent.com/114015620/222990868-78b50333-dbde-4ef2-8618-f8c6448c7c76.png">

Itinerary Map.

<img width="661" alt="Screen Shot 2023-03-05 at 16 56 39" src="https://user-images.githubusercontent.com/114015620/222990679-4fb63494-8ee5-42d4-a1b4-304f73eb5319.png">






