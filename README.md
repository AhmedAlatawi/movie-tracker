# MOVIE TRACKER

![Sample UI](screenshot.gif)

## Synopsis
This project is working off the The Movie DB API (https://www.themoviedb.org/documentation/api - note you'll need to go create an account to get an API key). The idea of the project is to be able to sign in as a user and save favorite movies. Pretty simple right? HA HA not!

## Built With
* JQuery
* CSS
* HTML
* React
* Redux

## Contributors

* Jason Lucas
* Ana Jauregui
* Travis Rollins

## Original Assignment - Turing MOD3

Movie Tracker

#### Specifications

Iteration 0: Pull in movie API

  * Pull most recent movies from MovieDB API.
  * Display each movie on root index /

Iteration 1: Sign In / Sign Out Functionality

* Be able to sign in on page /login and redirect user to /
  * Flash "Email and Password do not match" - if password is incorrect
* Ability to create a user.
  * Flash "Email has already been used" - if email has been taken
* The user has the ability to sign out.

Iteration 2: Favorites

* Each movie should be displayed with a favorite button.
* If the user is not signed in and clicks on a favorite button the user will be prompted with the request to create an account.
* Validate favorites before adding to db. Aka does that user already have the movie stored as favorites. There should be no duplicates.
* If the user visits /favorites they should see a list of all their favorite movies.
* The user should be able to delete favorites from /favorites or /.
* Favorite movies should have a visual indication on /.
