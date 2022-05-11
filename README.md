# World_Weather_Analysis


## Project Overview
A PlanMyTrip app was built with data from two APIs, OpenWeatherMap and Google Maps Directions. The PlanMyTrip app has three components:
1. Vacation Search: Allow users to enter a min and max temperature range, and with that information, the app will retrieve the nearest city with a description of the city's weather that fits within the temperature range desired by the user.

2. Customer Travel Destinations Map: Generate a world map using Google Maps API that marks all cities that fit the weather parameters (min and max temp) entered by the user. The markers should include pop-up info boxes that show the hotel name, city name, country code, and current weather description to the user.

3. Travel Itinerary Map: Build a map that visually shows a travel route between four cities in the same country. The purpose is to visually represent a vacation travel plan to the user. 

## Resources
- Python 3.9.7
- Pandas version 1.3.4
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Google Maps API, Plcae Search](https://developers.google.com/maps/documentation/places/web-service/search-nearby)
- [CityPy](https://github.com/wingchen/citipy)

## Results

### Deliverable 1
1. Generated a large set of random latittudes and longitudes using numpy, `np.random.uniform`.
2. Used CityPy library to find nearest city from the random lats and longs list.
3. Got weather data of each city from OpenWeatherMaps API.
4. Created a dataframe with all city weather information for each city, and exported it to a CSV.

### Deliverable 2
![Vacation Search](/Vacation_Search/WeatherPy_vacation_map.png)

### Deliverable 3
![Travel Map Markers](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

## Summary

An application was successfully built that allowed the user to enter a min and max temperature range, and then see a map of cities that fit the weather criteria. A range of 75 to 90 degrees F was used. From that filtered list of cities, a vacation was planned in Somalia to visit 4 different cities by driving. 
