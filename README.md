# [html5boilerplate.com](https://html5boilerplate.com/)

[![Build Status](https://travis-ci.org/h5bp/html5boilerplate.com.svg)](https://travis-ci.org/h5bp/html5boilerplate.com)
[![devDependency Status](https://david-dm.org/h5bp/html5boilerplate.com/dev-status.svg)](https://david-dm.org/h5bp/html5boilerplate.com#info=devDependencies)

The HTML5 Boilerplate website is a simple static site:

* The [development](http://www.heygates.co.uk) code is in the [`src/`](src) directory.
* The build process relies on [`gulp`](https://gulpjs.com/).
* The `gulp` tasks can be found in the [`gulpfile.js`](gulpfile.js)
  file.

## Setup

1. Install [`Node.js`](https://nodejs.org/) and
   [`npm`](https://docs.npmjs.com/getting-started/installing-node).
2. Run `npm install`.

## Development

You should be able to work almost entirely in the [`src/`](src)
directory.

While developing run `npm run serve` as this will open the website
in your default browser and automatically update it whenever changes
are made to the page or any of the files contained in the page.

## Build

When you have finished your changes, make sure that the distribution
package is correct by running `npm run test` and then checking the
output.

The site is served directly from the `docs/` directory
