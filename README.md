# React and Express with Docker dev and deploy Ready boiler-plate.

-For Local development: cd to both client and server folders and run "npm install" Start the app, cd to server folder and run "npm run dev".
it should start both client and express server.


Using Docker Images:

Note: You have to change the proxy in client/package.json from "http://localhost:8080" to "http://server:8080" before using docker images. 


-For development using Docker containers: on a docker installed machine, run "docker-compose up" on root folder.

-To run Docker Production image: Run "docker-compose -f docker-compose.prod.yml up" on root folder.

Note: if you wanna switch back from docker development to local development, you have to change the proxy in client/package.json back to "http://localhost:8080" and run the local development step.

