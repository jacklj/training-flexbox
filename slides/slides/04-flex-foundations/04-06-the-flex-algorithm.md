$class: smallText$

## The flex algorithm

CSS resolves a flexible length into a definite length by:
1. Collect all lengths, flexible or inflexible, along a single axis, that will share the space.
2. Sum the *preflex* sizes of the lengths.
3. If there is positive available space, then the space is split up among all the flexible lengths with positive flexibility, according to their grow factors, to make the sum equal to the available length.
4. If there is negative available space, then all the flexible lengths with negative flexibility shrink in proportion to their shrink factors, to make the sum equal to the available length.


Note:
1. E.g. for a horizontal flex container, the flex items’ left and right margins, left and right borders, left and right paddings, and widths, share the width. Each flex item’s vertical margins, borders, padding and height individually share the height of the flex container.
2. *The preflex size of an inflexible length is just the length itself. The preflex size of a flexble length is its preferred size.*
