# Company Inventory Page

This is the Seventh Assignment of CS648 course. It is a SPA created using React, served using Express, Graphql for API integration and MongoDB as the database. A simple inventory page where one can add/delete some products and view all the products present.\
The initial setup comes from Assignment6 repo and this repo is a clone of that with new changes for Assignment 7.

## Initial Step

Go to Api folder and run `npm install` to install all the dependencies.\
Go to Ui folder and run `npm install` to install all the dependencies.

## Development server

Go to Api folder and run `npm run start` to bring up the Api server.\
Go to Ui folder and run `npm run start` to bring up the UI.\
Now Navigate to `http://localhost:8000/` to interact with the application.

## GraphQL Playground

After starting Development Server using previous step, open `http://localhost:3000/graphql` to interact with the API using GraphQL Playground.

## MongoDB reset

From Api folder, you can run `mongo "mongodb+srv://cluster0.p5vkx.mongodb.net/myFirstDatabase" --username dmakati7 scripts/init.mongo.js` and enter password as `Abc123` to reset the database with two products added initially.
