# Paw Spot

[Paw Spot Live Link](https://the-paw-spot.herokuapp.com/)

## Overview
- Welcome to Paw Spot! Are your fur-babies your best friend? Do you wish you could take them more places? Paw Spot is here for you. Here at Paw Spot we are creating an app where users can post pet-friendly locations along with the ability to view other users pet posts and even search for local spots near you. Our goals are to increase waggy tails, improve pet bonding, and create fun local experiences for our users.

## Features
- User Login and Authentication
- Ability to Add, Update, and delete pet-friendly spots
- Have personal spots just for user
- View all spots
- Can filter paw spots by category
- Integrated Map API to help users locate pet-friendly spots

## Running The Project
- `git clone` the repository
- `cd` into the repository
- `bundle`
- `yarn`
- `rails db:create`
- `rails db:migrate`
- `rails db:seed`
- `yarn add react-geocode`
- `yarn add google-maps-react`
- `yarn add @react-google-maps/api`
- `rails s`
- You will need to create your own personal API key for google maps, by going to (https://mapsplatform.google.com/) and registering for a free account. 
- An API key will generate when you create your account. Save this. If you need to access it again, navigate to API's and Services, click on creditials to generate or regenerate your personal API key. 
- Add your personal API key to the project by adding a .env file at the bottom the  app, go into file, type GOOGLE_MAPS_API_Key = "insert personal api key here"
- Never share your personal API key; check .gitignore and make sure that .env is added so your personal API key is never pushed. 
- In you browser (while the server is running 'rails s')`localhost:3000`
- Create an account
- Start Exploring!


## Built With
- React on Rails
- React Strap
- Yarn
- JavaScript
- Active Record
- Heroku

## Test Driven Development
- Jest Testing
- Rspec
- Enzyme
- Backend Testing Coverage: 87.18%
- Frontend Testing Coverage: > 60%

## Dependencies
- "@babel/preset-react": "^7.18.6",
- "@rails/activestorage": "^7.0.3-1",
- "@rails/ujs": "^7.0.3-1",
- "@rails/webpacker": "5.4.3",
- "@react-google-maps/api": "^2.12.2",
- "axios": "^0.27.2",
- "babel-plugin-transform-react-remove-prop-types": "^0.4.24",
- "enzyme": "^3.11.0",
- "enzyme-adapter-react-16": "^1.15.6",
- "google-map-react": "^2.2.0",
- "google-maps-react": "^2.0.6",
- "jest": "^28.1.3",
- "prop-types": "^15.8.1",
- "react": "^18.2.0",
- "react-dom": "^18.2.0",
- "react-geocode": "^0.2.3",
- "react-router-dom": "5.3.3",
- "react_ujs": "^2.6.2",
- "reactstrap": "^9.1.3",
- "webpack": "^4.46.0",
- "webpack-cli": "^3.3.12"

## Contributers
- Corey Arnold
 - Tech Lead
 - [Github](https://github.com/arnoldc94)
 - [LinkedIn](https://www.linkedin.com/in/corey-arnold-744391207/)
- William Segree
 - Design Lead
 - [Github](https://github.com/wasegree)
 - [LinkedIn](https://www.linkedin.com/in/williamsegree/)
- Jordyn Jensen 
 - Product/Project Manager
 - [Github](https://github.com/jordyneajensen)
 - [LinkedIn](https://www.linkedin.com/in/jordyneajensen/)

## Credit and Collaborations
- [Figma](https://figma.com/) for initial wireframing and work flow management.
- [Trello](https://trello.com/) for project management.
- [Stack Overflow](https://stackoverflow.com/) for the struggles.
- [LEARN Academy](https://github.com/learn-academy-2022-delta) for guidance.
- LEARN Staff
    - Elyse Montano
    - Tricia Sykes
    - Sarah Proctor
    - Chantelle Isaacs
- Mentor: Eddie Gomez
- Mentor: Sunjay Armstead