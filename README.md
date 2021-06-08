[![NPM version][npm-image]][npm-url] [![ci_cd][gh-action-image]][gh-action-url] [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]

# @kollavarsham/gulp-coveralls

[Gulp](https://github.com/gulpjs/gulp) plugin to submit code coverage to [Coveralls](http://coveralls.io). (Fork of the unmaintained [gulp-coveralls](https://github.com/markdalgleish/gulp-coveralls) - thank you, [@markdalgleish](https://github.com/markdalgleish))

## Usage

First, install `@kollavarsham/gulp-coveralls` as a dev dependency:

```bash
$ npm install --save-dev @kollavarsham/gulp-coveralls
```

Then, add it to your `gulpfile.js`:

```javascript
var coveralls = require('@kollavarsham/gulp-coveralls');

gulp.src('test/coverage/**/lcov.info')
  .pipe(coveralls());
```

## License

[MIT License](https://kollavarsham.org/LICENSE.txt) ([Original License](http://markdalgleish.mit-license.org))

[npm-url]: https://www.npmjs.com/package/@kollavarsham/gulp-coveralls
[npm-image]: https://img.shields.io/npm/v/@kollavarsham/gulp-coveralls.svg?style=flat-square

[gh-action-url]: https://github.com/kollavarsham/gulp-coveralls/actions/workflows/ci.yml
[gh-action-image]: https://github.com/kollavarsham/gulp-coveralls/actions/workflows/ci.yml/badge.svg

[coveralls-url]: https://coveralls.io/r/kollavarsham/gulp-coveralls
[coveralls-image]: https://img.shields.io/coveralls/kollavarsham/gulp-coveralls/main.svg?style=flat-square

[depstat-url]: https://david-dm.org/kollavarsham/gulp-coveralls
[depstat-image]: https://status.david-dm.org/gh/kollavarsham/gulp-coveralls.svg
