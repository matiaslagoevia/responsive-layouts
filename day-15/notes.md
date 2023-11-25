# Day 15

## Intro to media queries

### Media query basics

Let us add new styles/override old ones that let us target specific conditions.
`@media media-type () {}`
If no media-type specified, all types are assumed.
Within the (), that's heights/widths, orientations, hover/not, etc.
One we'll focus the most is width: min-width or max-width.
It's possible to combine both with `and`, but not focusing on it for now.
Desktop-first is having the media queries specialize behavior for mobile, and the "default" on desktop. Mobile-first is the opposite.
Order matters, even for media queries — a min of 600 after a min of 800 will cause the min of 800 to never win. Media queries have to be after the default styles otherwise the default will win too.

### Adding one to our layout

Have the row elements be a block level element.
For a number of elements that had their widths set on the desktop sizes, set them back to 100%, and add some widths.
Did desktop-first design, could use mobile-first in some of the frontend mentor challenges.
