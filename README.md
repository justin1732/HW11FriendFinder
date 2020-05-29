# FriendFinder Heroku App

## Need to make a friend?

This was an individual project after our second group project for the University of Denver FullStack Coding Bootcamp.

This app uses Node JS and Heroku Deployment to ask the user questions and then perform calculations to match that user against other users in the already pre-built and pre-valued database. Users can then search again and/or add themselves to that database.

## Starting the app locally
My repo is located at:
https://github.com/justin1732/HW11FriendFinder
For a local version, I recommend using Visual Studio Code. Navigate over to my GitHub repo, click clone, and be sure to type in the following below:
git clone
Navigate over to the terminal and open up the area around server.js in the terminal. Then type:
npm install
After all dependencies are loaded, then type:
npm start

```
npm install
```

This should install node modules within the server and the client folder.

After both installations complete, run the following command in your terminal:

```
node server.js
```

Your app should now be running on <http://localhost:3000>. The Express server should intercept any AJAX requests from the client.
## Using Heroku
For remote viewing, my app is on Heroku at:
https://justintuckerfriendfinder.herokuapp.com/


## Using the App
Click on the "Go to Survey" button on the homepage.

Fill out the information.

Answer the questions as provided.

The system then calculates your score and matches you with someone else in the database that is closest to your score.

## Technologies Used
This application follows MVP routing and good Node JS principles to deploy successfully and without issue to Heroku. To achieve this, this app uses path for routing, express for the engine and some rendering, and bodyParser for the rest of the rendering. 

## Contact Information
I am available to be found at justteach17@gmail.com and my website is justin1732.github.io 


