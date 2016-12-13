# static-bootstrap

Bootstrap for static site with gulp + pug + minify + uglify + image optimization

[![Build Status](https://travis-ci.org/danielrohers/static-bootstrap.svg?branch=master)](https://travis-ci.org/danielrohers/static-bootstrap)
[![devDependency Status](https://david-dm.org/danielrohers/static-bootstrap/dev-status.svg)](https://david-dm.org/danielrohers/static-bootstrap#info=devDependencies)

## Requirements

#### Install NodeJS
- https://nodejs.org/en

#### Install dependencies
```bash
[sudo] npm install
```
or
```bash
yarn
```

## Structure

```
|-- project
|   |-- _includes <-- Include files - https://pugjs.org/language/includes.html
|   |   |-- footer.pug
|   |   |-- navbar.pug
|   |-- _layouts <-- Layout files - https://pugjs.org/language/extends.html
|   |   |-- default.pug
|   |-- _mixins <-- Mixin files - https://pugjs.org/language/mixins.html
|   |-- _site <-- Your pug files to site
|   |   |-- contact
|   |   |   |-- index.pug
|   |   |-- features
|   |   |   |-- index.pug
|   |   |-- index.pug
|   |-- assets
|   |   |-- images
|   |   |   |-- example.png
|   |   |-- javascripts
|   |   |   |-- example.js
|   |   |-- stylesheets
|   |   |   |-- example.css
|   |-- dist <-- Folder with compiled files
|   |-- .editorconfig <-- Indentation  styles - http://editorconfig.org
|   |-- .gitignore
|   |-- gulpfile.js
|   |-- package.json
```

## Launching

Compile files

```bash
gulp dist
```

Watch files

```bash
gulp watch
```

Preview compiled files

```bash
npm start
```

or

```bash
gulp serve
```

## Licence
[Licence](https://github.com/danielrohers/static-bootstrap/blob/master/LICENSE)
