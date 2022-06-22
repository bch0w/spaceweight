# spaceweight
[![Build Status](https://travis-ci.org/wjlei1990/spaceweight.svg?branch=master)](https://travis-ci.org/wjlei1990/spaceweight)
[![DOI](https://zenodo.org/badge/22621/wjlei1990/spaceweight.svg)](https://zenodo.org/badge/latestdoi/22621/wjlei1990/spaceweight)

Spatial weighting given a set of pionts on the unit sphere.

The weights are calculated based on geographical distribution of points. The weighting strategy includes:
1. [Spherical Voronoi Split](https://github.com/wjlei1990/spaceweight/blob/master/src/spaceweight/spherevoronoi.py#L177)
2. [Exponetial Decay](https://github.com/wjlei1990/spaceweight/blob/master/src/spaceweight/sphereweightbase.py#L256)
3. [Azimuth Bin](https://github.com/wjlei1990/spaceweight/blob/master/src/spaceweight/sphereazimuth.py#L22)

Please consider citing [this paper](https://doi.org/10.1093/gji/ggz356) if you used it in your research project:

`Youyi Ruan, Wenjie Lei, Ryan Modrak, Rıdvan Örsvuran, Ebru Bozdağ, Jeroen Tromp, Balancing unevenly distributed data in seismic tomography: a global adjoint tomography example, Geophysical Journal International, Volume 219, Issue 2, November 2019, Pages 1225–1236, https://doi.org/10.1093/gji/ggz356`

