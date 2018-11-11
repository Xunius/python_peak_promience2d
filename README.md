# python_peak_promience2d

Compute peak prominence on 2d array using contour method using `numpy` and 
`matplotlib`

The prominence of a local maximum (peak) is defined as 

> the height of the peak's summit above the lowest contour line encircling it
> but containing no higher summit.

See [wikipedia](https://en.wikipedia.org/wiki/Topographic_prominence)
for more details.

This module takes a surface in R3 defined by 2D arrays of X, Y and Z,
and use enclosing contours to find local maxima and their prominences.

Optionally, peaks with small prominence or area can be filtered out.

See a toy example below:

![](https://github.com/Xunius/python_peak_promience2d/blob/master/demo.png)

