# css-caption-side 0.0.7

Css module of single purpose classes for caption side

#### Stats

186 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-caption-side
```

#### With Git

```
git clone https://github.com/tachyons-css/css-caption-side
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-caption-side";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-caption-side">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   CAPTION SIDE
*/
.cst { caption-side: top; }
.csb { caption-side: bottom; }
.csi { caption-side: inherit; }
@media screen and (min-width: 48em) {
 .cst-ns { caption-side: top; }
 .csb-ns { caption-side: bottom; }
 .csi-ns { caption-side: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cst-m { caption-side: top; }
 .csb-m { caption-side: bottom; }
 .csi-m { caption-side: inherit; }
}
@media screen and (min-width: 64em) {
 .cst-l { caption-side: top; }
 .csb-l { caption-side: bottom; }
 .csi-l { caption-side: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
