# Day 9

## Reducing amount of HTML needed

container-row-column naming convention idea taken from Bootstrap.
could potentially share classes at the same level and reduce depth (i.e. container, row > col vs container > row > col).
having specific responsibilities for each CSS class with reusability in mind.

## Adding a hero image

Images get stretched to the height of other flex items at that level.
Can use `align-items: flex-start` and so on to avoid it.
Can also wrap the image in a div, since it'd be the div that stretches then, and not the image.
Can also add `align-self` to specific img element.

## Column widths and flexbox

A long text can try to push faster than the image scales, since the image has the room to shrink.
If there's no content, flex items want to shrink down to 0 width.
If both image and text have width: 100%, they're not 100%, but they're equal in size.
If the space is available, then the widths will be accurate (i.e. 30% and 30% <= 100%).

Could create gap w/ margin, but that's not ideal as the values are codependent yet all need to be individually modified.
Using justify-content (& align-items) is easier; space between/around/evenly are about where the extra spacing is distributed.
Justify content is on main axis, align items is on perpendicular axis.

## Ensuring the image is responsive

At smaller sizes, image can overflow/cause side scrolling.
Setting a max-width of 100% on images can make them easier to work with — they won't grow bigger than their original size.
I already have this in my reset.css, but good to know.
