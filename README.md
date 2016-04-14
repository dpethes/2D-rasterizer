2D-rasterizer
=============

Basic 2D triangle software rasterizer with texture mapping.
Uses the half-space approach to find covered pixels.
Features:
* texture mapping with nearest-neighbor or bilinear filtering
* subpixel precision
* resolution up to 2048x2048

References
-----------
* http://forum.devmaster.net/t/advanced-rasterization/6145 - basic setup / rasterization, subpixel precision, fill convention
* http://fgiesen.wordpress.com/2013/02/17/optimizing-sw-occlusion-culling-index/ - maths, optimalizations
* http://www1.eonfusion.com/manual/index.php/Formulae_for_interpolation - vertex attribute interpolation (link doesn't work anymore, search archive.org) 

Compilation
-----------
Use recent Freepascal (2.6.0 and higher) to compile, older versions will likely
work as well, but are untested.

TODO
-----------
documentation, demo

