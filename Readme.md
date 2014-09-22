
# grid

Common fixed/responsive grid core mixins inspired by Zurb Foundation

## Installation

Install with [component](https://github.com/component/component):

    $ component install chameleonui/grid

## API

```
grid-column(column-class, gutter-width)

grid-column-span(span-class, columns-count)

grid-column-offset(offset-class, columns-count)

grid-column-pull(pull-class, columns-count)

grid-column-push(push-class, columns-count)

grid-column-centered(column-class, centered-class)

grid-column-uncentered(column-class, uncentered-class)

grid-visibility(show-classes, hide-classes, postfix)

grid-visibility-hide(hide-classes, postfix)

grid-row(row-class, row-width, row-max-width, gutter-width)

grid-row-collapsed(row-class, column-class)

// Table like row - enables vertical centering
grid-row-tabular(row-tabular-class, column-class)

// Mixin to create different block-grids e.g. "tiles"
block-grid(per-row = false, gutter = 1, base-style = true)

grid-debug(bg-color, debug-class, row-class, column-class, tiles-class)
```

## Author(s)

[Edgedesign s.r.o.](http://www.edgedesing.cz) – [Tomas Kuba](https://github.com/tomaskuba), [Daniel Sitek](https://github.com/danielsitek)

## License

The MIT License (MIT)

Copyright © 2013 Edgedesign s.r.o.

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