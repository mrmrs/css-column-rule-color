# CSS COLUMN RULE COLOR

  Mobile-first classes for css-column-rule-color.
  Set the desired css-column-rule-color on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-column-rule-color
```
View on [npm](https://www.npmjs.org/package/css-column-rule-color)


## File Size

841B column-rule-color.css
841B column-rule-color.scss 
1minified and gzipped

## The Code
```
.crc-drkgry {       column-rule-color: $dark-gray; }
.crc-transparent {  column-rule-color: transparent; }
.crc-i {            column-rule-color: inherit; }

@media screen and (min-width: 48em) {
  .crc-drkgry-ns {       column-rule-color: $dark-gray; }
  .crc-transparent-ns {  column-rule-color: transparent; }
  .crc-i-ns {            column-rule-color: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .crc-drkgry-m {       column-rule-color: $dark-gray; }
  .crc-transparent-m {  column-rule-color: transparent; }
  .crc-i-m {            column-rule-color: inherit; }

}

@media screen and (min-width: 64em)  {
  .crc-drkgry-l {       column-rule-color: $dark-gray; }
  .crc-transparent-l {  column-rule-color: transparent; }
  .crc-i-l {            column-rule-color: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

