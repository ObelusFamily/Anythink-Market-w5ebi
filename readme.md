# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps to run this repository locally:

1. Clone the repository locally using command

```
git clone https://github.com/ObelusFamily/Anythink-Market-w5ebi.git
```

2. Install [Docker](https://docs.docker.com/get-docker/)

   1. You can verify if docker is installed or not by running following commands in your terminal `docker -v` and `docker-compose -v`

3. Run `docker-compose up` from project root directory

4. If docker is running correctly, the backend should be running and able to connect to local database. Test this by going to [http://localhost:3000/api/ping](https://docs.docker.com/get-docker/)

5. Now check if frontend is working and connected to backend by creating a new user at [http://localhost:3001/register](http://localhost:3001/register)
