# World_Weather_Analysis

## Project Overview

The following additions were developed for beta testing in the PlanMyTrip App to improve on its available features.

**1.** A ***Customer Travel Destinations Map*** that displays a list of potential vacation locations based on the user's input for desired weather.  

**2.** A ***Travel Itinerary Map*** based on four cities of the user's choice. With the use of Google Maps Directions API, the user will be able to view **a)** the travel route between the four cities and **b)** the detailed location info markers. 

Both maps are equipped with detailed destination markers that provide the user with the following information:

- Hotel name
- City
- Country
- Current weather description with the maximum temperature (F°)

## Resources 

- Software: Anaconda 4.9.2, Jupyter Notebook 6.1.4, Python 3.8.5
- Data Sources: 
   1. Data Analysis: [Vacation_Search](Vacation_Search/Vacation_Search.ipynb), [Vacation_Itinerary](Vacation_Itinerary/Vacation_Itinerary.ipynb)
   2. Raw data: [WeatherPy_Database.csv](Weather_Database/WeatherPy_Database.csv)

## Preview

#### 1. Customer Travel Destinations Map:

- After inputting the desired weather preferences, a customized travel destinations map will be generated with potential vacation destinations and nearby hotels within the user's criteria.

<p align="center">
  <kbd><img src="Vacation_Search/WeatherPy_vacation_map.png" width="900"/><kbd>
</p>

#### 2. [Vacation Itinerary](Vacation_Itinerary/travel_df.PNG)

- Based on the filtered weather criteria the user will be able to choose a starting/end point, and three additional destination stops to be added to a new travel map. See Example a).

   a)  The user has decided to take a road trip along the east coast of Brazil. They will begin and end their journey at *Caravelas* while makings stops at *Vila Velha, Sao Joao Da Barra, and Santa Isabel* along the way. 

<p align="center">
  <kbd><img src="Vacation_Itinerary/WeatherPy_travel_map.PNG" width="900"/><kbd>
</p>

   b) Interacting with the travel markers, generates a pop up providing the user necessary details required for their destinations stops.
   
<p align="center">
  <kbd><img src="Vacation_Itinerary/WeatherPy_travel_map_markers.png" width="700"/><kbd>
</p>
     
## Summary 

With minor alterations to the code, the following options can also be made available to the user:

a) Expanding the Latitude & Longitude search criteria to provide additional travel destinations to the user.

b) The options for "BICYCLING", or "WALKING" can also be made available to the user on the direction layer map by altering the travel_mode output.

c) Modifying the "Info Box template" to provide the user with with additional details in the marker pop up, e.g. Humidity, Cloudiness, Wind Speed.


