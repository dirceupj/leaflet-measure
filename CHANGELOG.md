leaflet-measure Changelog
=========================

## 3.0.0 (2018-02-14)

* Updated build from Grunt/Browserify to [Webpack](https://webpack.js.org/)
* Moves from jshint/jscs to [ESLint](https://eslint.org/)
* Reduced the number of external dependencies to get build down to under 40KB
* Now using better maintained [Turf.js](http://turfjs.org/) instead of [geocrunch](https://github.com/brandoncopeland/geocrunch) for distance and area calculations.
* Updates styles to better match the styles applied to `.leaflet-bar`. Previous styles were based on the Leaflet layer control.