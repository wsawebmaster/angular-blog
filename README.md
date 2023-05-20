# AngularBlog

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.2.

## Create Blog Project
  Run `ng new angular-blog` in your project<br />
  Clean app.component.html file contents, keeping only `<router-outlet></router-outlet>`<br />
  Set style in main css<br />
  `* {
    margin:0;
    padding:0;
    box-sizing: border-box;
    background-color: #111111;
  }`
  <br />
  Run `ng g c components/menu-bar`<br />
  Run `ng g c components/menu-title`<br />
  Run `ng g c components/big-card`<br />
  Run `ng g c components/small-card`<br />
  Delete the .spec.ts files<br />
  Add `<app-small-card>` to app.component.html file

### Creating menu-title
  Copy app-big-card from the big-card.component.ts file and add the `<app-big-card>` tag to the app.component.html file<br />
  Added styling to menu-title
### Creating big-card
  create pages directory in app<br />
  create component for home<br />
  ng g c pages/home
### Creating content
  ng g c pages/content

### Creating other pages
ng g c pages/content

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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
