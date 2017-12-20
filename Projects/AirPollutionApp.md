### Description

Implement a service that shows up-to date air pollution information.

Thera are several hundred measurement stations around the world reporting air pollution data (several of them are in India).
Data is collected and in many cases offered free of charge from various government and NGOs in an effort to raise awareness on the subject.

Consume and present this data to users in an attractive and understandable way. 

This project contains both a backend and app part.   
This project will also show how to develop a middleware that integrates with external third part services.

### Requirements

Implement an app that:
* Show air pollution for cities in a list
* Show air pollution on a map
* Search and filter for cities
* Show nearby stations
* Add as favourites
* Show details

Implement a basic back office web interface for managing stations and entering new air pollution data.
This UI is used by administrators. Admins must register and sign in before they can manage any data.

Basic user admin
* Signup
* Sign in
* Sign out

### Backend Service

The backend act as a middleware that uses external third party services to fetch, aggregate and present data to the application.
Extensive caching should be used to reduce the number of requests to external services to keep within the quota set by the external service. 

Examples of external services:

http://aqicn.org/api/    
https://airvisual.com/api    
https://market.mashape.com/sohil4932/open-environment-data-project    
http://api.indiaspend.org/dashboard/    

The team need to investigate, test and select one of the available services.

Stations and measurements entered manually should be stored in a local database and the data merged with the data fetched from the external service.
Capture and enter at least 5 new station and enter sample measurement (these can often be found in newspapers or embassy websites) 

### Application

The app can be implemented as either a web app, mobile web app, responsive app or even native app (agree with your mentor before starting).

### References

None.

### Questions

Questions to consider before and during the project.
* Who is the target audience and typical user?
* What functionality will this typical user like to have?
* Why do we need caching? How often do we need to refresh the cache?
* When do users need to sign in?
* How do we store new stations and pollution measurements?

### Improvement suggestions

Possible improvements and bonus tasks
* Show other weather related information (e.g. temperature, humidity etc)
* Show show history and trend
* Export as GeoJson and import into another GIS tool
* Offer API for integration directly with measurement station - IoT
