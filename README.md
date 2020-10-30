# Python-API
Objetive of this project: Create a Python script to visualize the weather of more than 500 cities across the world.Also creat plots to find relationships between weather and other variables.

  Scatter Plots to show relationship between explanining any findings:
    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude 
 
  Create a Linear Regression analysis on the above relationships divided by hemisphere 
    Northern Hemisphere - Temperature (F) vs. Latitude
    Southern Hemisphere - Temperature (F) vs. Latitude
    Northern Hemisphere - Humidity (%) vs. Latitude
    Southern Hemisphere - Humidity (%) vs. Latitude
    Northern Hemisphere - Cloudiness (%) vs. Latitude
    Southern Hemisphere - Cloudiness (%) vs. Latitude
    Northern Hemisphere - Wind Speed (mph) vs. Latitude
    Southern Hemisphere - Wind Speed (mph) vs. Latitude
    
Final Notebook includes:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


Part II - VacationPy

Objective: To utilize jupyter-gmaps and the Google Places to analyze weather data to plan future vacations

Create a heat map that displays the humidity for every city from the part I of the homework.
Ideal weather condition for the Ortiz Family: 
        Max tempeture of 95 and a min of 70
        Wind speed less than 10 mph.
        Some cloudiness is ok.

Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

