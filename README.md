Author: Katelyn Rohrer [katelynrohrer@arizona.edu] 
Course: Grad 533
Date: Feb. 7, 2025


Executing program:
This program runs on display of index.html.
Once open, click `Choose File` and select `bunny.ppm`, which was provided in this repo as an example image.


Description:
This program displays a simple site with an upload button. Once an image is uploaded, it will display a rotating
and scaling version of that image, as well as a live updating matrix used to transform each frame.

I did notice that the canvas would display with different dimensions if I had my window sized differently,
so I edited that part to remain static (the spec said a flat 600x600 dimension was acceptable). (Lines 168-171)
I did use 800x800, as it was closer to the original dimensions of the image.


Included files:
* index.html    -- a sample html file with a canvas
* a01.js        -- a sample javascript file for functionality with the image uploading, and a method to parse PPM images
* MathUtilities.js		-- some math functions that you can use and extend yourself. It contains matrix manipulations
* bunny.ppm     -- a test image
* 

* Images obtained from the following sources:
  * bunny: http://graphics.stanford.edu/data/3Dscanrep/  