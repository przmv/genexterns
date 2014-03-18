genexterns
==========

Generate Closure Compiler externs output from the JavaScript source file(s)

## Dependencies

1. [`phantomjs`](http://phantomjs.org/)
2. [`js-beautify`](https://github.com/einars/js-beautify) (Optional)

## Usage

```
$ genexterns path/to/some/library.js | js-beautify -f - > path/to/closure/externs.js
```

## More information

* [Declaring Externs](https://developers.google.com/closure/compiler/docs/api-tutorial3#externs)
