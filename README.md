# World_Weather_Analysis
OSU Module 6 WeatherPy with Python APIs
## The purpose of this module was to work with Python and API's to gather relevant data about weather in order to inform a travel itinerary.
 - First we used Python's Random module to create thousands of pairs of geographic coordinates (latitudes and longitudes).
 - Next, we used the citipy module to find the closest corresponding cities to the generated 'locations'.
 - Then we used the unique city results to create a database including lat, long, city and country and current weather conditions.
 <img width="559" alt="Del 1 DB" src="https://user-images.githubusercontent.com/46324081/147859110-8134390f-3eb0-4257-8752-1b5c1138805e.PNG">

## The second section made use of google maps apis to generate maps and visualizations for our trip.
![](Vacation_Itinerary/WeatherPy_travel_map.PNG)

## Resources
 - Conda 4.10.3
 - Python 3.7.11
 - Pandas
 - gmaps
 - Numpy
 - requests 2.26.0
 - API's
   - https://openweathermap.org/api
   - https://console.cloud.google.com/google/maps-apis
