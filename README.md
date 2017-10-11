# Starfield-with-OpenCV
An adaptation of the 3D starfield sample from Chapter 3 of "Cutting-Edge 3d Game Programming With C++" by John De Goes using an image buffer with OpenCV



This is based on Chapter three of the book. Only with some minor changes to use OpenCV. Part of the star field is specially
arranged as a landmark. This is not an infinite starfield.

The idea of this project was to be able to do some simple 3D stuff purely out of code without special libraries. The concept
is rather outdated given what's currently available. But in case where a code-only lightweight solution may be needed
doing something like this as seen in the book and this program might fit the bill.

Once you have down the ability to write pixels to a buffer, and render those pixels, the sky is pretty much the limit. And
this is accomplished at the root with simple matrix math. If you ever wondered what the most atomic level of 3D graphics
could be, this would be one example of it.


Why do the same with OpenCV? With simple 3D rendering of pixels with a basic bare-bones matrix system combined with the computer vision capabilities 
of OpenCV, the sky is pretty much the limit. "Bit clouds" can be rendered easily by tranforming every pixel. 

This is a Visual Studio 17 project. For Linux, look in a subfolder called "Linux" and there will be a version that was tested on a Raspberry Pi. 


