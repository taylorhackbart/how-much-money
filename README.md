# Track Your Money!

## Description

In this application, a user is able to add and subtract funds to show the total amount of money in their account. A graph is shown that displays the fluctuation in funds. A user can input an amount while the server is offline, and these will be displayed in the browser, and will be pushed into the database once the user has returned online. 

The live version of the app is deployed on Heroku, and can be accessed <a href="https://glacial-fortress-58963.herokuapp.com/">here. </a>

## Usage

Once a user enters the site for the first time, they will be shown a screen with no data:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/start.png">

They will then be able to add or subtract funds:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/add.png">

Once funds have been deposited or withdrawn, it will display as shown: 

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/example.png">

These will be added into the database (using MongoDB Atlas):

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/atlas1.png">


Here, I am showing that I am switching to offline mode for my next sample entries:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/offline.png">

Once a user loses service, they will still be able to keep track of their entries and they will be displayed on the screen, same as before:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/offlinefunds.png">

These errors will appear in the console, however, the data will still be pushed to the database once the user has access to internet again:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/offlineError.png">

Switching back to online:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/online.png">

Entering a new transaction "More Money":

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/onAndOffline.png">

All three transactions will now be displayed in the database:

<img src="https://github.com/taylorhackbart/how-much-money/blob/master/readmeimages/atlas2.png">

## Installation

To use or update this application, fork the repository and run "npm install" in the command line. While the packages should be installed and ready to use after running this, if "MODULE_NOT_FOUND" errors pop up, install express, mongoose, compression and morgan. Morgan is not a required package, but it does help to know the status of your routes as they are being fired. 

To run this locally, in the command line enter "node server.js" and direct yourself to "localhost:3000/"

## Technologies Used

This application primarily uses JavaScript, Mongoose, MongoDB, Express, MongoDB Atlas, and Heroku

## Credits
Shout out to Gary (my instructor) for helping us along the way!



