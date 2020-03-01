## read12
### JAvascript
#### Charts
* Create charts
to create charf <canvas>
before pull request the project Look over contributing guidelines.
* canvas is an HTML element which can be used to draw graphics via scripting with JavaScript this can be used to draw graphs, combine photos, or create simple animations.
unlike the < img> element, the < canvas> element requires the closing tag canvas.
* Drawing shapes with canvas
Now that we have set up our canvas environment, we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.
##### Colors
Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle:Sets the style used when filling shapes, and strokeStyle: Sets the style for shapes’ outlines.
##### Drawing text
Drawing text The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth]): Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
##### Drawing shapes with canvas
The grid canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin.