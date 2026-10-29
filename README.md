# Guess the Capital

A simple web game that shows a country and asks you to pick its capital from 4 choices.

## Tech used
- HTML, CSS and JavaScript (front end)
- Nginx in a Docker container
- IBM Cloud Container Registry
- IBM Cloud Code Engine (serverless deployment)

## Run locally with Docker

    docker build -t guess-the-capital .
    docker run -d -p 8080:80 guess-the-capital

Then open http://localhost:8080

## Deployment
The Docker image was pushed to IBM Cloud Container Registry and deployed as an application on IBM Code Engine.

## Credits
Starter code from the IBM Skills Network project template.
