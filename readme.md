# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/).
    - On Linux, install [Docker compose](https://docs.docker.com/compose/install/) separately.
    - On Windows, [WSL](https://docs.microsoft.com/en-us/windows/wsl/install) v2 needs to be installed and enabled.
2. Run `docker-compose up` from the root directory.
