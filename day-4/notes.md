# Day 4

## CSS Viewport Units: vh, vw, vmin, vmax

### Layouts

vh = viewport height, vw = viewport width.
100vX = 100% of viewport dimension, always matches size of that dimension.
using vX sometimes causes spilling on smaller screens, if the content within is longer.
percentage is always based on parent element, whereas vX is based on viewport.

vmax = max(vh, vw)
vmin = min(vh, vw)

can also use these on padding to combine with height/width.

### Fonts

can also use them for responsive fonts.
doesn't work so well for paragraph text, since it's smaller to begin with and not usually bold.
vw usually is more drastic in it's changes than vh in fonts.
vmin can be helpful for titles, but still sort of risky.
