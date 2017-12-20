### Description

Implement a Government Map Surveying Tool for land and field surveyors and anyone dealing with environmental and GIS data. Make GIS data collection or field survey process faster and more efficient. 

As PoC the groups should research and perform a small map survey on temples in and around Hyderabad.

This project contains both a backend and app part.

### Requirements

The high level workflow for performing a survey involves 

1. Administrator create a new survey
2. Surveyors select the survey in the app
3. Surveyors will create a feature by taking screenshots, capturing the location and filling in mandatory attributes
4. Once the survey is completed the administrator will generate a report and export the results

The app should support the following use cases:
* View list of available surveys
* Select survey
* Add Features to survey
* View features in list
* View feature on map
* Select feature details
* Edit feature
* Delete feature

Implement a basic back office web interface for easy management of surveys - create, view edit. 
This UI is used by administrators to manage surveys.
Admins must register and sign in before they can manage surveys.

Basic user administration
* Signup
* Sign in
* Sign out
* Update profile
* Survey attributes:

Name
* Description
* Picture     
+ any other properties you see fit

Feature attributes:
* Name
* Description
* Geometry
* Picture
* Key - Value (record attributes of interest, e.g. size, height, area, url etc)     
+ any other properties you see fit

### Backend

The backend needs to offer all the necessary REST APIs o support the application requirements listed above.

Capture and enter at least 20 features as example data and PoC. 
If open and free data exists, the team can decide to import this data instead of adding it manually.

### App

The app can be implemented as either a web app, mobile web app, responsive app or even native app (agree with your mentor before starting).

### References

None
 	 	 
### Questions

Questions to consider before and during the project
* What can survey tools be used for? Give examples? What value does it provide?
* What devices can a surveyor use that make the process more easy?
* How can the results be presented?
* Think of additional feature the surveyor may need?
* What types of map layers can be useful for performing surveys?
* What options do we have for storing and returning features spatially?

### Improvement suggestions

Possible improvements and bonus tasks
* Support creating features with geometry type of line and polygon
* Calculate area + distance (requires line and polygon geometry type
* Capture geometry either by drawing on the map or tracking users movement
* Search for feature by name
* Search for survey by name
* Show surveyors location on map (used for management to followup and plan)
* Import features as GeoJSON
* Create surveys with a custom set of attributes - e.g. check box, free text, range, list of values
* Capture location as they move
* Allow users to add screenshots to features
