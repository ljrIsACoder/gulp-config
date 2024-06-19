# gulp-config

[![License][license-img]][license-url]
[![NPM Downloads][downloads-img]][downloads-url]
[![NPM Version][version-img]][version-url]
[![Dependency Status][dependency-img]][dependency-url]
[![Code Style][style-img]][style-url]

> Awesome node modules.

## Installation

```shell
$ npm install gulp-config

# or yarn
$ yarn add gulp-config
```

## Usage

<!-- TODO: Introduction of Usage -->

```javascript
const gulpConfig = require('gulp-config')
const result = gulpConfig('w')
// result => 'w@zce.me'
```

## API

<!-- TODO: Introduction of API -->

### gulpConfig(input, options?)

#### input

- Type: `string`
- Details: name string

#### options

##### host

- Type: `string`
- Details: host string
- Default: `'zce.me'`

## CLI Usage

<!-- TODO: Introduction of CLI -->

Use npx:

```shell
$ npx gulp-config <input> [options]
```

Globally install:

```shell
$ npm install gulp-config -g
# or yarn
$ yarn global add gulp-config
```

```shell
$ gulp-config --help
gulp-config/0.1.0

Usage:
  $ gulp-config <input>

Commands:
  <input>  Sample cli program

For more info, run any command with the `--help` flag:
  $ gulp-config --help

Options:
  --host <host>  Sample options
  -h, --help     Display this message
  -v, --version  Display version number

Examples:
  $ gulp-config w --host zce.me
```

## Related

- [zce/caz](https://github.com/zce/caz) - A simple yet powerful template-based Scaffolding tools.

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; [luojinrong](https://www.abc.com)



[license-img]: https://img.shields.io/github/license/zce/gulp-config
[license-url]: https://github.com/zce/gulp-config/blob/master/LICENSE
[downloads-img]: https://img.shields.io/npm/dm/gulp-config
[downloads-url]: https://npm.im/gulp-config
[version-img]: https://img.shields.io/npm/v/gulp-config
[version-url]: https://npm.im/gulp-config
[dependency-img]: https://img.shields.io/librariesio/github/zce/gulp-config
[dependency-url]: https://github.com/zce/gulp-config
[style-img]: https://img.shields.io/badge/code_style-standard-brightgreen
[style-url]: https://standardjs.com
