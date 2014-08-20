# gulp-[cssnext](https://github.com/putaindecode/cssnext)

[![Build Status](http://img.shields.io/travis/putaindecode/gulp-cssnext.svg)](https://travis-ci.org/putaindecode/gulp-cssnext)
[![NPM version](http://img.shields.io/npm/v/gulp-cssnext.svg)](https://www.npmjs.org/package/gulp-cssnext)

> Use tomorrow's CSS syntax, today. Via Gulp.

*Issues with the output should be reported on [cssnext issue tracker](https://github.com/putaindecode/cssnext/issues).*

## Install

    $ npm install gulp-cssnext

## Usage

```js
var cssnext = require("gulp-cssnext")

gulp.task("stylesheets", function() {
  gulp.src("src/stylesheets/index.css")
    .pipe(cssnext({
        compress : true
    }))
    .pipe(gulp.dest("./dist/stylesheets"))
});
```

### Options

Options are directly passed to cssnext, so checkout [cssnext options](https://github.com/putaindecode/cssnext#nodejs-options) directly

---

## Contributing

Work on a branch, install dev-dependencies, respect coding style & run tests before submitting a bug fix or a feature.

    $ git clone https://github.com/putaindecode/gulp-cssnext.git
    $ git checkout -b patch-1
    $ npm install
    $ npm test

## [Changelog](CHANGELOG.md)

## [License](LICENSE)