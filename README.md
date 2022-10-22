# python-api-challenge
This is Kokila's Python API Homework

# PART 1 - WeatherPy

## API calls
* Lists to store the retrieved data from openweathermap API
* variables to store Processing Records and their sets
* Loop through the API and get the data
* For every API successful call, store data in a list else display Error message

## Convert Raw Data to Dataframe
* Display the DataFrame
* Export the city data into a .csv
* Display the Summary Statistics of the dataframe

## Inspect the Data and remove the Cities humidity > 100%
* Skip this step if there are no cities that have humidity > 100%.
* Get the indices of cities that have humidity over 100%.
* Make a new DataFrame equal to the city data to drop all humidity outliers by index.

## Plotting the Data
* Latitude Vs. Temperature plot
* Latitude Vs. Humidity plot
* Latitude Vs. Cloudiness plot
* Latitude Vs. WindSpeed Plot
* Analysis on the above plots

## Linear Regression
* Latitude Vs. Temperature plot for both Northern and Southern Hemispheres
* Latitude Vs. Humidity plot for both Northern and Southern Hemispheres
* Latitude Vs. Cloudiness plot for both Northern and Southern Hemispheres
* Latitude Vs. WindSpeed Plot for both Northern and Southern Hemispheres
* Analysis on the above plots for both Northern and Southern Hemispheres.

# Part 2 - VacationPy
* Store part 1 results into a Dataframe.
* create Humidity Heatmap
* create new Dataframe fitting weather criteria.
* create new dataframe "Hotel_df"
* Add Hotel Name column to dataframe.
* set parameters to search for hotels within 5000 meters.
* Hit the google places API for each city Co-ordinates.
* Store the first hotel result into a dataframe.
* Plot markers on the top of Heatmap.

