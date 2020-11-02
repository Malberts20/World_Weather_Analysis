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

1. Import DataFrame from deliverable 1
2. Input statements to enter min and max temp criteria for vacation
3. Create new data frame filtered for min temp = 75; max temp = 90
4. Removed any empty rows from data frame
5. Added column for nearest hotel to dataframe
6. Searched for nearest hotel for each city using lat and lng
7. Dropped empty rows
8. Created map of cities with markers (WeatherPy_vacation-map)

### Deliverable 3 : Retrieve Weathe Data (Weather
