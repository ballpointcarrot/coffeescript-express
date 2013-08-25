Coffeescript Express
====================

This is a port of the default express project template, with all javascript 
files converted to coffeescript, for those who prefer to use coffeescript as 
their primary language.

This express 'starter kit' also provides asset management via 
[connect-assets](https://github.com/TrevorBurnham/connect-assets), which 
allows coffeescript-to-js conversion of client-side code, as well as support 
for less/stylus stylesheet generation.

Requirements
------------

You need to have the following in order to run this setup (the last tested versions
are marked in parentheses):
 * Node.js (0.10.17)
 * Express (Global install) (3.3.5)
 * Coffeescript (Global install) (1.6.3)
 * connect-assets (2.5.2)

Usage
-----

cloning the repository, run the following:

	git clone https://github.com/iddar/coffeescript-express.git
	
	npm install -g coffee-script express
	npm install

	coffee app.coffee
	or
	npm start
	or
	nodemon app.coffee (recommend for develop time. require `npm install -g nodemon` )

this will start up your express coffeescript app, and you're ready to go.

