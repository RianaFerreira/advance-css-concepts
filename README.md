# Advanced CSS concepts

## Setup
```
$ cd project folder
$ npm init
$ npm install sass-node --save-dev  # compile scss to css
$ npm install live-server -g        # auto reload app when css changes
$ touch main.css
```

## Run the app

```
  $ live-server
```
Continuously compile scss to css in another tab.
```
$ npm run compile:sass
```

Open the app in the browser with url `http://127.0.0.1:8080/`

## Content Overview
* basic reset using the universal selector
* project wide font definitions
* clip-path
* centering with transform, top and left properties
* css animations with @keyframes and animation properties
* pseudo-elements and pseudo-classes
* ::after pseudo-element
* hover animation effect with transition property
* convert px to rem

### Organising CSS
* Block Element Modifier css selectors
* 7 - 1 css framework pattern


### Simple grid system
* attribute selector
* :not pseudo-class
* calc() vs simple Sass operations

### Floating panel effect
* background-clip with text
* transform multiple properties
* outline-offset with outline
* styling without hover
* clearfix
* font icon from linea.io
* direct child selector

### Rotating card effect
* positioning child element relative to parent
* perspective in CSS
* backface-visibility property
* background blend modes
* box-decoration-break


### Wrap text around shapes
* shape-outside
* float
* image filters

### Background video
* <video> element
* object-fit property

### Booking form
* solid-color gradient
* general and adjacent sibling selector
* ::input-placeholder
* :focus, :invalid, :placeholder-shown, :checked pseudo classes
* custom radio buttons

### Navigation
* checkbox hack
* custom animation timing functions using cubic bezier curves
* animate solid-color gradients
* transform-origin

### CSS popup
* target pseudo-class
* display: table-cell for boxes with equal height
* text formatting - columns and hyphenate words

### Responsive design
* mobile first vs desktop first
* breakpoints based on groups of devices
* use sass mixin for media queries
* @content and @iff sass directives
* Chrome responsive design DevTool

### Responsive images
* img srcset attribute and source elements with density descriptors
* picture element for art direction
* write media queries in HTML

### References
Jonas Schmedtmann resources http://codingheroes.io/resources/
Video background images https://coverr.co/
Images https://unsplash.com/
Lorem ipsum
https://hipsum.co/
http://star-wars-ipsum.herokuapp.com/
SVG icons https://css-tricks.com/pretty-good-svg-icon-system/
CSS special characters https://css-tricks.com/snippets/html/glyphs/
Clip-path https://bennettfeely.com/clippy/
Easing functions
http://easings.net/#easeInOutBack
Cubic-bezier http://cubic-bezier.com/#.17,.67,.83,.67
Test responsive layout https://sizzy.co/
