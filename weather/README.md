# Weather Predictions

![Weather logo](http://ai-i1.infcdn.net/icons_siandroid/png/200/3832/3832023.png "weather logo")

## How to use
On github :

* ```fork the project```
* ```clone the project on your machine```
	
Then on your console :


	$ npm i
	$ npm install -g mocha
	$ npm install jsdoc
	$ node index.js

## Run the test
In the weather directory


	$ mocha

## Available commands

* ```-a, --adress``` enter your own city
* ```-s, --save``` save preset(s)
* ```--long``` enter your longitude (requires ```--lat```)
* ```--lat``` enter your latitude (requires ```--long```)
* ```-c, --config``` use metric
* ```-h, --help``` show help
* ```-v, -verbose``` show your location

## Given informations

* **Current conditions** 
* **Highest temperature**
* **Lowest temperature**
* **If it's rainy, cloudy, sunny, ...**
* **Percentage of precipitation**
* **When the sun rises**
* **When the moon rises**

## How it works
The program gets your IP adress to be able to locate your machine and show the weather predictions for the location of your machine.
The predictions are powered by Forecast.io

## About
Workshop 6 for ESILV by Théo CORIN (oeeht)

## Licence

[Uncopyrighted](http://zenhabits.net/uncopyright/)
