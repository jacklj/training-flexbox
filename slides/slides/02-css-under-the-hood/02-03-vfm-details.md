## The Visual Formatting Model

The visual formatting model comprises of two stages:

1. Box Generation
2. Positioning


Note:
1. Box Generation
    - visual medium, e.g. web page, is made up of lots of 2D boxes, layered up along a 3rd dimension (z-index is the CSS property used to control the 3D layering order)
    - box generation takes each HTML element and generates one or more boxes. The type of element specifies how many boxes are generated; most elements generate one, e.g. <li> generates 2, one for the content and one for the bullet point icon
    - there are different types of boxes - the display property of the element defines its box's type
    - boxes have both an outer type (how it interacts with its parent and siblings) and an inner type (how it interacts with its children). These behaviours are independent - this will be useful later.
2. Positioning
    - All the boxes are then laid out on a page, taking into account:
        1. the chosen *Positioning Scheme*
        2. the box's dimensions and type,
        3. the relationships between elements in the document tree
        4. external info like viewport size
