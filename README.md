
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

## Why home.html and not index? 

The staging site for this project is on Heroku, and heroku won't run static HTML sites. To get around this, there is a file called index.php that makes Heroku think that this website is a php-based app. All it does is pull in the home.html file. Which brings us to...

## Pushing it live

Rename home.html to index.html and push it live (along with the rest of the assets, obviously). I know that this is clunky, but until there's a better way to trick Heroku, or we use a different auto-deploy for staging, that's the best I can do.





