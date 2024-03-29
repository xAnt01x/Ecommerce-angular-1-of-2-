# AngularEcommerce

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.7.

## Versions

Tools software versions are:
- nvm 0.35.0;
- npm 7.24.0;
- node 16.10.0;
- tsc 4.6.4;
- Angular 14;
- Spring Boot 2.7.1;

## SETUP

1) Put all the angular files in a folder called, for example, `angular-ecommerce`;
2) Open the GitHub Repository called `Ecommerce-springboot-2-of-2` and catch the files, open in a IDE and run the application. Also, run all the SQL Script files in that repository in the folder `db-scripts` in, for example, MySql Workbench and run all;
3) Enjoy the Ecommerce WebSite!

## User credentials for Login

- email: `ecommerceapp@gmail.com`;
- password: `angularecommerce`;

Try to complete an order!

## Testing Credit Card Payments:

- Number = 4242 4242 4242 4242
- CVC = Any 3 digits
- Expiration Date = Any future date
- Result = SUCCESS

--------------------

- Number = 4000 0000 0000 0002
- CVC = Any 3 digits
- Expiration Date = Any future date
- Result = CARD DECLINED

--------------------

- Number = 4000 0000 0000 9995
- CVC = Any 3 digits
- Expiration Date = Any future date
- Result = CARD DECLINED - INSUFFICIENT FUNDS

--------------------

- Number = 4000 0000 0000 9979
- CVC = Any 3 digits
- Expiration Date = Any future date
- Result = CARD DECLINED - STOLEN CARD

https://stripe.com/docs/testing

## Development server

Run `npm start` for a dev server. Navigate to [https://localhost:4200/](https://localhost:4200/). The application will automatically reload if you change any of the source files.

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
