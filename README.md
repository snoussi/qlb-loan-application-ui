# Quick Loan Bank - UI

Quick Loan Bank UI is an example demo on invoking a decision service based on Red Hat Decision Manager 7.

The Quick Loan Bank UI is based on [AngularJS](https://angularjs.org) and [PatternFly](http://patternfly.org)

## Prerequisites

Verify that the Loan Application Decision Service is up and running here:

http://localhost:8080/kie-server/services/rest/server/containers/loan-application_1.0

If not, follow the instructions here:

https://github.com/snoussi/qlb-loan-application-repo

## Deploying the web UI

1. clone this repo

2. Once you have it, `cd` into your project folder and install the dependencies:

```bash
npm install
```

3. We will use the browsersync tool to serve and refresh our web content 
Start browsersync by running:

```bash
npm start
```

This will start a server at [http://localhost:3000/](http://localhost:3000/) 