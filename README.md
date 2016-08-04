# [Meshki](http://borderliner.ir/meshki)
Meshki is a simple, black-colored, responsive boilerplate to kickstart any responsive project.

Check out <http://borderliner.ir/meshki> for samples and details.

## Getting started

There are a couple ways to download Meshki:
- [Download the zip](https://github.com/Borderliner/Meshki/archive/v0.1.0-alpha.zip) or [the tar.gz](https://github.com/Borderliner/Meshki/archive/v0.1.0-alpha.tar.gz)
- Clone the repo: `git clone https://github.com/Borderliner/Meshki.git` (Note: this is under active development, so if you're looking for stable and safe, use the zipped download)

### How to compile
You need node.js to minify the source .css files and produce an output. Head over to [nodejs.org](https://nodejs.org/en/) and download a version for your system, or download it from your package manager. Next install `Grunt` with this command:

`npm install -g grunt-cli`

Then `cd` into the root folder of the project, and run the command `npm run compile`. This will produce a file named "meshki.min.css" into the "/dist" folder.

### What's in the download?

The download includes Meshki's CSS, Normalize CSS as a reset, a sample favicon, and an index.html as a starting point.

```
Meshki/
├── index.html
├── css/
│   ├── normalize.min.css
│   └── meshki.css
└── images/
    └── favicon.ico

```

### Why it's awesome

Meshki is lightweight and simple. It styles only raw HTML elements (with a few exceptions) and provides a responsive grid. Nothing more.
- Around 400 lines of CSS unminified and with comments
- It's a starting point, not a UI framework
- No compiling or installing...just vanilla CSS


## Browser support

- Chrome latest
- Firefox latest
- Opera latest
- Safari latest
- IE latest

The above list is non-exhaustive. Meshki works perfectly with almost all older versions of the browsers above, though IE certainly has large degradation prior to IE9.


## License

All parts of Meshki are free to use and abuse under the [open-source MIT license](https://github.com/Borderliner/Meshki/blob/master/LICENSE.md).

## Acknowledgement

Meshki started by Mohammad Reza Hajianpour as a fork of [Skeleton](https://github.com/dhg/Skeleton).
Skeleton was created by [Dave Gamache](https://twitter.com/dhg) for a better web.
