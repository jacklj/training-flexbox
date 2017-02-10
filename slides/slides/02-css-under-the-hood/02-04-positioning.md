$class: smallText$
## Positioning:

There are 3 positioning schemes:

1. *Normal flow*: Includes block formatting, inline formatting, table layouts and relative positioning
  ```css
    position: static | relative;
  ```

2. *Floats*: A box is first laid out according to the normal flow, then taken out of the flow and shifted to the left or right as far as possible (to edge of its parent or until it hits another floated element)
```css
  float: left | right;
```

3. *Absolute positioning (includes fixed)*: Takes the box out of the normal flow, and precisely specifying its location: it is explicitly offset with respect to its containing block. It is removed from the normal flow entirely: it has no impact on siblings, and doesn't flow around other boxes.
```CSS
  position: absolute | fixed;
```
