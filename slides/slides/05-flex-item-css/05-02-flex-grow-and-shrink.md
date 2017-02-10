## Flex grow and shrink
```css
flex-grow: <positive number> /*default: 0*/
flex-shrink: <positive number> /*default: 1*/
```

- Specifies how much the flex item will grow (the flex grow factor), or shrink (the flex shrink factor), relative to its sibling flex items, when the flex container’s positive or negative free space is distributed among them.


Note:
- unitless value
- e.g. a flex item with flex shrink factor 3 will shrink three times faster than a sibling flex item with shrink factor 1. Both might have the same minimum length.

Demo:
- add flex-grow: 1 to one flex item (default: 0)
- add to a few others, also other values (including non-integer)
  - e.g. a single item having flex-grow: 0.5 means it takes half the available positive space
