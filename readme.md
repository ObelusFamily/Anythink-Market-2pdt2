# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- download and install [Docker](https://docs.docker.com/get-docker)
- verify installation docker -v and docker-compose -v

```sh
    docker -v
    docker-compose -v
```

- run project:

```sh
sh docker-compose up
```

- ping to be sure it's running [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
