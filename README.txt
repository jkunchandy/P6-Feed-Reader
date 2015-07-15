README file

Description:
	This application contains test procedures using Jasmine framework to validate code which displays a Google
	feedreader. The application will automatically run the individual tests (called specs) and use the lower
	half of the browser page to show the results.

	Clicking on the "Jasmine__TopLevel__Suite" label will display all the tests available and give the user the
	option to run all the specs.  Initially the run status row will show like this - "Ran 0 of 7 specs - run all".
	Clicking on "run all" will run all the specs.
	The row showing the results of a run will show as - " 0 specs, 0 failure "

	The tests are broken down to 4 categories. To run the tests for a single category just click on the category.
	The categories are:
		RSS Feeds
		The menu
		Initial Entries
		New Feed Selection

	The indviduals tests (specs) for each category are as follows:
		RSS Feeds
				are defined
				URL defined and not empty
				Name defined and not empty
		The menu
				Menu element hidden
				Menu changes visibility when clicked
		Initial Entries
				loadFeed adds atleast 1 entry to feed container
		New Feed Selection
				loadFeed modifies feed entry content


	The user can click on a category to run all the specs for that category.
	The user can also click on a particular spec to just ran that spec.


The files that make up this app:
	html file initially loaded into browser
		index.html,
	css files
		css/style.css,
		css/normalize.css,
		css/icomoon.css,
	fonts
		fonts/icomoon.eot,
		fonts/icomoon.svg,
		fonts/icomoon.ttf,
		fonts/icomoon.woff,
	user js code
		js/app.js
	jasmine install
		jasmine/lib/jasmine-2.1.2/boot.js
		jasmine/lib/jasmine-2.1.2/console.js
		jasmine/lib/jasmine-2.1.2/jasmine-html.js
		jasmine/lib/jasmine-2.1.2/jasmine.js
		jasmine/lib/jasmine-2.1.2/jasmine.css
		jasmine/lib/jasmine-2.1.2/jasmine_favicon.png
	user jasmine test code
		jasmine/spec/feedreader.js
	overview of completed code and folder contents
		README.txt,
	overview of original requirements
		README.md,
	grading expectations
	    Rubric.png,
    jquery
    	jquery-2.1.3.min.js,
    knockout
    	knockout-3.2.0.min.js
    Google fonts
    	http://fonts.googleapis.com/
     Ajax
     	http://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js
     Handlebars
     	http://cdn.jsdelivr.net/handlebarsjs/2.0.0/handlebars.min.js
     JSApi
     	http://google.com/jsapi

To run this app:
	In the browser window type - index.html

To exit this app:
	Close the browser page
