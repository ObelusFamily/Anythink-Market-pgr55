# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker at [Docker](https://docs.docker.com/get-docker/).
2. Make sure Docker is up and running with commands `docker - v` and `docker compose -v`.
3. Run `docker-compose up` in the project directory.
4. Hit the URL [http://localhost:3000/api/ping](http://localhost:3000/api/ping) to check whether the Backend is up and running.
5. Hit the URL [http://localhost:3001/register](http://localhost:3001/register) to check whether the Frontend is up and running. Go ahead and create a new user.
