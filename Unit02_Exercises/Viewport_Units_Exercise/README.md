# Viewport Units

These are my notes and exercises from Javier Usobiaga Ferrer's course on "Web Layout with CSS Grid, Flexbox and other Modern Techniques" on Domestika. 

## Table of contents

- [Overview](#overview)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

**Exercise:** 
- Change the viewport units in 2-1 viewport-units.css for the following:
  - The height of header_block1 and header_block2
  - The viewport width of h1


### Built with

- CSS

### What I learned

**vw**
Unit relative to the width of the viewport (typically the browser window,
or an iframe). 100vw equals 100% of the width of the viewport. It is
recommended to avoid applying a 100vw to an element (or combination of elements)
because the lateral position of the scroll bar depending on the operating system could
cause some horizontal scrolling on the page.

**vh**
Unit relative to the height of the viewport. 100vh is equal to 100% of the height of the
viewport.

**vmin and vmax**
Units equivalent to vw (width) or vh (height) of the viewport, depending on whichever is the smaller dimension of the two (in the case of vmin) or whichever is the larger dimension of
both (in the case of vmax). They are useful units on many occasions, for
example, when we want a content image to look as large as possible
with respect to the viewport, but without being cut off by one of its two
dimensions.

## Author

- Notes from Domestika Course by Javier Usobiaga Ferrer (Google Translated by me)


