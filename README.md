# standard-packages

### List of packages that use [`standard`](https://github.com/feross/standard)

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

## Usage

```js
var packages = require('standard-packages')
packages.forEach(function (pkg) {
  console.log('package name', pkg.name)
  console.log('repo url', pkg.repo)
})
```

## Contribute

To update the data in `standard.json` run:

```bash
npm run fetch
npm start
```
:warning:**Warning:** `npm run fetch` will download and save a ~300MB file called `alldata.json`. 
## License

MIT. Copyright (c) [Feross Aboukhadijeh](http://feross.org).
