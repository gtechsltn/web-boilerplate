# Simple, fast and lightweight web boilerplate serving as my basis for developing webapps and websites

https://github.com/vicegold/web-boilerplate

https://github.com/codinglabs/web-boilerplate

https://github.com/gtechsltn/web-boilerplate

![Ingredients of the web boilerplate](https://mzdr.github.io/web-boilerplate/ingredients.png)

Simple, fast and lightweight web boilerplate serving as my basis for developing webapps and websites. By default you'll get the following features:

- Bundling of JavaScript by [browserify](http://browserify.org/)
- Support of [ECMAScript 2015](http://www.ecma-international.org/publications/standards/Ecma-262.htm) (ES6) features which are transpiled by [Babel](https://babeljs.io/) (See [src/js](src/js) for a simple example)
- Configurable linting with [ESLint](http://eslint.org/docs/user-guide/configuring)
- Automatic SVG Sprite generation based on sub-directories
- Optimization of images on the fly (supports JPG, PNG, GIF and SVG) with [imagemin](https://github.com/imagemin/imagemin)
- Version string based cache busting
- Desktop notifications when errors occur
- [Sass](http://sass-lang.com/) Style Sheets with PostCSS [autoprefixing](https://github.com/postcss/autoprefixer)
- Time-saving synchronised browser testing with [Browsersync](https://www.browsersync.io/)

Pretty cool, huh?

---

**But Basti …**

I know, it's pretty custom and mostly written to fit my personal flavor, but on the other hand it's based on lots of years working in web development agencies, as a freelancer with other freelancers or just on personal projects. So it's pretty much the latest shit, at least I try my best to keep up with the community and I think you really could love it like I do.

I used to work with Grunt and Gulp, also with Bower/Bundler and other package managers. That's one of the reasons why I came up with this. I just wanted to get rid of those managers as [NPM](https://www.npmjs.com/)/[Node.js](https://nodejs.org/) solely is just fine enough to handle this kind of work. Also articles like “[Why we should stop using Grunt & Gulp](http://blog.keithcirkel.co.uk/why-we-should-stop-using-grunt/)” or “[Why I Left Gulp and Grunt for npm Scripts](https://medium.com/@housecor/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8)” inspired me to do this.

Anyway, I had a fun time creating this. If you have any suggestions, problems or feedback. Feel free to [create issues](https://github.com/mzdr/web-boilerplate/issues/new), [pull request](https://github.com/mzdr/web-boilerplate/pulls) or get in touch with me via my twitter account ([@mrprein](https://twitter.com/mrprein)).


---

Setup is dead simple. Just run:

1. `npm install`

2. `node build`

within the terminal of your choice. That's it!

Don't forget to check out the [project.json](project.json) for customizing the whole build process!

---

Right now there are three basic tasks `build`, `clean`, `watch`. You can run them like this:

`node build`  
`node clean`  
`node watch`  

If you only need to build specific things, you might want to run one of these:

`node build fonts`  
`node build html`  
`node build images`  
`node build scripts`  
`node build sprites`  
`node build styles`  

The same goes for watching:

`node watch fonts`  
`node watch html`  
`node watch images`  
`node watch scripts`  
`node watch sprites`  
`node watch styles`  

Also all `watch` tasks have a `--sync` option to enable [Browsersync](https://www.browsersync.io/).

---

Third party frameworks/libraries enabled by default: [normalize.css](https://necolas.github.io/normalize.css/), [picturefill](https://scottjehl.github.io/picturefill/).

v1.1.0
