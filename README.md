# Greatest_budget_tracker_ever
This app is for Module 19: Progress Web Applications in my full stack web developer bootcamp.

This app allows you to enter a name and value for financial tracking. The user is able to add funds or subtract funds and have the graph provide visual representation of their budget over a given timeline. This budget tracker app has offline functionality that will allow the user to continue using the app with no connection. Once the user gets back online, the data they submitted while offline will then push up to the database and sync with what was up there.

This app is also a Progressive Web Application (PWA) so it can be downloaded to a mobile device's home screen or to a desktop.

## User Story

```
AS AN avid traveler  
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection  
SO THAT my account balance is accurate when I am traveling  
```

## Acceptance Criteria

```
GIVEN a budget tracker without an internet connection  
WHEN the user inputs an expense or deposit  
THEN they will receive a notification that they have added an expense or deposit  
WHEN the user reestablishes an internet connection  
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated  
```

## Technology Used
```
This project uses the following technologies:  
Javascript  
Node.js  
MongoDB  
Mongoose  
Express  
Service Workers for offline functionality  
Morgan
Compression
```

## Instructions For Use
```
This application can be used by navigating to [https://budget-app-svnday.herokuapp.com/](https://budget-app-svnday.herokuapp.com/)

If running on your local machine, clone the repository.  
Next, install dependencies by running `npm init`  
Start the server by running command `npm start`  
Open your browser and navigate to: [http://localhost:3001/](http://localhost:3001/)  
```

____________________________________________________________________________________________________


Link to repository: [https://github.com/svnday/Greatest_budget_tracker_ever](https://github.com/svnday/Greatest_budget_tracker_ever)  
Link to deployed application: [https://budget-app-svnday.herokuapp.com/](https://budget-app-svnday.herokuapp.com/)
Link to screenshot: ![https://i.imgur.com/ykGIJGM.png](https://i.imgur.com/ykGIJGM.png)
