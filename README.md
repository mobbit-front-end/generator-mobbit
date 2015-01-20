# Front-end project generator

> [Yeoman](http://yeoman.io) generator that scaffolds out a front-end project using [gulp](http://gulpjs.com/) for the build process

## Features

Please see our [gulpfile.js](app/templates/gulpfile.js) for up to date information on what we support.

* CSS Autoprefixing
* Built-in preview server with BrowserSync
* Automagically compile Sass with [libsass](http://libsass.org)
* Automagically lint your scripts
* Awesome image optimization
* Automagically wire-up dependencies installed with [Bower](http://bower.io)

*For more information on what this generator can do for you, take a look at the [gulp plugins](app/templates/_package.json) used in our `package.json`.*

## Getting Started

- Install dependencies: `npm install -g yo bower`
- Install the generator: `npm install -g generator-mobbit-front-end`
- Run `yo mobbit-front-end` to scaffold your project
- Run `gulp dev` to preview and watch for changes
- Run `bower install --save <package>` to install frontend dependencies
- Run `gulp` to build your project for production

## License

[BSD license](http://opensource.org/licenses/bsd-license.php)