# haunt App - on based Ionic
The project for Ionic that optionally supports using custom SCSS.

Settup this project

We recommend using the ionic-cli.

$ sudo npm install -g ionic
More info on this can be found on the Ionic Getting Started page.
http://ionicframework.com/getting-started

Build


$ cd Haunt
$ sudo npm install -g cordova ionic gulp
$ npm install
$ gulp install
Using Sass (optional)

This project makes it easy to use Sass (the SCSS syntax) in your projects. This enables you to override styles from Ionic, and benefit from Sass's great features.

Just update the ./scss/ionic.app.scss file, and run gulp or gulp watch to rebuild the CSS files for Ionic.

- Run 
$ ionic build android
$ ionic build ios
$ ionic run android
$ ionic run ios
$ ionic serve	(localhost test/development)

- Updating Ionic lib

$ ionic lib update
Issues

Issues have been disabled on this repo, if you do find an issue or have a question consider posting it on the Ionic Forum. Or else if there is truly an error, follow our guidelines for submitting an issue to the main Ionic repository. On the other hand, pull requests are welcome here!
http://forum.ionicframework.com/