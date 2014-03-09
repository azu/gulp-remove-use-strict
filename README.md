# gulp-remove-use-strict

[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]


> remove-use-strict plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-remove-use-strict` as a development dependency:

```shell
npm install --save-dev gulp-remove-use-strict
```

Then, add it to your `gulpfile.js`:

```javascript
var removeUseStrict = require("gulp-remove-use-strict");

gulp.src("./src/*.js")
	.pipe(removeUseStrict())
	.pipe(gulp.dest("./dist"));
```

## API

### remove-use-strict(options)


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[npm-url]: https://npmjs.org/package/gulp-remove-use-strict
[npm-image]: https://badge.fury.io/js/gulp-remove-use-strict.png

[travis-url]: http://travis-ci.org/azu/gulp-remove-use-strict
[travis-image]: https://secure.travis-ci.org/azu/gulp-remove-use-strict.png?branch=master

[coveralls-url]: https://coveralls.io/r/azu/gulp-remove-use-strict
[coveralls-image]: https://coveralls.io/repos/azu/gulp-remove-use-strict/badge.png

[depstat-url]: https://david-dm.org/azu/gulp-remove-use-strict
[depstat-image]: https://david-dm.org/azu/gulp-remove-use-strict.png
