# Python API Challenge - What's the Weather Like?

## Use Python requests, APIs, and JSON traversals to per form the following:
## Part I - WeatherPy:
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator using.

## Part II - VacationPy:
Use Jupyter gmaps and the Google Places API to plan future vacations based on weather data.

## Breakdown of Tasks

### Part 1 - WeatherPy
1. Generate random list of lat, long values using numpy.
2. Find nearest city using citypy.
3. Perform weather API call using imported API key.
4. Convert arrays of JSON into pandas dataframe.
5. Export city data into csv
6. Build a scatterplot for City Latitude vs. Temperature using matplotlib.pyplot.
7. Build a scatterplot for City Latitude vs. Humidity using matplotlib.pyplot.
8. Build a scatterplot for City Latitude vs. Cloudiness using matplotlib.pyplot.
9. Build a scatterplot for City Latitude vs. Wind Speed using matplotlib.pyplot.
10. Create a function to create Linear Regression plots.
11. Use function to plot Max Temp vs. Latitude Linear Regression for northern and southern hemisphere
12. Use function to plot Humidity (%) vs. Latitude Linear Regression for northern and southern hemisphere.
13. Use function to plot Cloudiness (%) vs. Latitude Linear Regression for northern and southern hemisphere.
14. Use function to plot Wind Speed (mph) vs. Latitude Linear Regression for northern and southern hemisphere.

### Part 2 - VacationPy

1. Read in csv data from Part 1.
2. Use gmaps to create a humidity heat map that displays the humidity for every city.
3. Create new dataframe fitting weather criteria personally chosen based on vacation weather preferences. 
4. Perform Google API to find the first hotel for each city located within 5000 meters of your coordinates.
5. Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

## Output

![HeatMap](VacationPy/vacationheatmap.png)

![HotelHeatMap](VacationPy/vacationheatmapwithhotels.png)

## Disclaimer 

This project was published for education purposes only. 

Copyright
Trilogy Education Services © 2019. All Rights Reserved.
