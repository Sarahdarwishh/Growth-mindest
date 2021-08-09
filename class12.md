
 #  Chart.js, Canvas

***What is a Chart.js ?***
its a way to draw graph onto the html page using HTML5’s canvas element.


***Types of charts ***

1. Scatter
2. Line
3. Bar
4. Radar
5. Pie and Doughnut
6. Polar Area

***Creating a Chart***
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. 

***License***
Chart.js is available under the MIT license .

***Shadows***
-Using shadows involves just four properties:

1. shadowOffsetX = float Indicates the horizontal distance the shadow should extend from the object. This value isn’t affected by the transformation matrix. The 2. default is 0.
2. shadowOffsetY = float Indicates the vertical distance the shadow should extend from the object. This value isn’t affected by the transformation matrix. The 3. default is 0.
3. shadowBlur = float Indicates the size of the blurring effect; this value doesn’t correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0.
4. shadowColor = color A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black.

***Basic usage of canvas***


At first sight a < canvas > looks like the < img > element, with the only clear difference being that it doesn’t have the src and alt attributes. Indeed, the < canvas > element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn’t respect the ratio of the initial canvas, it will appear distorted.

