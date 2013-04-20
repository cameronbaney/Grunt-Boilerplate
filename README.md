#Grunt-Boilerplate

This is a project set-up using Grunt to take case of some standard tasks such as: compiling AMD based modules using RequireJS, watching/compiling Sass into CSS, watching/linting JS code and some other things such as running unit tests.

##TODO:

- Look at integrating Jasmine code coverage via `istanbul` plugin
- Write custom task to clean `release` directory after RequireJS has run
- Write custom task to rewrite html to use compiled JS files after successful release build
- Write custom task for renaming un/optimised html files