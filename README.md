# Bookmark CRUD REST API with NestJS

Sample project to study NestJS making a CRUD, auth and jwt strategy, with tests end-to-end (e2e) with PactumJS.


## Pre-requirements

To run this project, you will need:

- [git](https://git-scm.com/downloads) (I've used version `2.26.2`)
- [nodejs](https://nodejs.org/en/) (I've used version `v16.15.0`)
- NPM (I've used version `8.5.5`)
- [Yarn](https://yarnpkg.com/) (I've used version 1.22.15)
- [Docker](https://www.docker.com/) (I've used Docker version 20.10.14 with Docker Desktop and wsl2)
**Note:** When installing nodejs, NPM is automatically installed too.

## Installation

First clone the repo into your machine with: 
`git clone https://github.com/eduardorerick/nestjs-bookmarks.git`

To install the dev dependencies, run: 
`yarn`

## Configuring the environment variables

I uploaded the env files so you can use it for test!

## Importing to insomnia

You can import the Insomnia.yaml file to Insomnia to see all the endpoints

## Running the database 

In this project, I run the database with a postgres image on docker.

you can run the database and run the migrations with the command: 
`yarn db:dev:restart`

### Running the server 

Run `yarn start:dev` to run the server on port 3333.

### Running the tests 

I make the tests run on a different docker db that i called 'test-db'
You can run `yarn test:e2e` to up the test-db image, apply migrations and run tests.

---

Made with ❤️ by [Eduardo Rerick](https://github.com/eduardorerick).
