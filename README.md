# Jax-Eats

> By Dima Kroma
![Part of the Udacity Front-End Web Development Nanodegree](https://img.shields.io/badge/Udacity-React-02b3e4.svg)

# Table of Contents

* [Overview](#overview)
* [Important](#important)
* [How to run the project](#how-to-run-the-project)
* [Dependencies](#dependencies-&-tools-used)
* [APIs Used](#apis-used)
* [Credits & Helpful Links](#credits-&-helpful-links)

## Overview

This is single page application featuring a map of some restaurants in St.Johns Town Center in Jacksonville, FL where I live. 
 Made as the final project of Front End Web Developer Nanodegree .
 it includes making function calls to Google Maps and other location-based services like Foursquare.
 
The app allows you to filter the list down as you type. In return, it displays the locations on the map.

This application follow this [Udacity Project Rubric](https://review.udacity.com/#!/rubrics/1351/view)

## Important

Please note that the **Service Worker** works only in the **production build**. 
The project was created with create-react-app and I used the created service worker for it.

## How to run the project

To run the project in the **development mode**, follow the instructions below: 

Download or clone [this repository in your computer](https://github.com/dimakm/Jax-Eats)

cd to the repository folder, example cd c:/my-app and then in the repository folder:
* install project dependencies with 
```
npm install axios --save
npm install escape-string-regexp --save
npm install react-burger-menu --save
```
* start the server : 
```
npm start
```
* open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Dependencies Used

* I generated the project with `create-react-app`, it includes React and ReactDOM as dependencies and the scripts used by Create React App.
* [axios](https://github.com/axios/axios), a promise based HTTP client for the browser and node.js.
* [Escape RegExp](https://www.npmjs.com/package/escape-string-regexp) special characters.
* [react-burger-menu](https://www.npmjs.com/package/react-burger-menu), a sidebar React component with a collection of effects .


## APIs used

* Google Maps API for the map.
* [FourSquare](https://developer.foursquare.com/) for getting the information for the the restaurants


## Credits & Helpful Links

* [Udacity | Neighborhood Map - Project Explained](https://www.youtube.com/playlist?list=PLgOB68PvvmWCGNn8UMTpcfQEiITzxEEA1) by Yahya Elharony.
*[Working with the markers](https://developers.google.com/maps/documentation/javascript/markers)
* I followed React documentation on [Error Boundaries](https://reactjs.org/docs/error-boundaries.html) for handeling errors.
