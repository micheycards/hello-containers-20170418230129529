# Test app for Pluralsight course

This is a quick and dirty test node.js app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub for a Pluralsight video training course..

## Instructions for use
to run a test from the CMD license
./node_modules/mocha/bin/mocha

to run the node program
 node app.js    - then head over to the browser and use http://localhost:8080/

 to build the file using Docker file -   
 docker build -t micheycards/nodejstest .

 docker images - to see your images
 docker ps -a - to see the running images and docker info

 docker run -d -p 8080:8080 micheycards/nodejstest  - then head over to the browser and use http://localhost:8080/
