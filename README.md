# CSS CAPTION SIDE

  Mobile-first classes for css-caption-side.
  Set the desired css-caption-side on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-caption-side
```
View on [npm](https://www.npmjs.org/package/css-caption-side)


## File Size

571B caption-side.css
447B caption-side.min.css 
160B minified and gzipped

## The Code
```
.cst { caption-side: top; }
.csb { caption-side: bottom; }
.csi { caption-side: inherit; }

@media screen and (min-width: 48em) {
  .cst-ns { caption-side: top; }
  .csb-ns { caption-side: bottom; }
  .csi-ns { caption-side: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .cst-m { caption-side: top; }
  .csb-m { caption-side: bottom; }
  .csi-m { caption-side: inherit; }
}

@media screen and (min-width: 64em)  {
  .cst-l { caption-side: top; }
  .csb-l { caption-side: bottom; }
  .csi-l { caption-side: inherit; }
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

