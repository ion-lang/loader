# ion-loader

A webpack loader for the ion language.

## Install

```bash
npm install ion-loader --save
```

## Usage

Right on the require:

```js
var file = require("ion!./file.ion")
```

Webpack config (better):

```js
{
  module: {
    loaders: [
      { test: /\.ion$/, loader: 'ion' }
    ]
  }
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)
