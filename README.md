# canvas-bear

## Table of Contents
1. [What is Canvas](#what-is-canvas)
2. [How does Canvas work](#how-does-canvas-work)
3. [Drawing in Canvas](#drawing-in-canvas)

### What is Canvas
`Canvas` is an HTML element used to draw graphics, on the fly, via scripting. It is used to draw shapes, such as paths, circles, rectangles, and even complex imagery, such as photo and animation. Canvas can be used in tandem with other HTML elements, such as video and audio, to create a user experience that is more interactive and engaging than traditional webpages.

### How does Canvas work
Canvas is rendered as an HTML element and works within an HTML file. When the page is opened, the browser looks for the `<canvas>` element and parses it. It then creates a context, which is like a drawing surface on which developers draw vector graphics, raster graphics and text. The context is the child of the `<canvas>` element.\
JavaScript is then used to manipulate the canvas context. Developers write code to draw shapes, images, and text on the canvas. When a command is issued, the browser immediately draws the object on the canvas and continues to render the page.\
Canvas APIs are available for controlling the canvas element. This includes methods for setting the width and height, setting the style attributes, manipulating line width or type, drawing lines and shapes, and adding event handlers for user interactions.

### Drawing in Canvas
To draw shapes in Canvas, we use:
1. `rect()` - to draw a rectangle;
2. `arc()` - to draw a circle;
3. `moveTo()` and `lineTo()` - to draw a triangle;

**To draw a circle**\
*Canvas context arc()* is a method used in the HTML5 canvas element to draw an arc or circle. It takes 6 parameters: 
- x, y - determine the coordinates of the center point of the arc. 
- radius - defines the radius of the arc.
- startAngle, endAngle - determine the starting and ending angles of the arc in radians.
- anticlockwise (true or false) - a boolean that defines whether the arc should be drawn in a clockwise or counterclockwise direction.
