# Project 0

Web Programming with Python and JavaScript

	My Project 0 is a personal portfolio web page mock-up. Below the file list are the project requirements and how the requirements are met.

	List of files and contents:
		- about.html
			- About page where an personal overview story could be written about the person
		- contact.html
			- Contact message submission form. The submit button is deliberately disabled for the mock-up
		- index.html
			- Landing page
		- interests.html
			- Some of my interests
		- portfolio.html
			- Project show case
		- services.html
			- Available services that could be provided to potential clients
		- static folder that contains static files
		- static/css
			- sass_main.scss
				- scss styling sheet
			- main.css.map
				- sass mapping to css
			- main.css
				- css styling sheet
		- static/img
			- bg-img.jpg
				- background image used on all the pages
			- image-placeholder.jpg
				- image used in cards on the portfolio page
		- static/templates
			- nav.html
				- HTML used for the navbar that is added to each page.

Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
	- The project includes the following html pages: 
		- about.html
		- contact.html
		- index.html
		- interests.html
		- portfolio.html
		- services.html
		- nav.html
	- Every page is accesible from each other using the hyperlinks in the navigation bar at the top of each page.

Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
	- Multiple lists are used in the interests.html page.
	- A table is used in the services.html page.
	- Every page is using a background image. Additionally, the portfolio.html uses a placeholder image I added.

Your website must have at least one stylesheet file.
	- main.css is the stylesheet file.

Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
	- Five CSS properties used are:
		- font-family
		- background-image
		- text-align
		- margin
		- padding
	- Five CSS selectors used are:
		- element
		- element1, element2
		- element1 element2
		- nth-child(n)
		- #id
		- .class
	- The #id selector used is with id #table_services
	- The .class selector used is with class .page-title


Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
	- The @media query used changes the visibilty of h1 selector

You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
	- The portfolio.html page uses the card component with row/columns to use the grid model

Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
	- SCSS variables include $primary-color, $secondary-color, $font
	- SCSS nesting used is div{ul, ol{} ol ol{}}

In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.
	- You're reading the README.md file