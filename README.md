[![Northeaster University Logo](https://cloud.githubusercontent.com/assets/8379295/20542121/4363ffce-b0ce-11e6-96ed-cf37b7608e59.png)](https://neu.edu)

# NUMARCOM Wordpress Theme Template

A template for starting a new Wordpress Theme.

## Dependencies

Install with `npm install`.

-   [Bootstrap](http://getbootstrap.com)

## Installation

1.  [Download](../../archive/master.zip) this template.
1.  Unzip and rename the template directory.
1.  Empty [`README.md`](README.md) and fill with your own content.
1.  Move into the new project and `git init`.
1.  Ensure [Node.js](https://nodejs.org/en/) is installed.
>  Once the download and installation is complete, you'll have `Node` and `NPM`
1.  Also be sure to have [Grunt](http://gruntjs.com/) installed. If not run
`npm install -g grunt-cli` in terminal.
1.  Finally, ensure you're in the correct directory for the project and
install dependencies with `npm install`.

## Structure

Dependencies are stored in [`package.json`](package.json).

Store JavaScript files in [`assets/scripts`](assets/scripts).
Grunt will compile all necesssary Javascript files in `dist/assets/scripts/index.min.js`

Styles will be `@import`ed into index.scss and grunt will compile all necessary
autoprefixers and css in `./index.min.css`

## Tasks

Developers should run these often!

-   `grunt watch`: runs watcher function and any changes made in css, js and html will
be compiled
-  `grunt` will compile everything but not include a watcher for development

## [License](LICENSE)
