# mobilefirst-angular
Optimized for IBM MobileFirst 7.0 Hybrid Application Development - view the [live preview](https://damianperera.github.io/mobilefirst-angular/) designed for the iPad Pro

## Features
* Simple File & Folder Structure
* Angular 1.4.12
  * Angular JS
  * Angular Animate
  * Angular Messages
  * Angular Mocks
  * Angular Route
  * Angular Sanitize
  * Angular Touch
  * Angular Resource
* Browserify
* HotLoad
* Jasmine
* Karma
* Bootstrap
* Font Awesome
* jQuery

## Download
Installing this package from the official npm repository will create the project structure and install the necessary dependencies.

`npm install mobilefirst-angular`

## Setup
Configures the project to work on IBM Worklight 7.0 inside a _hybrid_ application environment.

1. Copy the project into the `apps/<hybrid-appname>/common/` inside your IBM Worklight 7.0 Project.

2. Reference the IBM Worklight Javascript scripts in the working `index.html` file.

3. Insert `<script>window.$ = window.jQuery = WLJQ;</script>` in the `<head>` section of your working `index.html` file.

4. Run `mfp bd && mfp preview` in the `apps/<hybrid-appname>/` folder of your project.

## Test
This boilerplate uses Jasmine and Karma to run tests, use the following command to start the Karma Test Server.

`npm test`
***
## Project Structure

|-- angular-mobilefirst    
&nbsp;&nbsp;&nbsp;&nbsp;|-- .gitignore  
&nbsp;&nbsp;&nbsp;&nbsp;|-- LICENSE  
&nbsp;&nbsp;&nbsp;&nbsp;|-- README.md  
&nbsp;&nbsp;&nbsp;&nbsp;|-- bower.json  
&nbsp;&nbsp;&nbsp;&nbsp;|-- package.json
&nbsp;&nbsp;&nbsp;&nbsp;|-- install.sh
&nbsp;&nbsp;&nbsp;&nbsp;|-- app  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- main.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- controllers  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- app.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- directives  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- directives.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- factories  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- factories.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- routes  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- routes.js  
&nbsp;&nbsp;&nbsp;&nbsp;|-- docs  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- index.html  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- app  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- bundle.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- main.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- controllers  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- app.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- directives  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- directives.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- factories  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- factories.js   
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- routes  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- routes.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- styles  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- main.css  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- templates  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- template.html  
&nbsp;&nbsp;&nbsp;&nbsp;|-- styles  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- main.css  
&nbsp;&nbsp;&nbsp;&nbsp;|-- test  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- index.html  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- karma.conf.js  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- spec  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- test.js  
&nbsp;&nbsp;&nbsp;&nbsp;|-- views  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- index.html  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- templates  
&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;&nbsp;|-- template.html  
