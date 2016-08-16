# babel-react-rollup-starter [![Build Status](https://travis-ci.org/yamafaktory/babel-react-rollup-starter.svg?branch=master)](https://travis-ci.org/yamafaktory/babel-react-rollup-starter) [![npm version](https://img.shields.io/npm/v/babel-react-rollup-starter.svg?style=flat)](https://www.npmjs.com/package/babel-react-rollup-starter) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

> A simple boilerplate to build [React](https://facebook.github.io/react/) applications with [Babel](http://babeljs.io/) and [Rollup](http://rollupjs.org/).

## Installation

```sh
npm install --global babel-react-rollup-starter
```

## Usage

### Development

Running the following command will open your default browser pointing to `html/index-dev.html` thanks to [Browsersync](https://www.browsersync.io/). Any modifications to files in *src* directory triggers a new development build and refresh your browser:

```sh
npm test
```

To generate a development:

```sh
npm run build:dev
```

### Production

1. First run the following command:

```sh
npm run build
```

2.  open `html/index.html` in your browser.

The Rollup production configuration file switches the NodeJS environment to production and minifies the code with [UglifyJS](http://lisperator.net/uglifyjs/).

## Linting

The code quality is checked by the [JavaScript Standard Style](http://standardjs.com/).

## License

Released under the [MIT license](https://opensource.org/licenses/MIT) by Davy Duperron.
