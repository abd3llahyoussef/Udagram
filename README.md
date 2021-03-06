# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Getting Started

1. Clone this repo locally into the location of your choice.
2. Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
3. Open a terminal and navigate to the root of the repo
4. follow the instructions in the installation step

The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project

### Dependencies
A list of project dependencies can be found [here](docs/dependencies.md).

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
2. In AWS, provision a s3 bucket for hosting the uploaded files.
3. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv).
4. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. 
5. After installation is done start the api in dev mode with `npm run dev`.
6. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

### app Badge 
[![CircleCI](https://circleci.com/gh/abd3llahyoussef/Udagram.svg?style=svg)](https://app.circleci.com/pipelines/github/abd3llahyoussef/Udagram/16/workflows/d0bbc56b-5c2b-4eec-803b-38c657bae654)

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End-to-End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
