# Introduction

In this Project, I will be creating a Basic Level Restaurant Recommender which will give you the top Restaurants near your address. I’ll explore the venues based on their Rating and Distance. Whenever a person wants to find a Particular Restaurants in the vicinity of his current address or any address then, this model will recommend the Best Restaurants nearby on Map with their ratings. Thus, our aim here is to fetch restaurants that someone can visit nearby.
Here, we’ll get venues that are fit for the location specified based on the data collected from the Foursquare API and information retrieved from Data Science application.

# Data Used

The data has been collected from Foursquare API. The first step will be to search for venues with given Query, Location and within a radius specified by the User from his given location. After extracting the venues using the Foursquare API, the latitude and longitude values will be used to fetch the venue details using Foursquare API.
After fetching the venue details, again Foursquare API will be used to fetch the details of all the venues and then add the relevant information and process the Data to get the Best and Top 6 Restaurants nearby.

