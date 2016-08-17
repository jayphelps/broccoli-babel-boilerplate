# [NO LONGER MAINTAINED] Use at your own risk or for reference.

# broccoli-babel-boilerplate

A boilerplate, using Broccoli, to author JavaScript libraries in ES6/ES7++ but transpile and distribute using Babel.js

* The root module name is taken from the `package.json` name property (so you'll want to change that first!)
* Put your source files in `src/`, your tests in `test/unit/`
* Files named `index.js` will take their parent directory's name as their AMD module name
  * e.g. `src/foo/index.js => project-name/foo`
* You can optionally provide a `src/index.html` that'll be output to `dist/` as well

```bash
npm run build;
# builds to dist/
npm start;
# builds to tmp/, starts a webserver, and watches files for changes to rebuild
```
