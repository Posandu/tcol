# Tcol
npm package to add colors to your terminal

## Installation
```shell
# npm
npm install tcol
# pnpm
pnpm install tcol
```

## Usage
```javascript
import { c } from "tcol";

console.log(c.Red("Hello"));
```

## Available methods

```javascript
Reset() // Reset all styles

Bright() // Bright text
Dim() // Dim text
Underscore() // Underlined text
Blink() // Blinking text
Reverse() // Reversed text
Hidden() // Hidden text     

Black() // Black text
Red() // Red text
Green() // Green text
Yellow() // Yellow text
Blue() // Blue text
Magenta() // Magenta text
Cyan() // Cyan text
White() // White text      

BgBlack() // Black background
BgRed() // Red background
BgGreen() // Green background
BgYellow() // Yellow background
BgBlue() // Blue background
BgMagenta() // Magenta background
BgCyan() // Cyan background
BgWhite() // White background
```
