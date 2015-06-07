# Angular app generator [![Build Status](https://secure.travis-ci.org/albatrosary/generator-angular-eggs.svg?branch=master)](http://travis-ci.org/albatrosary/generator-angular-eggs)

This generator are using Angular1, NewRouter and Express on Node.js. Angular we have emphasized the development life cycle.It supports the next thing for that.

* Unit Test
* End-to-End Test
* Documentation
* Coverage
* Metric


## Usage

Install: `npm install -g generator-angular-eggs`

Make a new directory and `cd` into it:
```
mkdir [app-name] && cd $_
```
This [app-name] is used as ng-app="[app-name]"

Run `yo angular-eggs`:
```
yo angular-eggs
```

## Generators

Available generators:

- angular-eggs:components [name]
- angular-eggs:service [name]
- angular-eggs:directive [name]
- angular-eggs:server [name]

## Tasks

- grunt serve
- grunt serve:dist
- grunt build
- grunt test
- grunt test:watch
- grunt test:coverage
- grunt e2e
- grunt doc
- grunt metric
- grunt metric:test

## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
