# Udagram

This application is a fairly simple application that includes all the major components of a Full-Stack web application. You can use the application when you practice Amazon Web Services(AWS) and circleCI. The code of the application is mostly provided by Udacity. Please refer to [this](https://github.com/udacity/nd0067-c4-deployment-process-project-starter)
for getting original starter code for deployment practicing. 


## Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, run `npm run backend:install` to install the node_modules. After installation is done, navigate to udagram-api folder by running `cd udagram-api` and start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, run `npm run frontend:install` to intall the node_modules. After installation is done, navigate to the udagram-frontend by running `cd udagram-frontend` and start the frontend in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd udagram-frontend`
1. `npm run test`
1. `npm run e2e`

Please aware of this project has no Unit test on the back-end.

## CircleCi pipeline status
The status of the last build:
[![<ORG_NAME>](https://circleci.com/gh/choiyounyeong/udacity-deploy-fullstack-js-app.svg?style=svg)](<LINK>)


## Access Front-End application
Click [this link](http://udacity-deployment.s3-website-us-east-1.amazonaws.com) for accessing the hosted working Front-End Application.


## Others

### Requirement of dependencies
Please refer to dependencies.md file in the docs folder.

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

### Built With

- [Angular](https://angular.io/)
- [Node](https://nodejs.org)
- [Express](https://expressjs.com/)
