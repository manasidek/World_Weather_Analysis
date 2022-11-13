# World Weather Analysis

## Overview of the Project

- The purpose of this analysis is to help PlanMyTrip to find and recommend ideal hotels based on clients' weather preferences.

## Resources

- Data Sources:
    1. https://openweathermap.org/
    2. https://developers.google.com/maps/

- Software: Anaconda 22.9.0, Python 3.7.6, Jupyter Notebook 6.4.12

## Results

### Step 1 of Analysis: Collect the Data

- The script for the analysis is: [Weather_Database](https://github.com/manasidek/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb)

- Using the OpenWeatherMap API, collected the current weather data from each unique city and created a dataframe.

- Export the DataFrame as a CSV file. The link to the csv is: [Weather_Database](https://github.com/manasidek/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)

![WeatherPy_Data](https://github.com/manasidek/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Data.png)

### Step 2 of Analysis: Exploratory Analysis with Visualization

- The script for the analysis is: [Vacation_Search](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb)

- Employ input statements to retrieve customer weather preferences.

![Customer_input](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Search/Customer_inputs.png)

- These preferences help in identifying potential travel destinations and nearby hotels and create a map with pop-up markers.

![Cities _For_Travel](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Search/Cities_For_Travel.png)

![Hotels_Cities_Customer](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Search/Hotels_Cities_Customer.png)

![WeatherPy_Vacation_Map](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_Vacation_Map.png)

### Step 3 of Analysis: Travel Itinerary Map

- The script for the analysis is: [Vacation_Itinerary](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)

- Using the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.

![Vacation_Destinations](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Destinations.png)

- Creating a map with a pop-up marker for each city on the itinerary.

![WeatherPy_Travel](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

![WeatherPy_Travel_Map_Marker](https://github.com/manasidek/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

