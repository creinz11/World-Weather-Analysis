# World-Weather-Analysis

## Overview

For this week's challenge, we were tasked with making enhancements to our travel app. The enhancements required us to continue to use the google maps/locations API, and Open Weather API. In this challenege, we were tasked with generating 2000 random geocoordinates (latitudes and longitudes), and their nearest citires using gmaps. We had three destinct deliverables:

1) A weather database for 2000 randomly generates geoocoordinates
2) A customer-specific travel destination database and map 
3) A travel itinerary map based on four nearby geocoordinates, with corresponding directions and weather information


## Breakdown of Deliverables

Deliverable 1: The changes included 2000 randomly generated latitudes and longitudes. Once we established our data set, we used gmaps to identify the nearest city to our geocoordinates. Once Identifying the nearest city, we used the open weather API to provide Weather data for our locations. Once compiled, the data was exported to a "Weather Database CSV" file tobe used in subsequent deliverables.

Deliverable 2: Based on our newly created Weather Database, we imported the locations and subsequent data. From here, we had users input their desired temperature range. Upon establishig a preference, we screened out database for suitable locations. Once suitable locations were established, we plotted the nearest hotels using the Google Places API, and layered in weather data previosuly retrieved in the open weather API. The below map returned results for a temperature range of 70 to 90 degree farenheit, along with the nearest hotel.

<img width="796" alt="WeathPy_vacation_map" src="https://user-images.githubusercontent.com/80016496/115972108-1ed1ea80-a512-11eb-8376-7890a8b5df04.png">

Deliverable 3: Now that we established our desirable travel universe for our clients, we could create a travel itinerary. The clients in our test case decided on a trip to Texas originating in San Antonio, and stopping in San Patricio, El Campo and Houston. With an sutiable itinerary estabished, we created a directional map using the gmaps directions API. In addition to a directional map, we provided the clients weather and hotel information specific to their itninerary. 

### Directional Intinerary Map

<img width="788" alt="WeatherPy_Travel_map" src="https://user-images.githubusercontent.com/80016496/115972278-031b1400-a513-11eb-9400-3ca97cb5c5b0.png">

### Weather & Hotel Information Map

<img width="790" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/80016496/115972292-14fcb700-a513-11eb-8a38-6d7ce213010b.png">


