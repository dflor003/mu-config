# μ-config

This library provides a lightweight configuration abstraction focused on building nodejs microservices following [The 12-Factor App Principles](https://12factor.net/config) for configuration. Rather than using config files per environment (i.e. `dev.config`, `prod.config`, etc.), it's main use-case is for reading in a single configuration file that can be customized by providing environment variables.

## Features

> *NOTE:* This library is a work in progress. It is not feature complete yet.

This library provides the following features:

* All configuration in single file
* Type conversion for env var values
* Default values for each config value
* Nested configuration
* Little to no code
* Written in TypeScript

## Installation

Install via [npm](https://www.npmjs.com/):

```sh
$ npm install --save mu-config
```

Or install via [yarn](https://yarnpkg.com/en/):

```sh
$ yarn add mu-config
```

## Usage

_TODO_

## Contributing

_TODO_

## License

mu-config is [MIT Licensed](./LICENSE).
