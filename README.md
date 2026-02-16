# css-caption-side

Functional CSS for caption-side

## Filesize

| File | Size |
|------|------|
| `dist/caption-side.css` | 769 bytes |
| `dist/caption-side.min.css` | 593 bytes (153 Gzipped) |

## Install

```sh
npm install css-caption-side
```

## Usage

### Import

```css
@import "css-caption-side";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-caption-side/dist/caption-side.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-caption-side/dist/caption-side.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.caption-side-top` | `caption-side: top;` |
| `.caption-side-bottom` | `caption-side: bottom;` |
| `.caption-side-inherit` | `caption-side: inherit;` |
| `.caption-side-top-s` | `caption-side: top;` |
| `.caption-side-bottom-s` | `caption-side: bottom;` |
| `.caption-side-inherit-s` | `caption-side: inherit;` |
| `.caption-side-top-m` | `caption-side: top;` |
| `.caption-side-bottom-m` | `caption-side: bottom;` |
| `.caption-side-inherit-m` | `caption-side: inherit;` |
| `.caption-side-top-l` | `caption-side: top;` |
| `.caption-side-bottom-l` | `caption-side: bottom;` |
| `.caption-side-inherit-l` | `caption-side: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.caption-side-top-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/caption-side.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/caption-side.css` — formatted
- `dist/caption-side.min.css` — minified

## License

MIT
