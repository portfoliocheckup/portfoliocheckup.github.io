# portfoliocheckup-dev

### Install gulp and Bower

Requires [node.js](http://nodejs.org/download/). Update to the latest version of npm: `npm install -g npm@latest`.

1. Install [gulp](http://gulpjs.com) and [Bower](http://bower.io/) globally with `npm install -g gulp bower`
2. Run `npm install` in the root directory. This may take a while to compile image minifiers, but this is a one time operation.
3. Run `bower install`

### Available gulp commands

* `gulp` — Compile and optimize the files in your assets directory
* `gulp watch` — Compile assets when file changes are made
* `gulp --production` — Compile assets for production (no source maps).

### Using BrowserSync

To use BrowserSync during `gulp watch` update `devUrl` at the bottom of `assets/manifest.json` to reflect your local development hostname.

### Using Jekyll locally

Requires [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.0, and Bundler (install with `gem install bundler`). On initial setup, run `bundle install` in the root directory.

* `bundle exec jekyll build` — Compile site
* `bundle exec jekyll serve` — Launch a server at http://localhost:4000/ with realtime file watching and compilation