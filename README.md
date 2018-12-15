# Ionic_Angular_Tabs
ionic 4.1.1 $ ionic start name tabs --type ionic-angular


Ionic Angular
Ionic Angular (ionic-angular) uses Angular 5 and @ionic/app-scripts for tooling.

You can start a new Ionic Angular app with the following command:

$ ionic start --type=ionic-angular
See Starter Templates for a list of starters for Ionic Angular.

Ionic Angular apps are written in TypeScript and Sass and are compiled and built with @ionic/app-scripts, which is a configurable build system optimized for Ionic Angular.

ionic build and ionic serve use @ionic/app-scripts out of the box, so it doesn’t need to be invoked directly. It also ships with good defaults, but can be configured in a variety of ways. See README.md for configuration details.

Project Structure
project/
├─ ionic.config.json # Ionic project config file
├─ package.json
├─ src/
│  ├─ app/
│  │  ├─ app.component.ts # root component for your app
│  │  ├─ app.html # app component template
│  │  ├─ app.module.ts # NgModule for app component
│  │  ├─ app.scss # global SCSS
│  │  └─ main.ts # bootstrap file
│  ├─ assets/ # put your images, etc. here
│  ├─ pages/ # contains the page components for your app
│  ├─ theme/
│  │  └─ variables.scss # see https://ionicframework.com/docs/theming
│  └─ index.html # main html file
└─ www/ # build output directory
