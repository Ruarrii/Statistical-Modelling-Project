# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
In this project I
- Will access data using APIs
- Will Clean and transform data using Python
- Will Load data into a database using Python
- Will perform EDA, including using both statistics and visualizations
- Will identify trends and patterns in data using statistical models
- Will interpret the results of the statistical models

## Process
Step 1: exploring and querying the data
Step 2: choosing a city and retrieving all bike station data
Step 3: using the API to cal the latitude, longitude and number of bikes for each station
Step 4: parse the JSON object into a Pandas dataframe
Step 5: Connect to both the Foursquare and Yelp APIs
Step 6: query both APIs to retrieve information on the bars and POIs within a radius of each bike station
Step 7: creating a dataframe for both the Yelp and Foursquare results.
Step 8: comparing the quality of both API results
Step 9: joining the data from parts 1 and 2
Step 10: using data visualization to explore the data
Step 11: creating an SQLite database to store the collected data
Step 12: building a regression model
Step 13: interpreting results
Step 14: turning the problem into a classification one

## Results
For my chosen area, there were only 8 bike stations. Not a lot of data to work with.  
I decided to gather the number of bars and the number of POIs within a 1000 metre radius of each of the stations.
As it turned out, the number of bars/POIs did not seem to have any great effect, if any, on the number of bikes available, or the number of empty bike slots.  


## Challenges 
I think that the super small data set made everything a little bit more difficult once it got to the modelling stage.  
Unless I'm totally missing something, I simply didn't have enough to work with. 

## Future Goals
If I had more time, I would like to query the citybikes API for a larger dataset.
I would also like to experiment with different POI data.
