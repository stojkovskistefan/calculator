Calculator
---
[![Build Status](https://travis-ci.org/DurandA/calculator.svg?branch=master)](https://travis-ci.org/DurandA/calculator)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=DurandA_calculator&metric=coverage)](https://sonarcloud.io/component_measures?id=DurandA_calculator&metric=coverage)

<img src="Logotype primary.png" width="60%" height="60%" />

Created with *create-react-app*. See the [full create-react-app guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).



Try It
---

[ahfarmer.github.io/calculator](https://ahfarmer.github.io/calculator/)



Install
---

`npm install`



Usage
---

`npm start`



Continuous Integration
---

This project uses [Travis-CI](https://travis-ci.org/) as a continuous integration tool.

## Unit testing

Run unit tests using `npm test --`.

## Static code analysis

[SonarCloud](https://sonarcloud.io/), a cloud-based service based on [SonarQube](https://www.sonarqube.org/), perfoms analysis on [code quality](https://www.sonarsource.com/why-us/code-quality/). It is configured in *sonar-project.properties* file and enabled by adding the *sonarcloud* addon in *.travis.yml*. To analyse code coverage, unit tests should generate code coverage reports using `npm test -- --coverage`.

## Linting

[ESLint](https://eslint.org/) performs style checking on code according to the rules specified in *.eslintrc* file. *.eslintrc* can be generated using `./node_modules/.bin/eslint --init --help`.

## Building and deployment

The project is built and deployed on GitHub Pages using [GitHub Pages Deployment](https://docs.travis-ci.com/user/deployment/pages/).
