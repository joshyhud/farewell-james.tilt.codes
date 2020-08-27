# front-end-boilerplate
Minimal front end boilerplate, kept up to date via Node package manager.

Will play nice(st) with the latest versions of modern browsers:-
* IE11
* Edge
* Firefox
* Chromium
* Safari

## Get started
* git clone https://git.jamesmonk.me/James/front-end-boilerplate.git
* cd front-end-boilerplate
* npm install --save-dev
* gulp
* Start building!

## Features

### Javascript
* Fully vanilla, no frameworks here!
* ES6 Javascript scripts process (linting, uglify, compression, concat) with backwards compatibility thanks to Babel
* Critical path JS inline in document footer (increased load speed, less http round trips)
* Lazyloading of non-critical JS files (loadJS, loads after initial paint)

### CSS
* Minimal modern CSS reset (no huge bloat for those extremely app specifc rare edge cases, as with Normalize.css)
* SASS styles process (linting, compression, autoprefixing, concat, loading of modules)
* Critical path CSS inline in document head (increased load speed, less http round trips)
* Lazyloading of non-critical CSS files (loadCSS, loads after initial paint)

### Assets
* Mustache HTML templating process (featuring partials)
* Imagemin IMG process (image optimisation and SVG minification)
* SVG icon sprite (generated inline from SVG assets)
* Favicon creation from supplied PNG, base64 encoded inline to remove additional HTTP request
* BrowserSync process (auto reload on file save/update)

## To do
* Look into automatically generating critical path/page CSS solution rather than having to manually control, although this has it's benefits(!).

## Extending
Recommended plugins/things for extending functionality IF/WHERE needed, only (let's keep this lean, OK?!):-

* Swiper - for carousels
