# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker via[this link ](https://docs.docker.com/get-docker/)!
2. Check if installation was succesful with `docker -v` & `docker-compose -v`
3. Run `docker-compose up` from the project root directory to load Anythink's backed & frontend.
   If everything went well the backend should now be running and able to connect to your local database.
   Test this with going to `http://localhost:3000/api/ping` in your browser.
4. Check if front-end is connected to backend by going to `http://localhost:3001/register` in your browser and creating a new user.
5. If everything went on smoothly, you should be able to login to the frontend.
