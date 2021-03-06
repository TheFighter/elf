<img src="http://corysimmons.github.io/elf/img/elf.svg" height="120px">

#### Installation
- Copy and paste [elf.styl](elf.styl) to your project
- `@import 'path/to/elf'`

#### API

(view [elf.styl](elf.styl) for mixin and parameter descriptions)
- `debug(color = blue)`
- `column(ratio = 1, gutter = elf.gutter)`
- `cycle(item = 0, uncycle = 0, gutter = elf.gutter)`
- `offset(ratio = 0, column-or-span = column, gutter = elf.gutter)`
- `span(ratio = 1)`
- `shift(ratio = 1, column-or-span = column, gutter = elf.gutter)`
- `unshift()`
- `align(direction = both)`
- `cf()`

#### CodePens
- [Forkable](http://codepen.io/corysimmons/pen/dPParo)
- [Importable](http://codepen.io/corysimmons/pen/qEEgvW)
- [Collection of Examples](http://codepen.io/collection/nLKJkX/)

#### Browser Support
- General http://caniuse.com/#search=calc
- `align()` http://caniuse.com/#search=flexbox
