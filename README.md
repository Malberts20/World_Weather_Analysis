# World_Weather_Analysis

## Basic Project Plan

### Deliverable 1 : Retrieve Weather Data (Weather_Database folder)

1. Generate a set of 2,000 random latitudes and longitudes 
2. Retrieve the nearest cities using citipy module
3. API call with the OpenWeatherMap to obtain weather data for each city:
    - Latitude and Longitude
    - Maximum Temperature
    - Percent Humidity
    - Percent cloudiness
    - Wind Speed
    - Weather description  
4. Create a new DataFrame 

### Deliverable 2 : Create a Customer Travel Destinations Map (Vacation_Search folder)

1. Import DataFrame from Deliverable 1
2. Input statements to enter min and max temp criteria for vacation
3. Create new data frame filtered for min temp = 75; max temp = 90
4. Removed any empty rows from data frame
5. Added column for nearest hotel to dataframe
6. Searched for nearest hotel for each city using lat and lng
7. Dropped empty rows
8. Created map of cities with markers (WeatherPy_vacation-map)

### Deliverable 3 : Create a Travel Itinerary Map (Vacation_Itinerary folder)

1. Start with filtered dataframe and map from Deliverable 2
2. Four (4) cities chosen for vacation itinerary:
    - Laguna
    - San Francisco
    - San Jose
    - Morro Bay
3. Created a dataframe for each chosen city
4. Obtained lat, lng pair for each chosen city, then converted to numpy array
5. Utilized gmaps to generate itinerary DRIVING to each choen city
6. Map of driving itinerary (WeatherPy_travel_map)
7. Joined city dtata frames into on dataframe
8. Created map of cities withmarkers (WeatherPy_travel_map_markers)
