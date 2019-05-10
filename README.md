[![Build Status](https://travis-ci.org/kaelzhang/caviar-plugin-define-runtime-env.svg?branch=master)](https://travis-ci.org/kaelzhang/caviar-plugin-define-runtime-env)
[![Coverage](https://codecov.io/gh/kaelzhang/caviar-plugin-define-runtime-env/branch/master/graph/badge.svg)](https://codecov.io/gh/kaelzhang/caviar-plugin-define-runtime-env)
<!-- optional appveyor tst
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/kaelzhang/caviar-plugin-define-runtime-env?branch=master&svg=true)](https://ci.appveyor.com/project/kaelzhang/caviar-plugin-define-runtime-env)
-->
<!-- optional npm version
[![NPM version](https://badge.fury.io/js/@caviar/plugin-define-runtime-env.svg)](http://badge.fury.io/js/@caviar/plugin-define-runtime-env)
-->
<!-- optional npm downloads
[![npm module downloads per month](http://img.shields.io/npm/dm/@caviar/plugin-define-runtime-env.svg)](https://www.npmjs.org/package/@caviar/plugin-define-runtime-env)
-->
<!-- optional dependency status
[![Dependency Status](https://david-dm.org/kaelzhang/caviar-plugin-define-runtime-env.svg)](https://david-dm.org/kaelzhang/caviar-plugin-define-runtime-env)
-->

# @caviar/plugin-define-runtime-env

Caviar plugin to allows you to define process.env variables which can be configured at runtime for both webpack and server

## Install

```sh
$ npm i @caviar/plugin-define-runtime-env
```

## Usage

```js
const RuntimeEnvPlugin = require('@caviar/plugin-define-runtime-env')

const plugin = new RuntimeEnvPlugin({

})

caviarConfig.plugins.push(plugin)
```

## License

[MIT](LICENSE)
