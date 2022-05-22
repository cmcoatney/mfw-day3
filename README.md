# Flexbox Playground

## Flexbox Properties

Parent (Flex Container)

    display: flex | inline-flex;

    flex-direction: row | row-reverse | column | column-reverse;

    flex-wrap: wrap | nowrap | wrap-reverse;

    flex-flow (shorthand for flex-direction and flex-wrap)

    justify-content (main axis): flex-start | flex-end | center | space-between | space-around | space-evenly;

    align-items (cross axis - adjust to individual sizes): flex-start | flex-end | center | baseline | stretch;

    align-content (cross axis - adjust to largest item): flex-start | flex-end | center | stretch | space-between | space-around;

Children (Flex Items)

    order: <integer>;

    flex-grow: <number>;

    flex-shrink: <number>;

    flex-basis: <length> | auto;

    flex: shorthand for grow, shrink, and basis (default:  0 1 auto)

    align-self: overrides alignment set on parent



## Trying it out

1. display: flex: Gets everything on one line
2. flex-direction: orders in source order or ( reverse ) all the items on main axis.
3. flex-wrap: should overflow wrap to the next line?
4. flex-flow: shorthand for flex-direction and flex-wrap
5. justify-content: Controls how items on main axis should be spaced
6. align-items: cross-axis spacing