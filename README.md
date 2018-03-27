micro-require
===================

**micro-require** is a small require library to be used in libraries and pure js projects.

----------
Usage
-------------

Use the `window.require` word to import one or more modules/files:

```javascript
(function() {
  // one file
  require('myFile.js', function (err) {
    if (err) return;
    // rest of the code..
  });

  // multiple files
  require(['myFile1.js', 'myFile.js2'], function (err) {
    if (err) return;
    // rest of the code..
  });
})();
```

Inspiration
-------------
- [**Why web modules?** from require.js](http://requirejs.org/docs/why.html)
- [**JavaScript Patterns** - Build Better Applications with Coding and Design Patterns](http://shop.oreilly.com/product/9780596806767.do)
