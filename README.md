# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
create an accurate statistical regression model to identify the relationship between number of bikes in a city and characteristics of points of interests within that city and what effect they have, and how signifant are they.

## Process
Making connection to CityBikes API and explore its data by retrieving Latitude, longitude, station name, and bikes available in the city
Making connection to Foursquare API to explore its structure and retrieve infromation
Making connection to Yelp API to explore its structure and retrieve infromation
joining datas from CityBikes, Foursquare, and Yelp APIs to create a single dataframe
Providing data visualiztion according to the new dataframe to explore the data
Building a SQLite database
Creating a regression model to demonstrate the relationship between point of interests and number of bikes
## Results

The regression model uses the statsmodels library to analyze the relationship between the number of bikes available at a station and characteristics of points of interest (POIs) nearby. Specifically, it uses the following features from the dataset:
Distance to POI
Latitude of POI
Longitude of POI


The model only explains small portion of the variance in bike availability. This suggests that while location-based factors (distance, latitude, longitude) may influence bike availability, other factors (e.g., local demand, bike station management) likely play a larger role. The model can further be enhanced and improved by adding or replacing other features. The coefficients for distance and location provide insight into how proximity to POIs and geographical position impact bike availability, but further model refinement or additional features are needed to improve prediction accuracy.

## Challenges 
Biggest challenge for me was to retrieve the information of each bike station so I can use that to retrieve information from Foursquare and Yelp within certain radius to finally compile the data and create a model
## Future Goals
Based on what was discussed in challenges, I wiil try to find a better solution given the time we had for the project was short