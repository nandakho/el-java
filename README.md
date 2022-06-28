# Electron - Java

Basically the same as [joeferner/node-java v0.12.2](https://github.com/joeferner/node-java)
But with applied fix from [Fixes utils.cpp to support electron #532](https://github.com/joeferner/node-java/pull/532) which is not merged yet to the main repo

## Installation

```bash
$ npm install el-java
```

## How to Build
Make sure you have the requirement modules:
[node-gyp](https://github.com/nodejs/node-gyp) and [electron-rebuild](https://github.com/electron/electron-rebuild) if not included

Run this in root directory (where your node_modules folder located):
```bash
.\node_modules\.bin\electron-rebuild.cmd -v [target-version]

//sample
.\node_modules\.bin\electron-rebuild.cmd -v 17.1.0
```
Then run this:
```bash
node .\node_modules\el-java\postInstall.js
```

Notes:
The command given above is in windows format.
For further instruction please read guides from the original repo here [joeferner/node-java v0.12.2](https://github.com/joeferner/node-java)