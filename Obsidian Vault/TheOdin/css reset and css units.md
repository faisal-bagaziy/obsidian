## CSS reset
the whole idea of a CSS reset is to deal with styling inconsistencies across browsers.
how to preform it?
1. [The Meyer Reset](https://meyerweb.com/eric/tools/css/reset/)
2. [Normalize.css](http://nicolasgallagher.com/about-normalize-css/)

## CSS Units
many units in css 

### Absolute unit
- px
	- size of a pixel

## Relative units
- em
	- the element you are selecting parent is controlling the size
	- e.g. font-size: 4em --> 64px, this is with assuming the parent size is 16px (16 * 4 = 64)
- rem 
	- the element you are selecting root (`:root` or `html`) is controlling the size
	
==rule-of-thumb, prefer `rem`.== over em

## view port units
- vh
	- 1% of the viewport's height.
	- `10vh` will resolve to `10%` of the current viewport height.
	- or `48px` on a phone that is `480px`
- vw
	- 1% of the viewport's width.
	- `10vh` will resolve to `10%` of the current viewport width.
	- or `48px` on a phone that is `480px`
- vmin
	- A percentage of the viewport width or height, _whichever is smaller_.
- vmax
	- A percentage of the viewport width or height, _whichever is larger_.