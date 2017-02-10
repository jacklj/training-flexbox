$class: smallText$
## RN Flex item properties

```flex: <integer>```

- When flex is a positive number, it makes the component flexible and it will be sized proportional to its flex value. So a component with flex set to 2 will take twice the space as a component with flex set to 1.

- When flex is 0, the component is sized according to width and height and it is inflexible.

- When flex is -1, the component is normally sized according width and height. However, if there's not enough space, the component will shrink to its minWidth and minHeight.

Note:
flexGrow, flexShrink, and flexBasis work the same as in CSS. **** how do they interact with flex??
