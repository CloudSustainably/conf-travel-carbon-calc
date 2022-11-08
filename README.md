# Conference Travel Carbon Calculator

available on:

https://cloudsustainably.github.io/conf-travel-carbon-calc

responses recorded:

https://docs.google.com/spreadsheets/d/1SM8IlYevP5Iaomzpy-cPImRRTIoMX8fjs3xGWQy5XCM/edit?usp=sharing

## To run locally

clone the repo:

`git clone https://github.com/CloudSustainably/conf-travel-carbon-calc/`

`cd conf-travel-carbon-calc`

install the dependencies:

`yarn`

run the project:

`yarn start`

this will run a server locally that you can access on

http://localhost:3000

Changes you make will be automatically rendered in the browser.

Changes to the `settings.yaml` will only take effect once you stop and start the server

## Deploy

Github is configured to automatically build and deploy the app to github pages when changes are made on the `main` branch

To deploy the website manually or to a different URL then ensure that the correct URL is configured in the app and then run

`yarn build`

This will generate a `/build` folder.

You can then copy the contents of this to your web server or to AWS S3.

## Setup

The url must be whitelisted in the google API
