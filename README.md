# Postman-Newman Workshop 
## Towards QA Automation Certification

### INTRODUCTION

Using Postman and Newman for Back-End testing is the second of the modules towards the QA Automation Certification.
This repository contains examples on how to implement todoist API testing using Postman, how to use Newman in the cli to be able to integrate this kind of testing into a CI pipeline, and also reporting tests results using html instead of command line output.

The tests implemented here cover topics such as:

- Status Codes
- Content
- json Schema
- Response time
- Negative Scenarios

### HOW TO USE THIS REPO

We followed a conventional directory structure for a full stack project. Pre-requisites is to have installed node.js and Newman. 

For the reporter, it is necessary to install it in this way:

`npm install -i newman-reporter-htmlextra`

### HOW TO RUN THE TESTS

Since the commands have been already entered into the *package.json* file, you can use:

`npm run test` will execute the tests.
`npm run report` will execute the html report.

### NOTES

In order to follow security guidelines, the *token is not included* in the enviroment variables, one solution is to use CircleCI or another provider environment variables set up in order to not disclose private information.  