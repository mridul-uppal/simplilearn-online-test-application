# Simplilearn Online Test Application

## Objective 

The Online Test Application system creates an application that enables users to provide online tests, review them, and display the results. 
This system contains three main modules: Quiz, Review, and Result. 
The quiz section of the online test application accepts the questions in JSON format. The JSON file can be easily shared from the server in the pre-defined format. The application renders the test at the client-side.
The “Review and display result” section allows users to declare the results immediately. You can simply call another JSON with the answers in it and evaluate and display the results immediately.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.6 and Node version 16.14.0.

## Steps: 
1. Load the welcome page of the application.
2. Now enter user name and start the Test.
3. As the quiz starts timer can be seen running and count of questions and point is up to date.
4. Once user selects correct answer then correct option’s background gets green and count of question get increased and points also got updated as per rule.
5. If th user selects a wrong answer, points get deducted as per rule and incorrect option’s background get red. And on same time Progress bar is also getting Updated. 
6. After submitting the last question of quiz then automatically, we will get Result and Review Module of Quiz Test.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
