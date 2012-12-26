html-strings
=====

Escape and unescape HTML-strings.

Usage
-----
Install module from npm:

`npm install html-strings`

Require and use:

```
var htmlStr = require('html-strings');
var escape = htmlStr.escape;
var unescape = htmlStr.unescape;

var someString = '<script type="text/javascript">&&</script>';

var escapedStr = escape(someString);
var unescapedStr = unescape(escapedStr);
```
