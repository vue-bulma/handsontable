# Handsontable

Handsontable component is based on [Handsontable](https://github.com/handsontable/handsontable) for Vue

## Installation

```
$ npm install vue-handsontable
```

## Examples

```vue
<template>
  <handsontable :data="data" :settings="{}"></handsontable>
</template>

<script>
import Handsontable from 'vue-Handsontable'

export default {
  components: {
    Handsontable
  },

  data () {
    return {
      data: [
        ['', 'Kia', 'Nissan', 'Toyota', 'Honda'],
        ['2008', 10, 11, 12, 13],
        ['2009', 20, 11, 14, 13],
        ['2010', 30, 15, 12, 13]
      ]
    }
  }
}
</script>
```

## Badges

![](https://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/status-stable-green.svg)

---

> [fundon.me](https://fundon.me) &nbsp;&middot;&nbsp;
> GitHub [@fundon](https://github.com/fundon) &nbsp;&middot;&nbsp;
> Twitter [@_fundon](https://twitter.com/_fundon)

