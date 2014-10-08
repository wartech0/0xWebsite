# 0x Website

Website for the irc channel 0x.
Express + Node
[AngularJS](http://angularjs.org/)

## How to use

Clone the repository, run `npm install` to grab the dependencies.

### Running the app

Runs like a typical express app:

    node app.js

## Directory Layout

    app.js              --> app config
    package.json        --> for npm
    public/             --> all of the files to be used in on the client side
      frontend/         --> all frontend angular facing html
        home.html       --> partial for home
      css/              --> css files
        app.css         --> default stylesheet
      img/              --> image files
      js/               --> javascript files
        app.js          --> declare top-level app module
        controllers.js  --> application controllers
        directives.js   --> custom angular directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
        lib/            --> angular and 3rd party JavaScript libraries
          angular/
            angular.js            --> the latest angular js
            angular.min.js        --> the latest minified angular js
            angular-*.js          --> angular add-on modules
            version.txt           --> version number
    routes/
      api.js            --> route for serving JSON
      index.js          --> route for serving HTML pages and partials
    views/
      index.jade        --> main page for app
      layout.jade       --> doctype, title, head boilerplate

## License
MIT
=======
0xWebsite
=========
