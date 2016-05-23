# Node Url Shortener

> A modern, minimalist, and lightweight URL shortener using [Node.js](http://nodejs.org) and [Redis](http://redis.io).

[![Build Status](https://travis-ci.org/dotzero/node-url-shortener.svg?branch=master)](https://travis-ci.org/dotzero/node-url-shortener)
[![GitHub tag](https://img.shields.io/github/tag/dotzero/node-url-shortener.svg?maxAge=2592000)](https://github.com/dotzero/node-url-shortener)
[![Dependency Status](https://david-dm.org/dotzero/node-url-shortener.svg)](https://david-dm.org/dotzero/node-url-shortener)

## Using

* [Express 4](http://expressjs.com/)
* [Redis](http://redis.io)

## Quick Start

```bash
$ git clone https://github.com/dotzero/node-url-shortener nus
$ cd nus
$ npm install
$ node app
```

## Command Line Options

```bash
$ node app -h

Usage: app [options]

Options:
  -u, --url     Application URL               [default: "http://127.0.0.1:3000"]
  -p, --port    Port number for the Express application          [default: 3000]
  --redis-host  Redis Server hostname                     [default: "localhost"]
  --redis-port  Redis Server port number                         [default: 6379]
  --redis-pass  Redis Server password                           [default: false]
  -h, --help    Show help                                              [boolean]
```

## Installation on production

```bash
$ git clone https://github.com/dotzero/node-url-shortener nus
$ cd nus
$ npm install --production
$ NODE_ENV=production node app --url "http://example.com"
```

## Tests

To run the test suite, first install the dependencies, then run `npm test`:

```bash
$ npm install
$ npm test
```

## License

Released under [the MIT license](LICENSE.md)
