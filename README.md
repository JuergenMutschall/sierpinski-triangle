Experiments with making async rendering LitElement.

Don't use this, it's just an experiment.

to start a simple web server

new file server.js:

var connect = require('connect');
var serveStatic = require('serve-static');
connect().use(serveStatic(__dirname)).listen(8080, function(){
    console.log('Server running on 8080...');
});


npm install connect serve-static

change locations to relative files in lit-element.js


node server