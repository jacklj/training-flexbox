$class: smallText$

## Flex tuple

Each length of a flex item is represented by a *flex tuple*: a 5-tuple of information about a flexible length, containing:

  1. Minimum size
  2. Maximum size
  3. Preferred size - defaults to 0, can be set to a different value with flex-basis: (or 3rd argument of flex:)
  4. Positive flexibility
  5. Negative flexibility


Note:
the minimum and maximum sizes are calculated depending on the type of length:
- margin and padding: Set the minimum size to 0 and the maximum size to infinity.
- Set the minimum size to the value of the ‘min-width’ or ‘min-height’, as appropriate
- borders: inflexible
