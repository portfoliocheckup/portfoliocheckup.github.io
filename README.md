portfoliocheckup.github.io
==========================

portfoliocheckup.com


### Install gulp and Bower

Requires [node.js](http://nodejs.org/download/). Update to the latest version of npm: `npm install -g npm@latest`.

1. Install [gulp](http://gulpjs.com) and [Bower](http://bower.io/) globally with `npm install -g gulp bower`
2. Run `npm install` in the root directory. This may take a while to compile image minifiers, but this is a one time operation.
3. Run `bower install`

### Available gulp commands

* `gulp` — Compile and optimize the files in your assets directory
* `gulp watch` — Watch files and compile assets when file changes are made
* `gulp --production` — Compile assets for production (no source maps).