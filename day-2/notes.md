# Day 2

## CSS em and rem

### em

1em generally = 16px.
A font size set with em is wrt parent.
Changes compound as you go down the hierarchy (i.e. grandparent affects parent which affects child).
This also affects nested elements themselves like lists/etc.

### rem

Designed to solve em's compounding problem.
rem = "root em", always relative to the root (`<html>` usually).

## Usage on elements other than fonts

- padding/margins
- widths/heights
- etc.

### em

Elements above (other than font-size) look at font-size of themselves as the reference, rather than their parent element.

Can be helpful with styling buttons/etc, so that adjustments to font size reflect accurately in these other properties as well.

### rem

Always looking at root, unlike em's.

Can be helpful for consistent spacing between buttons/etc.

## Other

There's an interesting pattern of adding variants to some base styling on top, i.e. `.btn` and `.btn--small`, `.btn-large`, etc. Elements that use the specialized version include both class names.
