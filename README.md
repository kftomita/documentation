PiLR Health Documentation
=========================

This repository contains the source files for generating the PiLR
Health documentation, found at <<URL_HERE>>. Versions of the docs can
also be built in PDF format. 

## Contribute

Simply fork the repository, clone it, make your modifications, and
submit a pull request.

## Build

If you'd like to build a local copy of the documentation, or see how
your changes will look on the live site, you can use the gulp build
system.

## gulp

Gulp (http://gulpjs.com/) is a streaming build system built on the
node.js platform. If you have node and npm installed already, just
follow these simple instructions to build a local copy of the PiLR
Health documentation.

One-time setup includes the following commands. 
````
$ git clone git@github.com:pilrhealth/documentation.git
$ cd documentation
$ npm install -g gulp
$ npm install
````

After the one-time setup, you have a few options to build the docs.

Build the docs locally

````
$ gulp
````

Build the docs, launch a local web server, and watch source files for
changes, at which point your browser will automatically refresh
(requires livereload browser extension) 

```` 
$ gulp server 

````

Build the docs, and push them to the gh-pages branch in the
documentation repository for publishing

````
$ gulp deploy
````



