# inkyconv
## Convert any image to one pimoroni's inkyphat / inkywhat understands. ##
[https://github.com/pimoroni/inky](https://github.com/pimoroni/inky)

Intended for use on a Linux system with imagemagick installed.
Should in theory also work on Windows with imagemagick in the PATH.

Beware that it puts a temp file in the working directory.

This script is hardcoded for the red InkyPHAT. If you have another model, edit the color value, example image, and display dimensions to match your product version.

The purpose of the example image is to provide imagemagick with a list of acceptable colors for the output image. I recommend using the example image provided by pimoroni (as is the included file for the red inkyphat) but any image with the right palette for your hardware should work.
