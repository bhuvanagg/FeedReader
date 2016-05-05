# FeedReader

This is an application to manage and view personal RSS Feeds.

All feeds to be suscribed can be generated using the following link:
https://rss.itunes.apple.com/us/?urlDesc=%2Fgenerator

All the feed links - change the URL in the end from XML to JSON.
For example:
https://itunes.apple.com/us/rss/topaudiobooks/limit=10/xml
Gets changed to 
https://itunes.apple.com/us/rss/topaudiobooks/limit=10/json

Setup for the project.
1. Need NodeJS installed.
2. Install MongoDB.
3. Point the db variable in "server.js" to your localhost db to be connected.

When running the project:
1. Onload press cancel on the login screen.
2. Create a new account by signing up with email and password.
3. Now you can start browsing your personal feeds.

Technologies used: HTML, CSS, JAVASCRIPT, jQuery, NodeJS, Mongo DB, Offline.js, jReject, Moment.js, AJAX, Ply.css
Note: CSS animations used will not work on IE 8 or before.

Screenshot of application: http://www.public.asu.edu/~baggarw1/ResponsiveImages/Feedy_SS.png
