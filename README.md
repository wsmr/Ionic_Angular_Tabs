# Ionic_Angular_Tabs
ionic 4.1.1<br>
$ ionic start name tabs --type ionic-angular<br>


Ionic Angular
Ionic Angular (ionic-angular) uses Angular 5 and @ionic/app-scripts for tooling.

You can start a new Ionic Angular app with the following command:

$ ionic start --type=ionic-angular
See Starter Templates for a list of starters for Ionic Angular.

Ionic Angular apps are written in TypeScript and Sass and are compiled and built with @ionic/app-scripts, which is a configurable build system optimized for Ionic Angular.

ionic build and ionic serve use @ionic/app-scripts out of the box, so it doesn’t need to be invoked directly. It also ships with good defaults, but can be configured in a variety of ways. See README.md for configuration details.

Project Structure<br>
project/ <br>
├─ ionic.config.json # Ionic project config file<br>
├─ package.json<br>
├─ src/<br>
│  ├─ app/<br>
│  │  ├─ app.component.ts # root component for your app<br>
│  │  ├─ app.html # app component template<br>
│  │  ├─ app.module.ts # NgModule for app component<br>
│  │  ├─ app.scss # global SCSS<br>
│  │  └─ main.ts # bootstrap file<br>
│  ├─ assets/ # put your images, etc. here<br>
│  ├─ pages/ # contains the page components for your app<br>
│  ├─ theme/<br>
│  │  └─ variables.scss # see https://ionicframework.com/docs/theming<br>
│  └─ index.html # main html file<br>
└─ www/ # build output directory<br>

