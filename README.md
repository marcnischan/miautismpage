
# miautismapp

### The mobile app project for Autism Alliance of Michigan

MiAutism.com - Find autistic-friendly restaurants, hair salons, and places of recreation in the Southeast Michigan area. Like Yelp for parents of autistic children.

## How this thing works

This site collects reviews and stores them in a google doc.

The layout is responsive, and loosely based the [HTML5 Boilerplate](http://html5boilerplate.com) template.

## Local development

In this repo is a file called web-server.js. It is a simple web server you can run by opening the terminal, cd-ing to the project directory and typing: 
    
    node web-server.js. 

This will start a node.js server on port 8002. You can now open a browser and point it to localhost:8002/home.html and see the site on your local machine. You can also open the web-server.js file and change the port to suit your needs.


## Heroku staging server

If you create a git remote called heroku and give it the address of git@heroku.com:miautismpage.git then you can push to it using
    git push heroku master
and see the staging site at miautismpage.herokuapp.com.



