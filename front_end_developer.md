# Front End Web Developer

## Planning
	* From mocks or wireframes, use HTML and CSS to create a static interface
		* Select CSS Framework to accomplish grid layout
		* Select theme, or build out custom theme for repeated chunks and main layout stuff
			* Background color and pattern
			* Model blocks, like generic lists of content or product listings
		* Decide on preprocessor framework
	* Add major interaction points (like drag and drop, wizards) with js
	* Decide on libraries to integrate (like jQuery, Modernizr, Backbone, Flat Design, YUI, etc)

## Building
	* Install dependencies
	* From static layout, create interactive interface by adding JS
	* Add data persistence by hooking up either templates or a front-end framework
	* Write tests against critical interaction points
	* Hook up user interactions to data model
	* Add front-end validation
	* Write front-end tests to ensure interface behaves in a uniform way
	* Add front-end i18n http://www.w3.org/International/questions/qa-i18n
	* Integrate templates into front-end

## Tuning
	* Setup preprocessor to build and minify CSS and JS
	* Add images to CDN
	* Setup grunt/gulp scripts to ensure static assets are piped to CDN
	* Run performance analysis on front-end, ensure "golden second" standard is reached for mobile
	* Write front-end tests