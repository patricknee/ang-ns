# AngNs

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.17.

Steps to create this project:

> ng new ang-ns
routing: y
stylesheets: scss
> cd ang-ns
> ng add @nativescript/schematics --sample

Then open barcelona.module.ts file:

Line 24 exports componentDeclarations. It should export providerDeclarations.

Correcting this line and importing barcelona.module.ts into the app.module.ts file allows the app to respond to:

http://localhost:4200/players

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
