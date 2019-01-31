# EnvTestApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.3.

We have created environment specific files under src/environment folder
and using some parameters which will be accessed(apiUrl) with correspnding value 
from environmetn in app.component.ts

Added entry under configuration section in angular.json for both build & serve

we can build it using 
ng build --configuration=ute3/ute1(env_name)
ng serve --configuration= ute3/ute1

No need to use serve configuration if we are using separate application server(node.js)
then only build is required which will create dist folder & will be serveed
using node server.js command
need to create server.js and install express

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build


Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
