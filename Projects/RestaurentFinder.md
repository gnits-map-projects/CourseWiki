### Description

Implement Hyderabad No1 Restaurant Finder that will allow users to search for and find restaurants nearby.

This project contains both a backend and front-end part.

### Requirements

Implement an app that:
* Shows nearby restaurants
* Filter on open/closed
* Show in list view 
* Show on map
* Click on a restaurant to show details
* Go to home page and Facebook page
* Show distance to restaurant

Implement a basic back office web interface for easy management of restaurants - add, update, delete, search etc.
This UI is used by administrators to manage available restaurants as new are opened, closed and their details change.
Admins must register and sign in before they can manage restaurants.

Basic user administration
* Signup
* Sign in
* Sign out
* Update profile

Restaurants should have a
* Name
* Description
* Image (could be an URL to image)
* Homepage url
* Facebook page url
* Lat and long
* Opening hours
* Phone number     
+ any other properties you see fit

### Backend Service

Implement a backend service that stores restaurants spatially.

Capture and enter at least 30 restaurants as example data and PoC. 
If open and free data exists, the team can decide to import this data instead of adding it manually.

The backend services should be hosted on TBD

### Application

The app can be implemented as either a web app, mobile web app, responsive app or even native app (agree with your mentor before starting).

### References

None
 	 	 
### Questions

Questions to consider before and during the project.
* Who is the target audience and typical user?
* What functionality will this typical user like to have?
* How would you market the services? 
* How will you get users to download the app? How will you get users to continue using the app (retention)?
* How do you track that the app is successful?
* Can you make any money from the project? How?
* Are there any good open source frameworks that can help us along the way? What about licenses and copy rights?
* What additional restaurant properties could be added to increase the user experience
* What options do we have for storing and returning restaurants spatially (how do you write a query that returns nearby items)?
* Project planning

### Improvement suggestions

Possible improvements and bonus tasks
* Search by name and street name
* Add restaurants to favourites
* Support rating restaurants
* Search for restaurants based on rating
* Support commenting on restaurants, both adding and viewing
* If there are thousands of restaurants, pagination might be needed - returning one page of restaurants at the time
* Authentication, users must login before they can create any data (managing restaurants, ratings, comments etc)
* Take me there, show closest route from current location to restaurant
* Pick of the day - suggest a random open restaurant nearby for eating todays lunch
