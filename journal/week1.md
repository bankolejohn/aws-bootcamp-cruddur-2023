# Week 1 — App Containerization

## Take note:

Ensure you set the environment variables before running the app

In running your application, ensure you edit the address to http://localhost:4567/api/activities/home 

Note that the url seems different using gitpod or codespaces but the syntax is the same.  Just ensure you append the /api/activities/home

After running the app successfully, use CTRL*C to quit. 
Then unset the environment variables.
Then navigate to the root folder
And run the docker build command 

## Build container

docker build -t  backend-flask ./backend-flask

otherwise you will keep getting the 404 error.
