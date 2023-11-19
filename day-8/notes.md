# Day 8

## Introduction to flexbox

By default, flex items want to be as small as possible.
Can give them widths and then flex will try to respect that, unless it absolutely can't — then you get overflow.
`display: flex` and `flex-direction: row | column` covered

## Adding space between columns

### Method 1: gap property

Use `gap` for space between columns.
[caniuse](https://caniuse.com) can help determine feature usability (it is now).

### Method 2: .col + .col selector

`+` is a CSS combinator.
Selecting adjacent sibling of a column (i.e. one before it), if it has one.
Use it with `margin-left` to get the same effect.
