# WeatherAppv1
A weather app that uses geolocation, OpenWeatherMap api, Eric Flowers's weather icons, SaSS employing nested callbacks


<a href="https://github.com/appijumbo/weatherAppv1/archive/master.zip"><img src="./extras/weather.jpg" width="600"></a>

This weather app is also on [Codepen](http://codepen.io/tom_o/pen/XdXqOB)

It was designed as part of the the [Free Code Camp course](https://www.freecodecamp.com/challenges/show-the-local-weather)

An alternative [version that uses freegoip](https://github.com/appijumbo/WeatherAppV2) not HTML5 geolocation was also coded


## Objectives

Build a CodePen.io app that is functionally similar to this: http://codepen.io/FreeCodeCamp/full/bELRjV.


User Story

  * see the weather in my current location.

  * see a different icon or background image (e.g. snowy mountain, hot desert) depending on the weather.

  * push a button to toggle between Fahrenheit and Celsius.


## Note: This app wont work in Codepen or Github directly

It's recommended to use the Open Weather API. However the Open Weather Api uses http not https.  This means that the <bold>geolocation won't work unfortunatly</bold>, so to use this app [you have to download this app as a zip](https://github.com/appijumbo/weatherAppv1/archive/master.zip)

Should any geolocation problems arrise the console logs a specific error. However for the user this isn't helpful, thus an error like this will be output

<img src="./extras/geoError.jpg" width="600">


