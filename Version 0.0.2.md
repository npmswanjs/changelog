# Version 0.0.2 is here!
Added a couple different new features. Clear function, new terminal coloring format, and some modifcations to built-in functions to Node.js!

There's multiple different modules now in swan, to import them all do this! (After installing the current version `npm i swan-kit@0.0.2` or, if first time installing for the file `npm i swan-kit`) 
```js
var { console, clear, log } = require("swan-kit");
// You can remove one, two, or all of them at any time!
```

## Clearing your terminal
A quick way of clearing your terminal no longer requires `console` to use, simply run
```js
clear();
```
and your all finished.

The module name is `clear`
```js
var { clear } = require("swan-kit");
```

You can also add anything to the beginning of the clear function by doing this instead:
```js
var anything = require("swan-kit");
// Adding "console" is useless as "console.clear();" is built in
anything.clear();
```

## Welcome the new color format
Instead of having a single color (Background or Foreground) you can now have a background, foreground, and an action all in one message!

The name of this module is `log`
```js
var { log } = require("swan-kit");
```

