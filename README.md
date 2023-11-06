# Hosting a Full-Stack Application

---

## Description

This capstone project build application onto AWS
Technology use:
- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## Constraints and Dependencies
1. This project work with Node 14.15 version
2. Other Node version has not been confirm

## Project Setup - Run Locally

1. Clone the project:
2. Follow same step as mention in `https://learn.udacity.com/nanodegrees/nd0067/parts/cd0295/lessons/f7bb992e-47f6-40e1-82f3-87d93be600cc/concepts/bc8fc127-4be0-404c-9177-5ab035dc8215`

## Project Setup - Run on AWS Cloud
1. Provisonal
- IAM user with access key
- S3 with public access
- RDS with public access (make sure to check connection via psql or pgadmin)
- ElasticbeanStalk

2. Push Project to Git

3. Link CircleCI to the Git poject

4. Configure Circle CI with variable as mentioned in `./deployment-process/screenshots/CI-Env.png`

5. Any changes commit to master branch should trigger build/test/deploy process as defined in config.yml
## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Documentation

- Screenshots: `./deployment-process/screenshots/`.
- Architecture Diagrams : `./deployment-process/architecture-diagram/`.
