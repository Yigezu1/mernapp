# mernapp
mern basic application
## I follow the setps below to create the MERN App.
* Copy the boilerplate code from other applications. All the necessary folders for the MERN application have been created.
* Define the MongoDB schema for the application in the models directory. The number of schemas defined in the application depends on the number of tables you want to manage in your application. All the schemas should be defined within the models folder.

* Define the controllers that you will use in your application within the controls folder. The number of controls you use in your application depends on the the schemas you have in your models folder. If more than one control is used in your application, you have to add index.js file to export all the controls in your application. In the Controllers methods that connect to the database are defined.

* Define the routes for your application. Use express webserver's router to define your route files. First setup the folder structure for your routes to routes/api. Within your api folder create all your routes, the number depends on the number of schema your app using. And then add index.js files to each folder to define the correct routes route.The route codes can be copied and the controllers changed.
* Update the seedDB.js code. This is a seed code to populate your MongoDB to help you troubleshoot and test your application.
* Udate the server code to use the routes and make connections to MongoDB. This code can be reused with a minor change. This finalizes the server side code for the MERN application.