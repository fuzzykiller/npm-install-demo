# npm-install-demo

Run `npm ci` and it will install everything that is in `package-lock.json`. The `node_modules` folder appears and no tracked files are changed.

Run `npm install` and it will install what’s in `package-lock.json` **minus** packages for different platforms. It will *also* update `package-lock.json` with new properties that did not exist with previous `npm` versions.