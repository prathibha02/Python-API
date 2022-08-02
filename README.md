# Python-API

## Part 1: WeatherPy

In this section, I created a Python script to visualize the weather of 500+ cities of varying distance from the equator. 

I created a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


The second requirement was to compute the linear regression for each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, I explained what the linear regression is modeling. 


### Part 2: VacationPy

I used Jupyter-gmaps and the Google Places API for this part of the assignment.

To complete this part of the assignment, I did the following: 


* Narrowed down the DataFrame to find the ideal weather condition. 

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  * I dropped any rows that don't satisfy all three conditions. In the cities I chose, the weather was ideal.

  
* Use Google Places API to find the first hotel for each city located within 5,000 meters of the coordinates.


As final considerations:

* Used the Matplotlib plotting libraries.
* For Part 1, I included a written description of three observable trends based on the data.
* For Part 2, I took a screenshot of the heatmap that I created and included it in the output file.

