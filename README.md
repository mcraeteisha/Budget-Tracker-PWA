# Budget-Tracker-PWA
A Progressive Web App that allows users to add expenses and deposits to their budget with or without an internet connection.

## Link to Deployed Application
[PWA Budget Tracker](https://vast-sands-44652.herokuapp.com/)

## Technologies Used
* Service Workers
* Cache API
* indexedDB
* MongoDB Atlas
* Heroku
 
## Work Completed

Using VS Code, Google Chrome Developer Tools, and the technologies listed above, I completed the following:

* Converted an existing web application to a PWA with offline functionality.
 
## Learnings and Issues
Some of the learnings I'm taking away from this project are:
1. An issue I ran into with this project was deployment. getting the Heroku app deplyoed using MongoDB Atlas. The fix for this was that in my Config Vars for MongoDB_URI in Heroku, I had "< >" around my password, so MongoDB Atlas was not connecting. Also, at times my Service Worker file was throwing errors and trying to serve the wrong files (I realized I was including uncessesay files in my Service Worker doc. Also, clearing my cache seemed to help).

## Future Application Updates
* Create easy-to-use edit and delete buttons for transactions, giving users the option to update their previous transaction history. 
 
## Contributors
Teisha McRae

![Website Screenshot](https://user-images.githubusercontent.com/73713665/126024959-bf56c19c-0e58-4400-a234-ede483d59433.png)



