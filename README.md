# grunt-coffeelintr [![Build Status](https://travis-ci.com/Sibiraj-S/grunt-coffeelintr.svg?branch=master)](https://travis-ci.com/Sibiraj-S/grunt-coffeelintr)

> A Grunt Plugin for Coffeelint

## Getting Started

This plugin requires Grunt `>= 1.0.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-coffeelintr --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-coffeelintr');
```

## The "coffeelintr" task

### Overview

In your project's Gruntfile, add a section named `coffeelintr` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  coffeelintr: {
    options: {
      congigFile: 'coffeelint.json',
      force: false
    },
    your_target: {
      files: {
        src: ['**/*.coffee']
      }
    }
  }
});
```
