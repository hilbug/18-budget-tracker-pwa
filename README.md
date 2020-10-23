# Budget Tracker Progressive Web App
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
A budget tracker progressive web app which allows for offline access and functionality. This app leverages IndexedDB so transactions are saved if there is no internet connection. Upon reconnection to the internet, the stored transactions are posted to MongoDB Atlas.

### Deployed App
Check out [Budget Tracker](https://secret-badlands-22359.herokuapp.com/) on Heroku!

### App Preview
![Budget Tracker](https://user-images.githubusercontent.com/65197724/96949323-a6806300-14b5-11eb-92e7-07b2dd237515.gif)

### Technologies Used
- HTML/CSS
- IndexedDB
- JavaScript
- Express
- Mongoose
- Morgan
- Compression
- MongoDB Atlas
- Heroku
- Nodemon

## Honorable Mentions
- Starter code provided by Trilogy Ed. 
- Thanks to fellow classmates for their trouble-shooting assistance!

## User Story
```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Acceptance Criteria
```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```

## Future Development
- Allow a user to edit or remove transactions
- Beautify the UI
- Add individual login capability