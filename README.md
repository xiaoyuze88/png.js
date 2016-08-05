
PNG.js
======

Forked from https://github.com/devongovett/png.js.

PNG.js is a PNG decoder fully written in JavaScript. It works in Node.js as
well as in (modern) browsers.

Modified a little bit so it can decode `CgBI` format png (Png file that is being [curshed](http://pmt.sourceforge.net/pngcrush/) by XCode in IOS.).

Also added support for Broswerify/Webpack by turning `zlib`(NodeJS) to [browserify-zlib](https://www.npmjs.com/package/browserify-zlib)  so that it can works fine both on NodeJS/Browser.

All apis are the same with the original project.

Make this repo to support my another project [isomorphic-pkg-reader](https://github.com/xiaoyuze88/isomorphic-pkg-reader) which can parse Apks/Ipas in both browser/NodeJS.

## REMOVED

This repository have been moved to (here)[https://github.com/TencentWSRD/png.js] and will be maintained by our team there, please check that out.

This repository here under my personal account won't be updated or accept any PR anymore.