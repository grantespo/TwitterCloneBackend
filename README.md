# TwitterCloneBackend

This is a backend application similiar to Twitter. In this `TwitterCloneBackend`, users can sign up, login, & post "screams" ( aka tweets). this app was deployed with Firebase
& uses express.js as a framework. 

Users must be logged in to call certain functions. Therefore, an authentication token is required for posting screams, deleting screams, liking screams, unliking screams, commenting 
on screams, fetching user details, uploading a profile picture, & sending push notifications.

`functions/index.js` contains all of the routes for `users` & `screams`. Also, the functions for creating & deleting push notifications
exists in this file.

`functions/handlers` contains all of the necessary functions relating to users & screams.

`functions/util` contains all of the necessary functions for authorizing & validating user data.

`functions/dbschame.js` shows the database schema for this app.

Although the back end is complete for this app, I am still working on the front end which will be developed using react.js.
