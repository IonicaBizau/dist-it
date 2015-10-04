## Documentation

### Usage

```sh
$ distify <input-file> <output-name>
```

This will create a file named `<output-name>` in the `dist` directory (if it's
not there, it will be created). Also, this will commit the rebuild changes.

### Example

```sh
$ distify lib/index.js my-lib.min.js
```

You will find `my-lib.min.js` in the `dist` directory.

### Dependencies

This tool depends on:

 - `browserify`
 - `namy`
 - `uglifyjs`

In case you don't have them installed, you will get specific errors. To install them, you can do:

```sh
$ npm i -g browserify namy uglifyjs
```
