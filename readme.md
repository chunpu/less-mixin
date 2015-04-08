lesses
===

[![NPM version][npm-image]][npm-url]
[![Downloads][downloads-image]][downloads-url]
[![Dependency Status][david-image]][david-url]
[npm-image]: https://img.shields.io/npm/v/lesses.svg?style=flat-square
[npm-url]: https://npmjs.org/package/lesses
[downloads-image]: http://img.shields.io/npm/dm/lesses.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/lesses
[david-image]: http://img.shields.io/david/chunpu/lesses.svg?style=flat-square
[david-url]: https://david-dm.org/chunpu/lesses


Useful less mixin

Installation
---

```sh
npm i lesses
```

Usage
---

```less
@import "mixin/all";
```

Check the [example](http://chunpu.github.io/lesses/example/) page


Mixin
---

#### util

- `.clearfix`
- `.size(width[, height])`
- `.color(color[, background-color])`
- `.color-reverse(color[, background-color])`
- `.opacity(value)`
- `.border(color[, border-radius])` border always use `1px solid @color`

#### grid

TODO

#### gradient

- `.horizontal(start, end)` end default equals to start
- `.vertical(start, end)`
- `.reset-filter` only used to reset old ie

#### position

- `.center` horizontal center
- `.middle(height)` vertical middle, but it needs a height

#### text

- `.text-size(font-size[, line-height: 1])`
- `.text-line(line-height[, count: 1])` limit text lines
- `.text-left`
- `.text-right`
- `.text-center`

#### shadow

- `.shadow([value])`
- `.inset-shadow([value])`

> default value is `1px 2px 8px 1px rgba(0, 0, 0, 0.25)`, can use in most situation


#### transition

- `.transition([value])`

>  default value is `all 0.4s ease-in-out`

#### global var

- `ie-compat` default is true to support ie6+ as possible as it can


Handful class
---

- `.clearfix`
- `.left`
- `.right`
- `.block`
- `.inline`
- `.inline-block`
- `.text-left`
- `.text-right`
- `.text-center`
- `.hidden` display none and visibility hidden
- `.invisible` only visibility hidden
- `.circle`
- `.round`
- `.fixed`
- `.absolute`
- `.relative`

Notice
---

lesses do nothing about autoprefixer, only old ie and w3c

License
---

[![License][license-image]][license-url]

[license-image]: http://img.shields.io/npm/l/lesses.svg?style=flat-square
[license-url]: #
