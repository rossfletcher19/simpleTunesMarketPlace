# OnlineStore

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.1.

## API KEY THRU FIREBASE

* Create a new file called 'api-keys.ts' in the src/app directory
* Create an account at [Firebase](https://firebase.google.com/) and obtain an api-key
* Then place your Firebase credentials in the 'api-keys.ts' as pictured below:
      `export var masterFirebaseConfig = {
        apiKey: "xxxx",
        authDomain: "xxxx.firebaseapp.com",
        databaseURL: "https://xxxx.firebaseio.com",
        storageBucket: "xxxx.appspot.com",
        messagingSenderId: "xxxx"
      };`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
