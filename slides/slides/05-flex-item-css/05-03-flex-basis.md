## Flex basis

```css
flex-basis: <length> | auto; /*default auto*/
```

- defines the initial length (along main axis) of the flex item, before free space is distributed (preflex length), as well as which 'part' of the length of the item is flexed.

![](images/rel-vs-abs-flex.svg)


Note:
- ```auto``` and ```0``` mean "look at my width or height property", or if none look at content.
- also defines which 'part' of the length of the element is flexed:
  - ```0```: similar to ```auto``` and the whole length is flexed
  - ```auto```:  the space around the content inside the flex item is flexed.
