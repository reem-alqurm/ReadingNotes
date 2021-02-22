# Charts:
* Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They are easier to look at and convey data quickly, but they are not always easy to create.

* A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5â€™s canvas element to draw the graph onto the page. It as a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

* To see how to use chart.js we are going to create a set of 3 graphs; one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart; the second will show which countries the customers come from, this will be the pie chart; finally weâ€™ll use a bar chart to show profit over the period.

# Setting up :
* The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory youâ€™ll be working in. Then create a new html page and import the script:
### Drawing a line chart
* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:
### Drawing a pie chart
* Our line chart is complete, so letâ€™s move on to our pie chart. First, we need the canvas element:
`< canvas id = “ countries “ width = “ 600 “ height = “400” >`` < / canvas >` Next, we need to get the context and to instantiate the chart:

`var countries = document.getElementById( “ countries “ ).getContext( “ 2d “ ); new Chart( countries )`.`Pie( pieData, pieOptions )`;

### Drawing a bar chart
* Finally, letâ€™s add a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart weâ€™ve already added. First, we add the canvas element: `< canvas id = “ income “ width =” 600 “ height = “ 400 “ > < / canvas >`
### Creating a Chart
* easy to get started with Chart.js. All that’s required is the script included in your page along with a single 

* In this example, we create a bar chart for a single dataset and render that in our page. You can see all the ways to use Chart.js in the usage documentation.

`< canvas id = “ tutorial “ width = “ 150 “ height = “ 150 “ > < / canvas >`

### The grid
* Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we’ll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we’ll stick to the default. 

# Colors
* Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
`fillStyle = color`
* Sets the style used when filling shapes.
`strokeStyle = color`
* Sets the style for shapes’ outlines.
color is a string representing a CSS `< color >`, a gradient object, or a pattern object. We’ll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).
Drawing text
T* he canvas rendering context provides two methods to render text:

`fillText(text, x, y [, maxWidth])`
* Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth])
* Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

*****************************************************************

## [ Home ](https://reem-alqurm.github.io/ReadingNotes/)
