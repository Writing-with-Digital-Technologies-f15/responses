##Flexbox

##Flexbox Overview (Main Page)
Flexbox is a layout module that’s goal is to provide an efficient way to arrange elements on a page. These elements are in a container and it is possible to layout, align, and distribute space among the items in the container without knowing their size. The main purpose of the layout is allowing to container to best fill the space provided, whether it be on a computer page or mobile screen. A flex container can expand or shrink items to either fill available space or prevent overflow. Thus, Flexbox is responsive and its current uses reflect its responsive capabilities. 

Image of basic layout for flexible boxes
https://developer.mozilla.org/files/3739/flex_terms.png

##History of Flexbox
### History:
The first working flexbox draft came out July 23, 2009. There were three major revisions of the flexbox spec. The current version is stable and a W3C Candidate Recommendation. 

### Resolved Issues:
There are 19 resolved issues for flexbox:
- Issue #1: multiline flexbox is missing from current draft
- Issue #2: flex-direction property doesn't extend to more values needed for multiline flexbox
- Issue #3: flexbox has two ways to align in transverse direction - confusing and still incomplete. Try to make it consistent with Grid and/or Table.
- Issue #4: consider 'true-center' as an align option for flexbox
- Issue #5: page breaking behavior needs to be defined for flexbox
- Issue #6: 'inline-' display values work around limitations of 'display' property semantics. Separate properties for element placement and element content layout are long overdue.
- Issue #7: Is 'float' property on flex items ignored or honored and wrapped into anonymous block?
- Issue #8: would 'flex-order' be more intuitive if named 'flex-index'?
- Issue #9: multiline flexbox needs properties to control line stacking direction and line pack
- Issue #10: “flex item” definition needs precise rules on handling absolute-positioned children
- Issue #11: need exact definition for how anonymous flex items are created from inline content
- Issue #12: consider 'stack' as flexbox direction
- Issue #13: default values in flex() function should be the initial values
- Issue #14: what is the meaning of 'before' and 'after' in 'flex-align'
- Issue #15: Treatment of margins and paddings in flex algorithm (with flex 1 for 'auto') is incomplete: no flex() function, no min/max values. Would it make sense to allow flex() function on margins and paddings? And how about min/max?
- Issue #16: need a solid use case for treating “margin:auto” as “margin:flex(0px 1 0)” along main axis in flexbox
- Issue #17: what is effective min width/height of a flex item with specified widht/height?
- Issue #18: combination of margins and item-level flex-align is redundant and is not supporting common case where all items have same alignment.
- Issue #19: flex() has issues that 'flex' property wouldn't have

### Spec Syntax Property Mapping:
Comparison of module changes between 2009 spec and current state
https://wiki.csswg.org/spec/flexbox-2009-2011-spec-property-mapping
	
## Flexbox Terminology
### Definitions:
- Display- defines a flex container
- Order- controls the order in which flex items appear in flex container
- Flex-direction- defines the direction flex items are place in flex container (horizontally or vertically and in what order)
- Flex-grow- ability for flex item to grow if necessary 
- Flex-wrap- allows items to wrap as needed instead of fitting on one line
- Flex-shrink- allows items to shrink
- Flex-basis- defines default size of element before remaining space is distributed 
- Flex-flow- shorthand for **flex-direction** and **flex-wrap**
- Justify-content- defines alignment along the main-axis
- Flex- shorthand for **flex-grow**, **flex-basis**, and **flex-shrink**
- Align-self- allows default alignment to be overridden for individual flex items
- Align-items- defines default behavior for how items are laid out along the cross axis
- Align-content- aligns a flex container’s lines within where there is extra space in the cross-axis

### Naming Terminology
Suggestion- Rename “flexbox” to “flex container”
Suggestion- Rename “flexbox item” to “flex item” or “flex box”
Reason: Make consistent with CSS terminology elsewhere

## Grid vs. Flexbox
### Grid
How the page renders:
When using grid, the layout is defined in the container therefore the nav is rendered into the middle column as soon as it starts to arrive.

Arranging content:
Grid can only arrange the content in the order it is coded. 

### Flexbox
How the page renders:
When using the flexbox module, content dictates the layout of the webpage. This is because the container declares itself as a flexbox and the child elements declare how they will interact with each other inside the flexbox. When the page starts to load, the container begins receiving the first child, which is the main content. When the nav arrives, the content resizes to make room for it. 

Arranging content:
By default, Flexbox will arrange items in source order. However, the order property controls how they actually appear in the flex container. 

## Current Use
### Flexbox Grid: A grid system based on the flex display property
Options: Responsive, Fluid, Simple Syntax, Offsets, Auto Width, Nested Grids, Alignment, Reordering, and Reversing

### Problems solved by Flexbox:
- Better, simpler grid systems
- Input Add-ons
- Media Object
- Sticky Footer
- Vertical Centering
- Holy Grail Layout

## Outlook
### Browser Support
The newest spec is implemented in all 5 major desktop browsers: Chrome, Firefox, Safari, Internet Explorer 10+, and Opera 12.1+. There are no robust polyfills for the current spec, but you can mix old and new flexbox for maximum browser support. https://css-tricks.com/using-flexbox/

### Bugs & Workarounds
Example: minimum content sizing of flex items not honored 
Workaround: set flex-shrink to value of 0 instead of default 1 and a flex-basis value of auto
https://github.com/philipwalton/flexbugs

## Rationale/Structuring
I am planning on making the overview of Flexbox my home page of the site then having a menu to link to all the other section. The menu will go in the order I have written out and each heading will be what each page is about. The only thing I am thinking of combining is the outlook and current use. I also wanted to mention flexbox’s use with mobile apps so I may put that in the current use as well. Still have a lot of information to put in this is just what I have written for now. I will try to link all terminology back to my definition page when I mention it on the site.
