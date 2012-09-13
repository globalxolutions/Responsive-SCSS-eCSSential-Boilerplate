The Responsive SCSS eCSSential Boilerplate is a front-end framework created by
designer and developer Ryan Roth to be utilized in the creation of
mobile-first responsive designs by his company, Dropseed Solutions, LLC. (http://dropseedsolutions.com).

The boilerplate has a number of major components. They include:

	1. The Semantic Grid System (http://semantic.gs)
	
	2. Adaptive-Images (http://adaptive-images.com)
	
	3. Font Awesome (http://fortawesome.github.com/Font-Awesome/)
	
	4. eCSSential (https://github.com/scottjehl/eCSSential)
	
At its root, the boilerplate is an amalgation of different techniques from
equally brilliant and talented developers. Ryan and Dropseed Solutions
thanks them for their tireless commitment to quality and openness. They include:

	1. 320 and Up (http://stuffandnonsense.co.uk/projects/320andup)
	
	2. HTML5 Boilerplate (http://html5boilerplate.com)
	
	3. Normalize CSS (http://necolas.github.com/normalize.css)
	
	4. Inuit CSS (http://csswizardry.com/inuitcss)
	
	5. Skeleton (http://www.getskeleton.com)
	
	6. Eric Meyer (http://meyerweb.com/eric/tools/css/reset)
	
To use the boilerplate:

	1. Read about the Semantic grid to get an idea of how to use it.
		
		a) It's as simple as adding @include column(6); to your css class or id
	
	2. Adaptive Images automatically caches and resizes images for responsive designs
		
		a) Place all images to be cached and resized (think images that are not repeatable, layout design type images; more content images) in the img directory
		
		b) Make the img/cache directory world-writable on your server (chmod 777)
		
		c) Place images not to be resized in assets/img
		
		d) DONE!
	
	3. Writing your SCSS:
		
		a) In your Ruby prompt change directory all the way to the assets folder of the boilerplate and do the following:
		
			sass --watch scss:css
		
		b) Write SCSS which pertains to devices with a min-width of 320PX inside scss/all.scss
		
		c) Write other SCSS inside the file with the EM value to which it is pertinent
		
	