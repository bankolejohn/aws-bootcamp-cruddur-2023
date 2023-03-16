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

## Run the container

    docker run --rm -p 4567:4567 -it backend-flask

App not running

Set the environment variables.... app still not runnning

Goto the container and attach shell

### set environment variables in the run command 

    docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKEND_URL='*' backend-flask

Note: To run the container in the background append '-d' before the image

### containerise the frontend

Navigate to the frontend directory

Create a docker-compose.yml file which would allow one to run multiple containers at the same time

After which you run the docker-compose up command 

After the process you get to access the app in  a more beautiful way.

so exciting to have gotten to this stage

![Screenshot 2023-03-16 034814](https://user-images.githubusercontent.com/76499525/225499217-51878c1f-9784-4ca1-be9e-e85a13df59eb.png)

