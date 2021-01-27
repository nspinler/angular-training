# angular-training
Angular - The Complete Guide 2020 training

The Angular Training was done using bootstrap@3.3.7, but the instructions installed Bootstrap 4.x

Angular 2020 Complete Guide

-- Create a base app
ng new <app name>

-- add bootstrap, in app (bootstrap4)
npm install --save bootstrap

-- remove bootstrap
https://loiane.com/2017/08/how-to-add-bootstrap-to-an-angular-cli-project/

-- add bootstrap 3
	• npm uninstall bootstrap 
  • npm install --save bootstrap@3.3.7 
	• Import directly in src/style.css or src/style.scss:
		○ @import '~bootstrap/dist/css/bootstrap.min.css';
	• Or add path to angular.json
	--  to deploy bootstrap with code, go into angular.json -> styles and add the path to bootstrap
	"styles": [
	              "./node_modules/bootstrap/dist/css/bootstrap.min.css",
	              "src/styles.css"
	            ],
	

