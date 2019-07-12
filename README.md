# PropulsionJS-generator
PropulsionJS' application generator

[PropulsionJS'](https://www.npmjs.com/package/propulsionjs) project generator and bundle generator.

[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][downloads-url]
[![Linux Build][travis-image]][travis-url]

## Installation

```sh
$ npm install -g propulsionjs-generator
```

## Quick Start

Create the app:

```bash
$ express --view=hbs myApp && cd myApp
```

Install dependencies:

```bash
$ npm install
```

Start your Express.js app at `http://localhost:3000/`:

```bash
$ npm start
```

## Command Line Options

This generator can also be further configured with the following command line flags.

        --version        output the version number
    -e, --ejs            add ejs engine support
        --pug            add pug engine support
        --hbs            add handlebars engine support
    -H, --hogan          add hogan.js engine support
    -v, --view <engine>  add view <engine> supported by consolidate.js, see the README (defaults to nunjucks)
        --no-view        use static html instead of view engine
    -c, --css <engine>   add stylesheet <engine> support (less|stylus|compass|sass) (defaults to plain css)
        --git            add .gitignore
    -f, --force          force on non-empty directory
    -h, --help           output usage information

## Supported template engines

By default, PropulsionJS uses [consolidate.js](https://github.com/tj/consolidate.js/) because some template engines need code support to be used with `app.engine`. You can disable consolidate.js manually with template engines which are supported with express (like: dust|ejs|hbs|hjs|jade|pug|twig|vash).

See: [List (table) of supported template engines with consolidate.js](https://github.com/tj/consolidate.js#supported-template-engines)

## License

This project is a fork of [express-generator](https://github.com/expressjs/generator).

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/propulsionjs-generator.svg
[npm-url]: https://npmjs.org/package/propulsionjs-generator
[travis-image]: https://img.shields.io/travis/A-312/propulsionjs-generator/master.svg?label=linux
[travis-url]: https://travis-ci.org/A-312/propulsionjs-generator
[downloads-image]: https://img.shields.io/npm/dm/propulsionjs-generator.svg
[downloads-url]: https://npmjs.org/package/propulsionjs-generator
