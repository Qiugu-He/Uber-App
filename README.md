# Taxi Pickup App

This is an Android/Java version taxi app that provides pickup services for customer based on their location.

# How this app works:

The app provide authorization functionality to distingui if the user is driver or customer by login. The app allows new user registration as well, however, new user have to indicate if they registered as a driver or customer. The database for storing user information and their location are using firebase. 

The driver/customer's location is loacted using Google Map API. Once their location are located, for real time tracking purpose, their location will be updated every second using GeoFire location queries. This query is imported and exported to/from database to track their real time location. The pickup request is requested to an appropriate driver within 1000m,a nearby driver will be choose, the requested will be found and the request will be send to that driver. All appropriate/necessary activities/funcationalities for the app are implemented to meet the user need.
