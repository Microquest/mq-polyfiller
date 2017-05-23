### Polyfiller

This repo wraps the [web-shim](http://afarkas.github.io/webshim/demos/index.html) v1.16.0 and
a [form polyfill](http://afarkas.github.io/webshim/demos/index.html#Forms-forms-ext) into one module that is
compatable with `webpack` and `npm`.

Note: `css` files are "required" by `index.js`, if you're not using a css loader, then you'll have a problem. And you'll need a file loader too.
