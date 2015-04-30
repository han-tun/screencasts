# Introduction to D3

Streaming live at [this Google Hangout](https://plus.google.com/hangouts/_/g2adpgfm4tkrdvwq3qgcbanmfaa).

[Slides](https://docs.google.com/presentation/d/1QI8ztO-2baoW8SToaPTlSu24w8dvqvrEMD-xVpI3LmE/pub?start=false&loop=false&delayms=3000)

This tutorial covers fundamental [D3.js](http://d3js.org/) concepts from the ground up, and introduces basic visualizations.

 * technologies leveraged by D3
   * HTML
   * SVG
   * CSS
 * fundamental D3 concepts
   * selections
   * scales
   * axes
   * graphical elements
     * rectangles
     * circles
     * lines
 * visualizations
   * bar chart
   * scatter plot
   * line chart

## Examples

Check out the [Example Viewer](http://curran.github.io/screencasts/introToD3/examples/viewer/#/). Use left and right arrow keys to navigate.

 * [Example 1](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot01) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot01) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot01/index.html)) - Hello HTML
 * [Example 2](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot02) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot02) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot02/index.html)) - Hello SVG
 * [Example 3](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot03) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot03) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot03/index.html)) - Default SVG size
 * [Example 4](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot04) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot04) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot04/index.html)) - Specifying SVG dimensions
 * [Example 5](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot05) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot05) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot05/index.html)) - Adding (x, y) coordinates
 * [Example 6](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot06) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot06) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot06/index.html)) - Adding color
 * [Example 7](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot07) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot07) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot07/index.html)) - rgb() color syntax
 * [Example 8](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot08) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot08) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot08/index.html)) - Transparency with rgba()
 * [Example 9](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot09) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot09) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot09/index.html)) - Hex color codes
 * [Example 10](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot10) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot10) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot10/index.html)) - Drawing outlines with stroke
 * [Example 11](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot11) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot11) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot11/index.html)) - Controlling stroke width
 * [Example 12](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot12) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot12) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot12/index.html)) - Using fill=none
 * [Example 13](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot13) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot13) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot13/index.html)) - Drawing a circle
 * [Example 14](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot14) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot14) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot14/index.html)) - cx and cy
 * [Example 15](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot15) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot15) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot15/index.html)) - stroke and width
 * [Example 16](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot16) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot16) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot16/index.html)) - drawing a line
 * [Example 17](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot17) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot17) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot17/index.html)) - drawing several lines
 * [Example 18](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot18) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot18) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot18/index.html)) - using SVG paths
 * [Example 19](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot19) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot19) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot19/index.html)) - drawing several lines with a path
 * [Example 20](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot20) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot20) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot20/index.html)) - filling a path
 * [Example 21](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot21) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot21) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot21/index.html)) - closing a path
 * [Example 22](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot22) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot22) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot22/index.html)) - pseudo scatterplot
 * [Example 23](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot23) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot23) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot23/index.html)) - the g element
 * [Example 24](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot24) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot24) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot24/index.html)) - pseudo bar chart
 * [Example 25](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot25) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot25) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot25/index.html)) - pseudo line chart
 * [Example 26](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot26) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot26) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot26/index.html)) - SVG Text
 * [Example 27](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot27) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot27) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot27/index.html)) - Styling SVG Text with CSS
 * [Example 28](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot28) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot28) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot28/index.html)) - CSS class selector syntax
 * [Example 29](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot29) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot29) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot29/index.html)) - multiple SVG text elements
 * [Example 30](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot30) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot30) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot30/index.html)) - font fill and stroke
 * [Example 31](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot31) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot31) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot31/index.html)) - Using Google Fonts
 * [Example 32](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot32) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot32) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot32/index.html)) - Applying CSS to circles
 * [Example 33](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot33) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot33) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot33/index.html)) - JavaScript Debugging
 * [Example 34](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot34) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot34) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot34/index.html)) - JavaScript Numbers
 * [Example 35](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot35) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot35) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot35/index.html)) - JavaScript Strings
 * [Example 36](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot36) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot36) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot36/index.html)) - Concatenation
 * [Example 37](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot37) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot37) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot37/index.html)) - Concatenation of number strings
 * [Example 38](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot38) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot38) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot38/index.html)) - Parsing strings with parseFloat
 * [Example 39](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot39) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot39) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot39/index.html)) - Parsing strings with +
 * [Example 40](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot40) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot40) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot40/index.html)) - JavaScript Arrays
 * [Example 41](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot41) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot41) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot41/index.html)) - JavaScript Objects
 * [Example 42](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot42) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot42) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot42/index.html)) - An array of objects
 * [Example 43](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot43) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot43) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot43/index.html)) - JavaScript functions
 * [Example 44](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot44) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot44) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot44/index.html)) - Functions in variables
 * [Example 45](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot45) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot45) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot45/index.html)) - Functional forEach
 * [Example 46](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot46) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot46) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot46/index.html)) - Loading CSV data
 * [Example 47](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot47) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot47) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot47/index.html)) - Concatenating unparsed strings
 * [Example 48](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot48) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot48) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot48/index.html)) - Parsing CSV data
 * [Example 49](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot49) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot49) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot49/index.html)) - Parsing CSV data
 * [Example 50](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot50) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot50) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot50/index.html)) - D3 linear scale
 * [Example 51](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot51) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot51) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot51/index.html)) - D3 method chaining
 * [Example 52](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot52) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot52) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot52/index.html)) - D3 getter setter functions
 * [Example 53](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot53) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot53) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot53/index.html)) - D3 ordinal scale
 * [Example 54](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot54) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot54) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot54/index.html)) - rangePoints
 * [Example 55](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot55) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot55) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot55/index.html)) - rangeRoundPoints
 * [Example 56](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot56) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot56) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot56/index.html)) - constructing DOM elements with D3
 * [Example 57](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot57) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot57) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot57/index.html)) - D3 method chaining
 * [Example 58](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot58) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot58) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot58/index.html)) - The complete D3 pipeline
 * [Example 59](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot59) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot59) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot59/index.html)) - Passing the scale as a function
 * [Example 60](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot60) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot60) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot60/index.html)) - Splitting data binding and enter
 * [Example 61](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot61) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot61) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot61/index.html)) - Enter handles added data only
 * [Example 62](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot62) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot62) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot62/index.html)) - Enter does not update data
 * [Example 63](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot63) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot63) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot63/index.html)) - The D3 update phase
 * [Example 64](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot64) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot64) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot64/index.html)) - Using enter for static properties
 * [Example 65](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot65) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot65) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot65/index.html)) - The need for exit
 * [Example 66](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot66) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot66) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot66/index.html)) - Exit
 * [Example 67](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot67) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot67) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot67/index.html)) - Using setTimeout
 * [Example 68](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot68) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot68) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot68/index.html)) - Rendering an array of objects
 * [Example 69](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot69) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot69) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot69/index.html)) - Rendering a parsed CSV file
 * [Example 70](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot70) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot70) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot70/index.html)) - Functional simplification
 * [Example 71](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot71) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot71) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot71/index.html)) - Introducing the Iris data set
 * [Example 72](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot72) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot72) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot72/index.html)) - using extent
 * [Example 73](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot73) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot73) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot73/index.html)) - basic scatter plot
 * [Example 74](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot74) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot74) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot74/index.html)) - inverting the Y range
 * [Example 75](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot75) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot75) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot75/index.html)) - isolating configurable variables
 * [Example 76](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot76) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot76) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot76/index.html)) - using variables for X and Y columns
 * [Example 77](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot77) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot77) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot77/index.html)) - Adding a radius column
 * [Example 78](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot78) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot78) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot78/index.html)) - Using CSS to color circles
 * [Example 79](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot79) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot79) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot79/index.html)) - Drawing transparent rings
 * [Example 80](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot80) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot80) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot80/index.html)) - Adding a color column
 * [Example 81](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot81) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot81) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot81/index.html)) - Using fill, tweaking parameters
 * [Example 82](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot82) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot82) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot82/index.html)) - Population vs. GDP
 * [Example 83](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot83) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot83) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot83/index.html)) - logarithmic scales
 * [Example 84](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot84) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot84) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot84/index.html)) - population as linear size
 * [Example 85](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot85) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot85) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot85/index.html)) - population as logarithmic size
 * [Example 86](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot86) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot86) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot86/index.html)) - population as sqrt size
 * [Example 87](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot87) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot87) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot87/index.html)) - population true to size
 * [Example 88](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot88) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot88) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot88/index.html)) - sizing the inner visualization
 * [Example 89](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot89) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot89) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot89/index.html)) - translating the inner visualization
 * [Example 90](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot90) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot90) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot90/index.html)) - sizing taking translation into account
 * [Example 91](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot91) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot91) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot91/index.html)) - using variables to define the margin
 * [Example 92](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot92) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot92) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot92/index.html)) - using a margin object
 * [Example 93](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot93) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot93) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot93/index.html)) - specifying number of people per pixel
 * [Example 94](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot94) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot94) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot94/index.html)) - visualizing cities
 * [Example 95](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot95) - ([run it!](http://curran.github.io/screencasts/introToD3/examples/code/snapshot95) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToD3/examples/code/snapshot95/index.html)) - tweaking the visualization

Feel free to use and modify this presentation framework for your own presentations! MIT License.

By [Curran Kelleher](https://github.com/curran/portfolio) April 2015