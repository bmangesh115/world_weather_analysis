# world_weather_analysis
 
 # Overview
The purpose is to test the app for planning the trip based on current weather data amd client's preference of the weather.

1. Retrieve weather data.
2. Create a customer travel destinations Map.
3. Create a travel itinerary map.

## Resources
- Data Source: OpenWeatherMap API, Google Maps and Places API
- Software: Jupyter Notebook, Python 3.7.13, Visual Studio Code 1.68.1

## Results
The link to the script to retrieve weather database.<br>
[Collect weather data](/Weather_Database/Weather_Database.ipynb)<br>

The link to the weather DataFrame in csv file.<br>
[Weather DataFrame](/Weather_Database/WeatherPy_Database.csv)<br>

### DataFrame showing city location and weather conditions 

<figure>
    <figcaption>DataFrame showing city location and weather conditions</figcaption>
    <img src="/Weather_Database/Weather_Database_DataFrame.png" width="1066" height="465"
         alt="DataFrame showing city location and weather conditions">
</figure> <br>

###  Customer travel destinations map 

The link to the script to create a customer travel destinations map<br>
[Create travel desitinations map](/Vacation_Search/Vacation_Search.ipynb)<br>

The link to the customer travel destinations DataFrame in csv file.<br>
[Travel destinations DataFrame ](/Vacation_Search/WeatherPy_vacation.csv)<br>

<figure>
    <figcaption>DataFrame showing hotels based on customer preference</figcaption>
    <img src="/Vacation_Search/vacation_search_hotel_dataframe.png" width="1182" height="446"
         alt="DataFrame showing hotels based on customer preference">
</figure> <br>

<figure>
    <figcaption>Travel desinations map based on customer preference</figcaption>
    <img src="/Vacation_Search/WeatherPy_vacation.png" width="1512" height="650"
         alt="Travel desinations map based on customer preference">
</figure> <br>

###  Travel itinerary map 

The link to the script to create a customer travel itinerary map<br>
[Create travel itinerary map](/Vacation_Itinerary/Vacation_Itinerary.ipynb)<br>

<figure>
    <figcaption>DataFrame of the customer itinerary</figcaption>
    <img src="/Vacation_Itinerary/vacation_itinerary_dataframe.png" width="1113" height="225"
         alt="DataFrame of the customer itinerary">
</figure> <br>

<figure>
    <figcaption>Customer directions layer map for the itinerary</figcaption>
    <img src="/Vacation_Itinerary/WeatherPy_travel_map.png" width="1469" height="508"
         alt="Customer directions layer map for the itinerary">
</figure> <br>

<figure>
    <figcaption>Customer marker layer map for the itinerary</figcaption>
    <img src="/Vacation_Itinerary/WeatherPy_travel_map_markers.png" width="1484" height="590"
         alt="Customer marker layer map for the itinerary">
</figure> <br>
