# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
create an accurate statistical regression model to identify the relationship between number of bikes in a city and characteristics of points of interests within that city and what effect they have, and how signifant are they.

## Process
Making connection to CityBikes API and explore its data by retrieving Latitude, longitude, station name, and bikes available in the city
Making connection to Foursquare API to explore its structure and retrieve infromation such as category and address for each bike station
Making connection to Yelp API to explore its structure and retrieve infromation such as rating and review count and address 
joining datas from CityBikes, Foursquare, and Yelp APIs to create a single dataframe
Providing data visualiztion according to the new dataframe to explore the data
Building a SQLite database
Creating a regression model to demonstrate the relationship between point of interests and number of bikes
## Results
Unfortunately due to limited data available for Vancouver, I had to make a major assumption where number of bikes can be explained based on
popularity of the areas based on the resturaunts, ratings, review counts and their geological map location to describe the relationship


According to the model, we can suggest that behaviour of POIs and its characteristics have significant impact on rating of the resturaunts. (Note: This is an assumption due to lack of data in my case) This also can mean that the availibility of 
bike stations within the area according to its latitude and logitude which can demonstrate popularity of the area.
However with that being said, according to Adj. R-squared only 3 percent of variability in significance of the resturaunts can be explained by the independent variables
## Challenges 
My major challenge was to join the datas but due to the constraint that no keys where mutual between the 3 dataframes, I had to make assumptions, as mentioned,
which impacted the analysis of the regression model
I discussed this issue with a cohort instructor as well.

## Future Goals
Based on what was discussed in challenges, I wiil try to find a better solution given the time we had for the project was short