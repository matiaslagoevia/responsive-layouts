# Day 12

## Getting fancy with navigations

### Sending to other side

Without modifying HTML, can add a class and use `margin-left: auto` to send all the way to the right, and viceversa.

With modifying HTML, using separate lists and flex/margins/etc. If 1+ list, look into aria-roles/etc for how to specify primary vs secondary, etc.

.col + .col trick of highlighting ones w/ a previous one as before useful too, tho bc gap is widely supported now it should be less frequent.

### More improvements to navigation

Using logo outside the navbar since for people on screenreaders there'd be two "Home's" otherwise.

Main axis vs cross axis coming up again, `justify-content` vs `align-items`/`align-self`.

Can either set width to 100% to have the remaining space take up the left and keep the sign up/sign in buttons on the right.

Can also do `flex-grow` (default 0) and `flex-shrink` (default 1) — why everything wants to be as small as it can with flexbox (by default).

### Centering things the easy way

Can select the one supposed to go in the middle and `margin: 0 auto`.
Not covered, but could also use `space-evenly` with axis alignments?
