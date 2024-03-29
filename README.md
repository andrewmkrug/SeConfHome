# SeConfHome

[![license][license-image]][license-url] [![Build Status](https://travis-ci.org/andrewmkrug/SeConfHome.svg?branch=master)](https://travis-ci.org/andrewmkrug/SeConfHome) [![Dependency Status][dependencyci-image]][dependencyci-url]

> 

## Prerequisites

To install this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll -v 3.6.2`
2. [NodeJS](http://nodejs.org) - use the installer.

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**Development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc.

```shell
$ npm run start
```

useless

**Deploy mode**

You can easily deploy your site build with the command
```shell
$ npm run deploy
```

## Tests

If you want to run the tests on your local machine please install `gem install html-proofer`. And then run the tests using
```shell
$ htmlproofer ./_site
```

[license-image]: https://img.shields.io/badge/license-ISC-blue.svg
[license-url]: https://github.com/andrewmkrug/SeConfHome/blob/master/LICENSE
[travis-image]: https://travis-ci.org/andrewmkrug/SeConfHome.svg?branch=master
[travis-url]: https://travis-ci.org/andrewmkrug/SeConfHome
[dependencyci-image]: https://dependencyci.com/github/andrewmkrug/SeConfHome/badge
[dependencyci-url]: https://dependencyci.com/github/andrewmkrug/SeConfHome
