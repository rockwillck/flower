# Procedural Flower
A procedural flower. Binds to any HTML5 Canvas.

## Quickstart
Use `https://cdn.jsdelivr.net/gh/rockwillck/flower/flower.min.js` to load the script.

Then just use `bindFlower(document.getElementById("CANVAS-ID-REPLACE-THIS"))` in any JS script in your document.

You can also define the outline color (like we do on this webpage) as the second argument `STRING`.

## Technical Details
The renderer is a basic from-scratch 3D perspective renderer.

The generator begins with an arbitrary axis vector. It then starts generating petals in groups of four at different "levels" around this axis vector.
