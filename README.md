# [gulp](http://gulpjs.com)-kissy-xtemplate [![Build Status](https://travis-ci.org/daxingplay/gulp-kissy-xtemplate.svg?branch=master)](https://travis-ci.org/daxingplay/gulp-kissy-xtemplate)

> Lorem ipsum


## Install

```bash
$ npm install --save-dev gulp-kissy-xtemplate
```


## Usage

```js
var gulp = require('gulp');
var kissyXtemplate = require('gulp-kissy-xtemplate');

gulp.task('default', function () {
	return gulp.src('src/app.ext')
		.pipe(kissyXtemplate())
		.pipe(gulp.dest('dist'));
});
```


## API

### kissyXtemplate(options)

## Options

```
gulp.task('default', function () {
	return gulp.src('src/app.ext')
		.pipe(kissyXtemplate({
			version: '1.5.0', // config your KISSY version
			inputCharset: 'gbk', // your tpl src charset
			outputCharset: 'gbk' // compiled charset
		}))
		.pipe(gulp.dest('dist'));
});
```

### Current Supported Versions

* 1.4.0
* 1.4.1
* 1.4.2
* 1.5.0
* 5.0.0-alpha.1
* 5.0.0-alpha.2
* 5.0.0-alpha.10
* kg-4.1.4

Lorem ipsum.


## License

MIT © [daxingplay](https://github.com/daxingplay)
