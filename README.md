# CSS Colors

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Package Control](https://packagecontrol.herokuapp.com/downloads/CSS%20Colors.svg?style=flat-square)](https://packagecontrol.io/packages/CSS-Colors)
[![GitHub release](https://img.shields.io/github/release/idleberg/CSS-Colors.svg?style=flat-square)](https://github.com/idleberg/CSS-Colors/releases)
[![Travis](https://img.shields.io/travis/idleberg/CSS-Colors.svg?style=flat-square)](https://travis-ci.org/idleberg/CSS-Colors)

CSS color snippets for Sublime Text, supporting a variety of color systems such as W3C, Pantone, ANPA, HKS or RAL

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P on OS X`)
3. Select *CSS Colors* and press `Enter`

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/CSS-Colors`

## Usage

The snippets are available for the scopes `source.css`, `source.less`, `source.sass` and `source.scss`

Use any of the following triggers:

Prefix       | Value | Representation | Colour System
-------------|-------|----------------|--------------
anpaHex      | code  | Hexdecimal     | American Newspaper Publishers Association (1)
anpaHSL      | code  | HSL            | American Newspaper Publishers Association (0)
anpaHSLa     | code  | HSLa           | American Newspaper Publishers Association (0)
anpaRGB      | code  | RGB            | American Newspaper Publishers Association (0)
anpaRGBa     | code  | RGBa           | American Newspaper Publishers Association (0)
anpaRGBa     | code  | RGBa           | American Newspaper Publishers Association (0)
hkskHex      | code  | Hexadecimal    | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system) (2)
hkskRGB      | code  | RGB            | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system) (2)
hkskRGBa     | code  | RGBa           | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system) (2)
hksnHex      | code  | Hexadecimal    | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system) (2)
hksnRGB      | code  | RGB            | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system) (2)
hksnRGBa     | code  | RGBa           | [HKS Color System](http://en.wikipedia.org/wiki/HKS_(colour_system) (2)
pantoneHex   | code  | Hexadecimal    | [Pantone Matching System](https://www.pantone.com) (3)
pantoneHSL   | code  | HSL            | [Pantone Matching System](https://www.pantone.com) (0)
pantoneHSLa  | code  | HSLa           | [Pantone Matching System](https://www.pantone.com) (0)
pantoneRGB   | code  | RGB            | [Pantone Matching System](https://www.pantone.com) (3)
pantoneRGBa  | code  | RGBa           | [Pantone Matching System](https://www.pantone.com) (3)
ralHex       | code  | Hexadecimal    | [RAL Color System](http://en.wikipedia.org/wiki/RAL_colour_standard) (4)
ralHSL       | code  | HSL            | [RAL Color System](http://en.wikipedia.org/wiki/RAL_colour_standard) (0)
ralHSLa      | code  | HSLa           | [RAL Color System](http://en.wikipedia.org/wiki/RAL_colour_standard) (0)
ralRGB       | code  | RGB            | [RAL Color System](http://en.wikipedia.org/wiki/RAL_colour_standard) (4)
ralRGBa      | code  | RGBa           | [RAL Color System](http://en.wikipedia.org/wiki/RAL_colour_standard) (4)
w3cHex       | name  | Hexadecimal    | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
w3cHSL       | name  | HSL            | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
w3cHSLa      | name  | HSLa           | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
w3cRGB       | name  | RGB            | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)
w3cRGBa      | name  | RGBa           | [CSS Color Module Level 3](http://www.w3.org/TR/css3-color)

*(0) converted from Hex values*  
*(1) sampled from Adobe Photoshop*  
*(2) sampled from [Online HKS Converter](http://hks2.com/)*  
*(3) sampled from [umsiko.co.za](http://www.umsiko.co.za/links/color.html/)*  
*(4) sampled from [ralcolor.com](http://www.ralcolor.com/)*  

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