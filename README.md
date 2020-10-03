# Travel Destination App using Openweather and Google APIs

## Overview of the project
This is a fun project that aims to provide the user with travel destinationa dn hotel recommendations based on their desired city and weather criteria. 


Note: In order to run this notebook you will need your own Openweather and Google API keys. They are fairely easy to get and I have added links below to their webpages. 

Openweather: https://openweathermap.org/api

Google Cloud Platform: https://cloud.google.com/maps-platform/


## Description and how to use

1. Open the `Weather_Database.ipynb` in the Weather_database folder to build the dabase of cities of interest. The program builds a dabase of cities from 2000 random latitudes and longitudes.

2. Open the `Vacation_Search.ipynb` in the Vacation_Search folder and input your desired temperature ranges. Based on the temperature ranges the program will filter out the destinations for you. The output will be  google map with markers and a csv dataset taht can be used for building a itinerary in the next step. 

<p>&nbsp;</p>

![Destination Map](/Vacation_Search/WeatherPy_vacation_map.png)*Destination Map*

<p>&nbsp;</p>

3.Next to build an initnerary, open the `Vacation_Itinerary.ipynb` in the Vacation_Itinerary folder. Load the Vacation Search database in teh file and select 4 cities of your choice from the google maps displayed. For my search I chose cities in Brazil. 
The program will give you the best route between teh cities depending upon your mode of travel i.e. 'Driving', 'Walking' or 'Bicycling'. 

<p>&nbsp;</p>

![Cities Map](/Vacation_Search/Weather_travel_map.png)*My Cities Map*

<p>&nbsp;</p>

![Cities Map](/Vacation_Search/Weather_travel_map_markers.png)*City Markers*

Please feel free to provide me with your suggestions. Thank you. 