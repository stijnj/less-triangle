# less-triangle
An easy mixin to create a triangle in CSS3 with LESS.

## Usage
```
    .triangle(@direction, @size, @color)
    .triangle(@direction, @width, @height, @color)
```
- @direction defines the direction: `up`, `down`, `left` or `right`.
- @size defines the size of triangle
- @width defines the width of triangle
- @height defines the height of triangle
- @color defines the color

## Example
```
.dropdown {
    &:after {
        .triangle(down, 3em, 5px, #fff);
    }
}
```