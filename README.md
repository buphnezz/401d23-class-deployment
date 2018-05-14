# 401d23-class-deployment
## Authors
Zachary Schumpert

## Overview
This application is deployed on Heroku and utilizes Github and Travis Cl. A MongoDB database was added to the application via 'mlab' and the database was added to Heroku.  The application has been linked to AWS using Heroku's environment variables. 

## Getting Started

The following npm install should occur before attempting to run this application:

[npm install -D babel-register babel-preset-env babel-eslint eslint eslint-config-airbnb-base eslint-plugin-import eslint-plugin-jest jest aws-sdk-mock babel-preset-stage-0 babel-cli]

Also, install these packages before running the application:

[npm i winston@next dotenv faker aws-sdk fs-extra multer]

[npm install -g artillery]

Install Mongodb and start your mongodb server before running the application.

The last thing to do is create your own Heroku and and Travis Cl account and link your Github to both services. 

## DON'T FORGET
Ensure your .env file is added to your .gitignore to prevent your AWS key from being pushed to Github! 
