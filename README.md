AngularMongo
============

Requirements:

1. Ubuntu 14.04
2. Node
3. MongoDB 

App to demonstrate AngularJS , node and  mongodb CRUD


Project scaffold by YEOMAN and configure node.js with express and angular.
CRUD based on mongodb.

Note: This a simple example of crud using mongoDB, so login and session controls does not in this projetc.
But in future evolutions!

How to Install
==============

Clone the project

`$ cd AngularMongo`

`$ npm install`

`$ bower install`


find in npm module mongodb ..node_modules\mongodb\node_modules\bson\ext\index.js

and change path to js version in catch block

bson = require('../build/Release/bson');
to
bson = require('../browser_build/bson');

`$ node app.js` or `$ npm start`

Open your web browser 

[http://localhost:3000/app/#/people](http://localhost:3000/app/#/people)

Execute Tests
=============

Necessary Karma installed!

On project Root

`karma start test/karma.conf.js`

Or Grunt test

`grunt test`


Sources:

1. [http://yeoman.io/](http://yeoman.io/)

2. [https://angularjs.org/](https://angularjs.org/)

3. [http://nodejs.org/](http://nodejs.org/)

4. [http://www.mongodb.org/](http://www.mongodb.org/)
