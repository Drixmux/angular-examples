# Deploy Angular App using Nginx and Docker

This project has an angular app being deployed using nginx and docker.

## Steps to try this project

- Create the image that builds the app and prepares it for deployment by running `docker build -t ng-docker-app:v1.0.0 -f ./Dockerfile .`
- Start a new container using the image generated in the previous step by running `docker run -p 8000:80 -d ng-docker-app:v1.0.0`


