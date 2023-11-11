# Day 1

## Using percentages and avoiding heights

### Percentages vs Fixed Widths
By default, CSS is responsive.
Block level elements have a default width of 100%.
Adding a fixed width with pixels/other fixed units creates a problem at different screen sizes.

### Percentages on the child
CSS by default tries to make sure you don't lose any information.
When a child element uses fixed width, it will overflow in smaller screen sizes.
An element's percentage is always relative to it's immediate parent element.

### Why it's a good idea to avoid heights (when possible)
Similar to width, they cause issues on smaller screen sizes.
Without setting it, the content will automagically adjust to fit the screen.
If you want space, use padding with a relative unit (like rem/em).