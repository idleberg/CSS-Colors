# CSS Colors [![Build Status](https://secure.travis-ci.org/idleberg/CSS-Colors.png)](http://travis-ci.org/idleberg/CSS-Colors)

CSS color completions for Sublime Text, supporting a variety of color systems such as W3C, Pantone, ANPA, HKS or RAL

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P on OS X`)
3. Select *CSS Colors* and press `Enter`}

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/CSS-Colors`

## Usage

The completions are available for the scopes `source.css`, `source.less`, `source.sass` and `source.scss`

Use any of the following triggers:

Prefix       | Value | Representation | Colour System
-------------|-------|----------------|--------------
ANPA→Hex     | code  | Hexdecimal     | American Newspaper Publishers Association
ANPA→HSL     | code  | HSL            | American Newspaper Publishers Association
ANPA→HSLa    | code  | HSLa           | American Newspaper Publishers Association
ANPA→RGB     | code  | RGB            | American Newspaper Publishers Association
ANPA→RGBa    | code  | RGBa           | American Newspaper Publishers Association
ANPA→RGBa    | code  | RGBa           | American Newspaper Publishers Association
HKS K→Hex    | code  | Hexadecimal    | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system))
HKS K→RGB    | code  | RGB            | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system))
HKS K→RGBa   | code  | RGBa           | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system))
HKS N→Hex    | code  | Hexadecimal    | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system))
HKS N→RGB    | code  | RGB            | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system))
HKS N→RGBa   | code  | RGBa           | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system))
Pantone→Hex  | code  | Hexadecimal    | [Pantone Matching System](https://www.pantone.com)
Pantone→HSL  | code  | HSL            | [Pantone Matching System](https://www.pantone.com)
Pantone→HSLa | code  | HSLa           | [Pantone Matching System](https://www.pantone.com)
Pantone→RGB  | code  | RGB            | [Pantone Matching System](https://www.pantone.com)
Pantone→RGBa | code  | RGBa           | [Pantone Matching System](https://www.pantone.com)
RAL→Hex      | code  | Hexadecimal    | [RAL System](http://www.ralcolor.com/)
RAL→HSL      | code  | HSL            | [RAL System](http://www.ralcolor.com/)
RAL→HSLa     | code  | HSLa           | [RAL System](http://www.ralcolor.com/)
RAL→RGB      | code  | RGB            | [RAL System](http://www.ralcolor.com/)
RAL→RGBa     | code  | RGBa           | [RAL System](http://www.ralcolor.com/)
W3C→Hex      | name  | Hexadecimal    | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
W3C→HSL      | name  | HSL            | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
W3C→HSLa     | name  | HSLa           | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
W3C→RGB      | name  | RGB            | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
W3C→RGBa     | name  | RGBa           | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)

### Examples:

- `W3C→RGB:lime` → rgb(0, 255, 0)
- `Pantone→Hex:313C` → #0092c7
- `RAL→RGBa:3001` → rgba(165, 32, 25, 1.0)

Think of the `→` as a visual separator only. When typing a trigger, you should leave it out!


## License

The MIT License (MIT)

Copyright (c) 2014 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/CSS-Colors) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`