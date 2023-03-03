# Introducting Version 0.0.1!
A quick release of colors inside of the Terminal. Much like chalk!

To begin install swan by running `npm i swan-kit` in your terminal, then go to your `index.js` and get started!
```js
var { color } = require("swan-kit");
```
This is how you include the function inside of your file, we also include a good amount of colors to choose from!
## Colors
The colors are the same for both Foreground (Text) and Background (Behind the text)
- black
- red
- green
- yellow
- blue
- purple
- cyan
- white
- gray

## Example
To get started with coloring your terminal you simply include `color.{color you want}` inside of the `console.log` function. Ex:
```js
console.log(color.green("Hello World!"));
```
Expect, when adding a background add "bg" to the beginning of the text. Ex:
```js
console.log(color.bgRed("Hello World!"));
```

> **Warning**
> Currently, your only able to use one color per `console.log`, saying you can't both have a text color and background in the same text.
