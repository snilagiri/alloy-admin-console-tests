This repository contains automated E2E test cases for Admin Console UI using [Nightwatch] (http://nightwatchjs.org)
Clone this repository to test the Admin Console UI Tests

git clone https://github.com/snilagiri/alloy-admin-console-tests.git

# Description
Purpose of this repository is to test the automated e2e test cases for Admin Console UI. Providing most of the set up ready configured and as easy as by running git clone and npm install.

Note: 
Running npm install downloads Nightwatch.js, Selenium standalone server, Chromedriver, IE driver and Gecko driver (Firefox) automatically.

# Prerequisites

    NodeJS - for Nightwatch
    Java Runtime - for Selenium standalone server

# Usage

Install dependencies
 npm install

Run tests
# Test against default environment (Chrome)
    npm test 

# Test against all environments (Firefox, Chrome)
    npm run test:all 

