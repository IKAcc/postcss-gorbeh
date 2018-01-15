# postcss-gorbeh
[![](http://ikacc.ir/github-assets/gorbeh-header-v2.0.png)](https://gorbeh.ikacc.ir)
[Gorbeh Icons](https://github.com/IKAcc/Gorbeh) only in PostCSS

## Installation
```
$ npm i -D postcss-gorbeh
```

## Usage
### `Configuration`

Make sure having proper configs on **postcss.config.js** :
```js
module.exports = {
    plugins: [
      require('autoprefixer'),
      require('postcss-import')(),
      require('postcss-each')(),
      require('postcss-mixins')(),
      require('postcss-nested')(),
      require('postcss-at-rules-variables')(),
      require('postcss-for')(),
      require('postcss-custom-properties')(),
      require('postcss-simple-vars')(),
      require('postcss-short')(),
      require('postcss-calc')(),
      require('postcss-color-function')()
    ]
}
```

### `Import`
Import `../../node_modules/postcss-gorbeh/__vars.css` and `../../node_modules/postcss-gorbeh/gorbeh.css` sequentially to your main CSS file.

**note**: *don't forget to set up your fonts*
