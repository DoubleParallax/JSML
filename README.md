# JSML

![forthebadge](https://forthebadge.com/images/badges/designed-in-ms-paint.svg)
##### JSML is a NodeJS based Minecraft launcher, built with the capability and intention of modding.

## Features

* Launch any Minecraft version
* Provide the capability to interact with the JVM

## Automatic Installation

JSML requires [Node.js](https://nodejs.org/) to run.
Download the template files and run `npm run fresh` to get started.

```sh
$ git clone <insert git url>
$ cd jsml
$ npm run fresh
```

## Manual Installation

JSML requires the following dependencies to be installed:

| Dependency | Install Script |
| ---------- | -------------- |
| [Electron](https://electronjs.org/) | `npm i -D electron@latest` |
| [Electron Rebuild](https://www.npmjs.com/package/electron-rebuild) | `npm i -D electron-rebuild ` |
| [Java](https://www.npmjs.com/package/java) | `npm i -S java` |
| [Path](https://www.npmjs.com/package/path) | `npm i -S path` |
| [URL](https://www.npmjs.com/package/url) | `npm i -S url` |

After installing the required dependencies, run the following commands

| Command | Description |
| ------- | ----------- |
| `./node_modules/.bin/electron-rebuild` | Rebuild the native modules for use with Electron |
| `node ./node_modules/java/postInstall.js` | Fix the errors caused by `electron-rebuild` |

## Running

If you've downloaded the template files and installed the required dependencies, navigate to the root of your project and run the following command:
```sh
$ npm start
```