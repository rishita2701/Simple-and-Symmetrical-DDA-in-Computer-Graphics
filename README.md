# Simple-and-Symmetrical-DDA-in-Computer-Graphics

In computer graphics, a digital differential analyzer (DDA) is hardware or software used for interpolation of variables over an interval between start and end point. DDAs are used for rasterization of lines, triangles and polygons. They can be extended to non linear functions, such as perspective correct texture mapping, quadratic curves, and traversing voxels.

In its simplest implementation for linear cases such as lines, the DDA algorithm interpolates values in interval by computing for each xi the equations xi = xi−1 + 1, yi = yi−1 + m, where m is the slope of the line. 

This article contains code for positive and negative line slope using simple and symmetrical DDA.
