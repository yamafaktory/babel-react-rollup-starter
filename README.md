# babel-react-rollup-starter [![Build Status](https://travis-ci.org/yamafaktory/babel-react-rollup-starter.svg?branch=master)](https://travis-ci.org/yamafaktory/babel-react-rollup-starter) [![npm version](https://img.shields.io/npm/v/babel-react-rollup-starter.svg?style=flat)](https://www.npmjs.com/package/babel-react-rollup-starter) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

> A simple starter project to build cool [React](https://facebook.github.io/react/) applications with [Babel](http://babeljs.io/) and [Rollup](http://rollupjs.org/).

The aim of this project is to provide a simple boilerplate to get started with React bundled as an ES2015 module via Rollup, compiled by Babel.

To sum up and give an overview of what can be achieved like a breath of fresh air:

```JavaScript
// Import React and React-dom.
import React from 'react'
import ReactDOM from 'react-dom'

// Import the components.
import { DummyComponent } from './components/dummy-component.jsx'

// Define the root element.
const root = document.querySelector('main')

// Append the DummyComponent to the root element.
ReactDOM.render(<DummyComponent />, root)
```

Rollup will magically include only what you need in your bundle depending on the imports!

## Prerequisite

### NodeJS

The easiest way to go is to use [nvm](https://github.com/creationix/nvm) and to install one of the recent NodeJS versions bundled with npm 3 by default (i.e. *NodeJS >= 5.0.0*).

## Installation

Clone this repository.

```bash
git clone https://github.com/yamafaktory/babel-react-rollup-starter
cd babel-react-rollup-starter
npm i
```

Or even better, use *npm*!

```bash
npm i babel-react-rollup-starter
```

## Usage

### Development

A basic workflow involving [Browsersync](https://www.browsersync.io/) is already implemented. Running the following command will open your default browser pointing to the `html/index-dev.html` file. Any modification of one of the files included in the *src* directory will trigger a new development build and refresh your browser:

```bash
npm test
```

You can also generate a development build by running the following command:

```bash
npm run build:dev
```

### Production

First run the following command:

```bash
npm run build
```

Then open the `html/index.html` file in your browser.

The Rollup production configuration file switch the NodeJS environment to production and minify the code with [UglifyJS](http://lisperator.net/uglifyjs/).

## Linting

The code quality is checked by the [JavaScript Standard Style](http://standardjs.com/).

## License

Released under the [MIT license](https://opensource.org/licenses/MIT) by Davy Duperron.
