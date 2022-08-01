# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To run Docker

First install Docker and very if it is installed properly by typing docker -v in the terminal

Now go to the folder where you have cloned the repository and go to the root directory which contains both frontend and backend dirs. Then run docker-compose up command.

To verify whether docker is running properly. Open this link http://localhost:3000/api/ping in the browser if it doesn't show any errors. Then you are good to go.