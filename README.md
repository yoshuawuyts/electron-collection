# electron-collection [![stability][0]][1]
[![npm version][2]][3] [![build status][4]][5]
[![downloads][8]][9] [![js-standard-style][10]][11]

Set of helper modules to build Electron applications.

## API

### `debug([opts])`
Adds useful debug features to your Electron app. See:
[electron-debug](https://www.npmjs.com/package/electron-debug).

### `firstRun([opts])`
Check if it's the first time the process is run. See:
[first-run](https://github.com/sindresorhus/first-run).

### `fixPath()`
Fix the $PATH on macOS when run from a GUI app. See:
[fix-path](https://github.com/sindresorhus/fix-path).

### `isDev()`
Check if Electron is running in Development. See:
[electron-is-dev](https://github.com/sindresorhus/electron-is-dev).

### `move()`
Automatically move Electron apps to the Applications directory. See:
[electron-lets-move](https://github.com/tommoor/electron-lets-move).

### `rootPath`
Determine the root path to your project. Read-only value. See:
[app-root-path](https://github.com/inxilpro/node-app-root-path).

### `shouldStart = squirrelStartup()`
Default [Squirrel.Windows](https://github.com/Squirrel/Squirrel.Windows) event
handler for your Electron apps. Returns a boolean. See:
[electron-squirrel-startup](https://github.com/mongodb-js/electron-squirrel-startup).

## License
[MIT](https://tldrlegal.com/license/mit-license)

[0]: https://img.shields.io/badge/stability-experimental-orange.svg?style=flat-square
[1]: https://nodejs.org/api/documentation.html#documentation_stability_index
[2]: https://img.shields.io/npm/v/electron-collection.svg?style=flat-square
[3]: https://npmjs.org/package/electron-collection
[4]: https://img.shields.io/travis/yoshuawuyts/electron-collection/master.svg?style=flat-square
[5]: https://travis-ci.org/yoshuawuyts/electron-collection
[6]: https://img.shields.io/codecov/c/github/yoshuawuyts/electron-collection/master.svg?style=flat-square
[7]: https://codecov.io/github/yoshuawuyts/electron-collection
[8]: http://img.shields.io/npm/dm/electron-collection.svg?style=flat-square
[9]: https://npmjs.org/package/electron-collection
[10]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[11]: https://github.com/feross/standard
