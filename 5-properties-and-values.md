List of some common CSS properties and their possible values:

```css
/* Background Properties */
background-color: color | transparent;
background-image: url('path/to/image.jpg') | none;
background-repeat: repeat | repeat-x | repeat-y | no-repeat;
background-position: left top | center center | right bottom | x% y%;
background-size: auto | length | cover | contain;

/* Border Properties */
border-style: none | hidden | dotted | dashed | solid | double | groove | ridge | inset | outset;
border-width: length | thin | medium | thick;
border-color: color;
border-radius: length | percentage;

/* Box Model Properties */
margin: length | percentage | auto;
padding: length | percentage;
width: length | percentage | auto;
height: length | percentage | auto;
box-sizing: content-box | border-box;

/* Color and Background Properties */
color: color;
opacity: number (0 to 1);

/* Font Properties */
font-family: font1, font2, font3;
font-size: length | percentage | xx-small | x-small | small | medium | large | x-large | xx-large;
font-style: normal | italic | oblique;
font-weight: normal | bold | bolder | lighter | 100 - 900;

/* Text Properties */
text-align: left | right | center | justify;
text-decoration: none | underline | overline | line-through;
text-transform: none | capitalize | uppercase | lowercase;
line-height: normal | number | length | percentage;

/* Display and Positioning */  
display: block | inline | inline-block | flex | grid | none;
position: static | relative | absolute | fixed | sticky;
top, right, bottom, left: length | percentage | auto;
z-index: auto | integer;

/* Flexbox Properties */
flex-direction: row | row-reverse | column | column-reverse;  
flex-wrap: nowrap | wrap | wrap-reverse;
justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
align-items: flex-start | flex-end | center | baseline | stretch;

/* CSS Grid Properties */
grid-template-columns: track-size ... | auto | max-content | min-content | fit-content();
grid-template-rows: track-size ... | auto | max-content | min-content | fit-content();
grid-column: start-line / end-line | span number;
grid-row: start-line / end-line | span number;

/* Transition and Animation */
transition: property duration timing-function delay; 
animation: name duration timing-function delay iteration-count direction fill-mode play-state;

```

Some key points to remember:
- `length` values can be specified in pixels (`px`), ems (`em`), rems (`rem`), or other unit types
- `color` values can be keywords (`red`, `blue`, `green`, etc.), hexadecimal (`#ff0000`, `#00ff00`), RGB/RGBA (`rgb(255, 0, 0)`, `rgba(0, 0, 255, 0.5)`), or HSL/HSLA (`hsl(0, 100%, 50%)`, `hsla(240, 100%, 50%, 0.5)`)
- CSS shorthand properties like `margin`, `padding`, `border` allow setting multiple values at once
- Flexbox and Grid have many specific properties to control layout of child elements
