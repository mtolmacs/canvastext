# CanvasText - Rendering TTF font files on HTML Canvas

NOTE: This is an educational project and not production ready!

### Current features:
* Renders only simple glyphs, replaces compound glyphs with the .notdef glyph
* Renders font bounding boxes
* Renders contour points with implied points, with off-curve points are colored red, on-curve points blue
* Draws glyph contours with bezier curves (pixel-perfect vector outline)

# Production-ready alterantives
* [fonteditor-core @ npmjs.com](https://www.npmjs.com/package/fonteditor-core)
* [harfbuzz compiled to WebAssembly](https://www.npmjs.com/package/harfbuzzjs)
* [@konghayao/opentype.js](https://www.npmjs.com/package/@konghayao/opentype.js)

### Development Tools
* [Font metrics on the web with points and contours](https://fontdrop.info)
* [Apple's official TTF docs](https://developer.apple.com/fonts/TrueType-Reference-Manual/)
