# less-triangle
An easy mixin to create a triangle in CSS3 with LESS.

## Usage
```
    .triangle(@direction, @size, @color)
```
- @direction defines the direction: `up`, `down`, `left` or `right`.
- @size defines the size
- @color defines the color

## Example
```
.dropdown {
    &:after {
        .triangle(down, 5px, #fff);
    }
}
```