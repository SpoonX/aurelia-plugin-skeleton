# aurelia-plugin-skeleton

[![Build Status](https://travis-ci.org/SpoonX/aurelia-plugin-skeleton.svg)](https://travis-ci.org/SpoonX/aurelia-plugin-skeleton)
[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg?maxAge=2592000?style=plastic)](https://gitter.im/SpoonX/Dev)

Starter package for aurelia-plugins following SpoonX conventions.

This aurelia-plugin starter repository uses [spoonx-tools](https://github.com/SpoonX/spoonx-tools) for all the gulp build tasks, karma setup and linting rules.

Features:
* jspm as package manager for the plugin
* babel6 and babel-dts-builder for transpilation 
* builds for all module loaders and creates a usuable basic d.ts file for typescript
* contains all the entries for jspm, webpack or aurelia-cli installation, for both, ESNext and Typescript
* starter readme.md (to come) with installation instructions 
* basic travis.yml
* `spoonx.js` contains the various build options
* `gulp help` lists the available tasks

## Prerequisites:

Global gulp and jspm installation

`npm i -g gulp jspm`

## Guideline:
(to come)

initially
* update package name in package.json, bower.json, typings.json
* update travis.yml and enable it in https://travis-ci.org/

after adding dependecies
* update spoonx.js
* prepare-release 
* fix/update package.json/bower.json
* update installation installations

 
