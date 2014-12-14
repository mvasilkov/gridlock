# Gridlock

A tiny, simple and dynamic grid system.

## Introduction

Before you run away at the sight of yet another grid system, Gridlock was designed to be diffrent because it puts you as it's focus point and as a result uses plain english class names and a simple structure to create the grids that you want. If you don't like something, change it to your liking and everything will continue to work at the change of a property.

```html
<div class="row">
	<div class="column-5">This is a column.</div>
	<div class="column-5">This is a column.</div>
</div>
```

> Providing your class names add up to that of the total columns, you can mix and match any amount of columns and widths you like.

## Properties

| Name                 | Description                              | Default |
| -------------------- | ---------------------------------------- | ------- |
| gridlock-columns     | The number of columns to use in the grid | 12      |
| gridlock-row-name    | The name to use for rows                 | row     |
| gridlock-column-name | The name to use for columns              | column  |
| gridlock-puller-name | The name to use for pullers              | push    |
| gridlock-pusher-name | The name to use for pullers              | pull    |
| gridlock-gutter      | The gutter between columns               | .5em    |

## Compatibility

| Browser           | Supported                         |
| ----------------- | --------------------------------- |
| Chrome            | yes                               |
| Firefox           | yes                               |
| Internet Explorer | partial (_from version 8_)        |
| Opera             | yes                               |

## License

The MIT License (MIT)
Copyright (c) 2014 Nathaniel Blackburn
    
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.