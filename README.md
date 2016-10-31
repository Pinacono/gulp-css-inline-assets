# gulp-css-inline-assets
> Inline local and external assets (images, fonts) in a CSS file in the form of a data URI.

[![Build Status](https://travis-ci.org/Pinacono/gulp-css-inline-assets.svg?branch=master")](https://travis-ci.org/Pinacono/gulp-css-inline-assets)

## Install
```shell
$ npm install --save-dev gulp-css-inline-assets
```

## Usage

```js
```

```javascript
var gulp = require('gulp');
var inline = require('gulp-css-inline-assets');

gulp.task('default', function () {
    return gulp.src('src/app.css')
        .pipe(inline(options))
        .pipe(gulp.dest('dist'));
});
```

## Options

### ignoreErrors
Type: `boolean`

Determines if URLs with errors should be ignored.

## Credit
Based on [gulp-inline-assets](https://github.com/gustavohenke/gulp-inline-assets) module by [Gustavo Henke](https://github.com/gustavohenke) 

## License
MIT @ Pinacono