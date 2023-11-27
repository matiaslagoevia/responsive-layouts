# Day 16

## What breakpoints to use?

### How to decide what breakpoints to use?

When does my layout start to fail and I need to fix it?
Figure it out by looking at it and deciding where that is.
Some areas may be ok, but other ones not — try not to have different breakpoints close enough, to make CSS easier to maintain.
Be aware of what devices have what screen size, because there may be none/not too many as to be picking a worse breakpoint than could be possible.

### Correct way to do CSS breakpoints article

https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/

TLDR:

- 0-**600px** (phone)
- 600-**900px** (tablet portrait)
- 900-**1200px** (tablet landscape)
- 1200-**1800px** (desktop)
- 1800px-beyond (large desktop)
