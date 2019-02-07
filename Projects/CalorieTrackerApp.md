### Description

Service that helps track calories and helps users maintain their fitness goals.

It provides options for choosing a fitness plan (maintain weight / loose weight) according to height, weight, age, and exercise routine. 
The user will be able to search and select the foods consumed for breakfast, lunch, snacks, and dinner.
The app will continuously show the remaining calories that could be consumed in a day. 
It graphically represents your daily progress and also provides with a stack of healthy recipes. 

This project contains both a backend and app part.

### Requirements

Implement an app that:
* Set dietary goals according to one’s height, weight, gender, and workout routine.
* Track calories consumed and burned in a day
* Search food items and add them to list of items consumed in each day.
* Show weekly progress in the form of logs
* Let user enter performed exercises per day (optional)
* Implement a basic back office web interface for managing and updating the food database. This UI is used by administrators. Admins must register and sign in before they can manage any data.

Basic user admin:
* Signup
* Sign in
* Sign out

### Backend Service
Food items entered manually should be stored in a local database and the data merged with the data fetched from the external service. 
Capture and enter at least 20 new food items and enter sample measurement.

### Application
The app can be implemented as either a web app, mobile web app, responsive app or even native app (agree with your mentor before starting).

### Questions
Questions to consider before and during the project.
* Who are the target audience and the typical user?
* What functionality will this typical user like to have?
* Why do we need caching? How often do we need to refresh the cache?
* When do users need to sign in?
* How do we store new food and calorie measurements?
