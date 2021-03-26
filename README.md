# Udacity Front End Nanodegree - Travel App Project

This **Travel App Project** source code is submitted to [Udacity](https://www.udacity.com/ "Udacity") for reviewing purposes.

## 1. Project Summary

This project aims to give you the opportunity to put all of the skills you have learned into one project to build your own custom travel app. Due to the nature of this course, it is very JavaScript heavy, but it is still expected you create clean and appealing HTML/CSS. You will also be targeting the DOM, working with objects, and retrieving data from 3 APIs in which one of those is reliant on another to work. Finally, this is all going to be done in a Webpack environment, using an express server, and wrapped up with service workers.

## 3. API Credentials

* Create an user account at [Geonames](https://www.geonames.org/ "Geonames"), [WeatherBit](https://www.weatherbit.io/ "WeatherBit") and [Pixabay](https://pixabay.com/ "Pixabay") respectively to obtain the API keys.
* Create a file named `.env` with the following code and your API credentials.
```
GEONAMES_USER=your Geonames username
WEATHERBIT_KEY=your WeatherBit API key
PIXABAY_KEY=your Pixabay API key
```

## 4. Installation Guide

* Download the app zip file
* Unzip it from the desktop
* Move the newly created .env file to the root directory of this app folder
* Install node.js - https://nodejs.org/
* Install all modules listed as dependencies in package.json; terminal command line - `npm install`
* Run JEST testing; terminal command line - `npm test`
* Run production environment and build/update dist folder; terminal command line - `npm run build-prod`
* Run local server (http://localhost:8081/); terminal command line - `npm run start`
