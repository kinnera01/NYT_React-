# New York Times Article Search
This is a React.js app that allows users to search for New York Times articles. After performing a search, the user will see article results including the name of the article, the date and time of publishing, and a button linking to the article source. Finally, users are able to add and remove articles from a saved articles section. The app uses Node/Express for the server and routing, MongoDB/Mongoose for the database and models

[Live Demo](https://blooming-peak-51918.herokuapp.com/)

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development. I will assume that you already have Node.js and MongoDB installed locally. See deployment for notes on how to deploy the project on a live system.

Install dependencies
In your CLI, enter mongod
In a new CLI window, go to root of directory and enter node server.js
In a third CLI window, go to root and enter yarn start. This will start the webpack dev server.
Your browser should automatically open a new tab containing the app.

Dependencies
You will need to yarn install the following node modules:

express
mongoose
body-parser
axios
react
react-dom
react-router-dom
react-scripts
Since I have included two package.json files, you do not need to install dependencies by name. Simply run the following in the root of your directory as well as in the Client folder:

yarn install
Deployment
Follow these instructions to deploy your app live on Heroku

Create a heroku app in your project directory

heroku create <projectName>
Provision mLab MongoDB add-on for your project

heroku addons:create mongolab
Deploy the app

yarn deploy
Now your project should be successfully deployed on heroku.


