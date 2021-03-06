# Advanced CSS concepts

## Setup
```
$ cd project folder
$ npm init
$ npm install sass-node --save-dev      # compile scss to css
$ npm install live-server -g            # auto reload app when css changes
$ npm install concat --save-dev         # concatenate multiple files
$ npm install autoprefixer --save-dev   # auto prefix advanced css properties
$ npm install postcss-cli --save-dev    # required by the autoprefixer lib
$ npm install npm-run-all --save-dev    # run all the build process steps
$ touch main.css
```

## Run the app
Reference the package.json file for the scripts.


Single script to start the development server and continuously compile sass to css.
```
$ npm run start
```

Alternatively run the individual scripts in seperate CLI tabs.

Run command in a seperate CLI tab.
Start the development server.
```
$ live-server
```

Run command in a seperate CLI tab.
Watch for changes to sass files and automatically compile to css.
```
$ npm run watch:sass
```

## CSS Build process individual steps
Reference the package.json file for the script tasks. The build process produces css/style.css which is referenced by the running server.

```
$ npm run compile:sass
$ npm run concat:css
$ npm run prefix:css
$ npm run compress:css
```

## CSS all inclusive build command
```
$ npm run build:css
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

### Responsive images in HTML
* img srcset attribute and source elements with density descriptors
* picture element for art direction
* write media queries in HTML

### Resolution switching with HTML
* img srcset attribute, width descriptors and size attribute

### Responsive images in CSS
* resolution media queries to target high-res screens with 2x
* combining multiple conditions in media queries

### Browser compatibility
* caniuse.com for modern css properties in production
* graceful degradation with @supports
* backdrop-filter


### App behaviour customisations
* Custom content highlighting style,
* Only apply media queries to screens and not print.
* Use alternative css media query to identify touch devices. Mobile devices with larger screens are confused with desktops, the only difference is that touch devices don't support hover.

### Best practices
* JS is needed for navigation option selected to display the correct section.
* JS is needed to close popup when clicking anywhere outside the popup view.
* use more variables
* add comments to code

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
