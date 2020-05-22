# MX_covid_maps

# Coronavirus MX Maps using python

# Libraries needed Pandas, Folium, Numpy


# Purpose: 
Analyze Ceninetlas Government project to track Coronavirus cases around Mexico and the test distribution per Entity in order to establish if a Machine Learning Model is need in a specific level such as local enitities.

# Methodology
As government's data doesn't contain Latitude and Longitude, INEGI's data was taken to be crossed with Coronavirus data, both databases contain a foreign key to be crossed for local entitites but INEGI's data is recorded in a specific level such as local district so in order to get an aproximate coordentes without calculating euclidean distances, there was taken average per local entity to get the center of it. 
