# css-queries

Functional CSS for queries

## Filesize

| File | Size |
|------|------|
| `dist/queries.css` | 1 bytes |
| `dist/queries.min.css` | 0 bytes (20 Gzipped) |

## Install

```sh
npm install css-queries
```

## Usage

### Import

```css
@import "css-queries";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-queries/dist/queries.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-queries/dist/queries.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|


### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.example-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/queries.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/queries.css` — formatted
- `dist/queries.min.css` — minified

## License

MIT
