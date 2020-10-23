---
title: luma
tags: browser,beginner
---

Calculates the perceived luma of a RGB color.

- Uses the formula described [here](https://www.w3.org/TR/AERT/#color-contrast) for calculating a color perceived luminance.
- The range of all input parameters is [0, 255].
- The range of the resulting value is [0, 255].

```js
const luma = ([r, g, b]) => 0.299 * r + 0.587 * g + 0.114 * b;
```

```js
luma([36, 86, 12]); // 62.614
```
