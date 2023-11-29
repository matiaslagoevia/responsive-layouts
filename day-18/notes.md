# Day 18

## Challenge Solution & Mobile-First

Comparing to my solution.

### Writing the HTML

He creates a `<section>` rather than a `<header>`.
He also uses BEM (i.e. `.intro__text` rather than `.intro p`).
He's also using containers within the sections, like I am.
He's also using the row -> column structure, like I am; but he's having `col` be a separate div rather than applying it on the p tag directly.
He's putting the image within a col div, rather than by itself.

### Writing Mobile First CSS

My solution has squished images and overflowing text on the header.
Apply solution changes on new CSS file and keep the old one around to toggle between them.
Approach of starting up with too much space/too big and then cutting down can be helpful.
Wasn't using reset CSS, so apply all those border box, image, etc. changes.
Use max-width to avoid stretching on larger sizes while still being able to shrink if necessary.
I didn't notice the headers used serif fonts and not sans-serif :O.
Starting with typography first can also be a good idea.
Bit confused as to why he's going with pixel values for padding/etc.
Line heights being a good tip for large headings/etc.
Not worrying about layouts yet has pictures be at the bottom on mobile which is great, and I think BEM will also be a good idea for me to learn too.
Ok, he fixes the pixel stuff later so don't worry about that.
Just by focusing on typography, background colors, and spacing, the mobile layout is done.
320px is usually the smallest screen size that's common.

### Adding media queries for larger screens

Usually a good idea to stop lines from going all the way across as it makes them harder to read; can use some sort of column layout to avoid this.
Can use max-width within container to stop it from getting way too long, but columns can still help.
If after max-width it's still too long, can use media query after seeing where the layout breaks.
Just using flex makes them be columns, and can use width of 100% or flex-grow of 1 to have them line up the pictures and paragraphs.
Separation of layout within media queries is helpful as well (w/ some font size changes/etc).

### A look at min-height

Not an issue to set these heights, as expected, so my bit of that solution was ok.
lorem snippet also good to know, can do `lorem50` for 50 words, etc.
Using align-items center on a flex, like I did too, to center it.
