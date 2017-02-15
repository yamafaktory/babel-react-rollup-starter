# babel-react-rollup-starter [![Build Status](https://travis-ci.org/yamafaktory/babel-react-rollup-starter.svg?branch=master)](https://travis-ci.org/yamafaktory/babel-react-rollup-starter) [![npm version](https://img.shields.io/npm/v/babel-react-rollup-starter.svg?style=flat)](https://www.npmjs.com/package/babel-react-rollup-starter) [![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)


> A simple boilerplate for web apps with [React](https://facebook.github.io/react/), [Babel](http://babeljs.io/), and [Rollup](http://rollupjs.org/).

## Installation

Via **npm** into a fresh project:

```sh
npm i babel-react-rollup-starter
```

Or using Git:

```sh
git clone https://github.com/yamafaktory/babel-react-rollup-starter.git
cd babel-react-rollup-starter
npm i
```

For a faster installation, use [yarn](https://yarnpkg.com/en/) instead of npm.

## Usage

### Development

Running the following command will open your default browser to `html/index-dev.html`. Thanks to [Browsersync](https://www.browsersync.io/), any modifications inside `src` trigger a browser refresh:

```sh
npm start
```

To generate a development bundle:

```sh
npm run build:dev
```

### Production

1. First run the following command:

 ```sh
 npm run build
 ```

2. Open `html/index.html` in your browser.

The Rollup production configuration file changes `NODE_ENV` to production and minifies the code with [UglifyJS](http://lisperator.net/uglifyjs/).

## Linting

The code quality is checked by the [JavaScript Standard Style](http://standardjs.com/).

## License

Released under the [MIT license](https://opensource.org/licenses/MIT) by Davy Duperron.
