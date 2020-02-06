# Project-1
This project begin with foundational work with c++. Specifically, in Part 1 I create a simple C++ class that represents a colored pixel; I am also provided with a PNG image class that encapsulates the loading and saving of image files. In Part 2, you will use the pixel and PNG classes from Part 1 to transform an image in several different ways.

The first function is Illinify:To illinify an image is to transform the hue of every pixel to Illini Orange (11) or Illini Blue (216). The hue of every pixel should be set to one or the other of these two hue values, based on whether the pixel's original hue value is closer to Illini Orange or Illini Blue. 

The second function is spotlight: A spotlight adjusts the luminance of a pixel based on the distance between the the pixel and the designated center by decreasing the luminance by 0.5% per 1 pixel unit of Euclidean distance, up to an 80% decrease in
luminance at most.

The third function is watermark: To watermark an image is to lighten a region
of it based on the contents of another image that acts as a stencil.For every pixel that exists within the bounds
of both base image and stencil, the luminance of the base image should be increased by +0.2 (absolute, but not
to exceed 1.0) if and only if the luminance of the stencil at the same pixel position is at maximum (1.0).
