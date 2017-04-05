# ng-module-scaffold

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> This is an Angular 2 Module Scaffold

The idea of ths scaffold is to have a clear and easy one setp to produce single Angular 2 modules for sharing between projects.
The Module can be tested with karma and jasmine.
There is also an Integration of compodoc to generate Documentation out of your Module.

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [NPM Commands](#npm)
- [Contribute](#contribute)
- [License](#license)

## Background

# Source Folder Structure
```
src |
    |
     index.ts (your index file for the Module)
     components
               |
               your components here
     services  |
               your services here
     ...
```

## Install

```
npm install will install the needed libraries for the module and the demo project
```

## Usage

You can use different NPM Scripts to "test", "ts-lint", and "build:ngc" your Module

```
npm run ts-lint for lint the code with the syntaxs checker from the root dir
npm run build:ngc for building your module with inline template and style to the dist folder
npm run start:app Starts the demo application in the /demo folder
npm test for single test run with inline coverage information (ci)
npm run test:coverage for creating coverage html reports under the coverage folder
npm run test:watch for watching on code changes and rebuilding tests at once
```

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

MIT © coodoo
