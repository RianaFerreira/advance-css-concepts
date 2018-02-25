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

* Block Element Modifier css selectors
* 7 - 1 css framework pattern

* Simple grid system
* attribute selector
* :not pseudo-class
* calc() vs simple Sass operations

* background-clip with text
* transform multiple properties
* outline-offset with outline
* styling without hover
