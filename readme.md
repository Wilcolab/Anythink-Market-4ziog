# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone this repo onto your machine by running
`git clone https://github.com/ObelusFamily/Anythink-Market-4ziog.git`

Start the docker containers provided by running

```cd ../Anythink-Market-4ziog
docker-compose up
```

Check if the backend is properly setup by opening `http://localhost:3000/api/ping` on your browser

Check if the frontend is properly setup by opening `http://localhost:3000/register` on your browser
