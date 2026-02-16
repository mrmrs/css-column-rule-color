# css-column-rule-color

Functional CSS for column-rule-color

## Filesize

| File | Size |
|------|------|
| `dist/column-rule-color.css` | 777 bytes |
| `dist/column-rule-color.min.css` | 601 bytes (168 Gzipped) |

## Install

```sh
npm install css-column-rule-color
```

## Usage

### Import

```css
@import "css-column-rule-color";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-column-rule-color/dist/column-rule-color.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-column-rule-color/dist/column-rule-color.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.crc-drkgry` | `column-rule-color: $dark-gray;` |
| `.crc-transparent` | `column-rule-color: transparent;` |
| `.crc-i` | `column-rule-color: inherit;` |
| `.crc-drkgry-s` | `column-rule-color: $dark-gray;` |
| `.crc-transparent-s` | `column-rule-color: transparent;` |
| `.crc-i-s` | `column-rule-color: inherit;` |
| `.crc-drkgry-m` | `column-rule-color: $dark-gray;` |
| `.crc-transparent-m` | `column-rule-color: transparent;` |
| `.crc-i-m` | `column-rule-color: inherit;` |
| `.crc-drkgry-l` | `column-rule-color: $dark-gray;` |
| `.crc-transparent-l` | `column-rule-color: transparent;` |
| `.crc-i-l` | `column-rule-color: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.crc-drkgry-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/column-rule-color.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/column-rule-color.css` — formatted
- `dist/column-rule-color.min.css` — minified

## License

MIT
