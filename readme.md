# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
***INSTRUCTIONS***
1. Install Docker
2. Verify that docker is ready to be used, in your terminal enter commands:
     docker -v
     docker-compose -v
3. Run docker-compose up from the project root directory to load Anythinks backend and frontend
4. Test if backend is running and able to connect to local database by pointing browser to http://localhost:3000/api/ping
5. Verify that frontend is able to connect to backend by going to http://localhost:3001/register and creating a new user
6. Good to go!
