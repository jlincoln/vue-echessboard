# vue-echessboard

This is from a fork of vue-chessboard for Elephant Chess.

[![npm](https://img.shields.io/npm/v/vue-chessboard.svg) ![npm](https://img.shields.io/npm/dm/vue-chessboard.svg)](https://www.npmjs.com/package/vue-chessboard)
[![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

Chessboard vue component to load positions, create positions and see threats

- It uses [echess.js](https://github.com/jlincoln/echess.js) for chess movements and validations
- It uses echessground for chessboard UI  [echessground](https://github.com/jlincoln/echessground)

## Table of contents

# Installation

```
npm install --save vue-echessboard
```

## Default component import


```javascript
import {chessboard} from 'vue-echessboard'
import 'vue-chessboard/dist/vue-echessboard.css'
```

Then use it in your template
```html
    <echessboard/>
```

## Browser

```html
<div id="app">
  <echessboard></echessboard>
</div>

<link rel="stylesheet" href="vue-echessboard/dist/vue-echessboard.css"/>

<script src="vue.js"></script>
<script src="vue-chessboard/dist/vue-echessboard.browser.js"></script>

<script>
new Vue({
  el: '#app',
  components: {
    VueEchessboard
  }
});
</script>
```

# Examples

See vue-chessboard examples

## License

GPL-3.0
