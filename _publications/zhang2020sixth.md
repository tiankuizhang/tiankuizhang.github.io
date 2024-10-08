---
title: "Sixth-order Accurate Schemes for Reinitialization and Extrapolation in the Level Set Framework"
collection: publications
permalink: /publications/zhang2020sixth
venue: "Journal of Scientific Computing"
date: 2020-03-30
---
<b>Tiankui Zhang</b> and Charles W Wolgemuth

[[pdf]](http://tiankuizhang.github.io/files/10paper/zhang2020sixth.pdf)

## Abstract
The level set method is a common approach for handling moving boundary problems, which allows a moving, irregular surface to be described implicitly on a Cartesian grid. This approach often requires reinitialization of the level set function and extrapolation of fields defined only on the interface. Because many applications in physics and engineering involve calculation of second derivatives of the interface curvature and fourth order derivatives of surface fields, accurate simulations of these problems require high-order methods for reinitialization and extrapolation. Here we build off WENO schemes for Hamilton-Jacobi equations to develop novel sixth-order accurate methods for reinitialization and extrapolation. We present numerical results in three dimensional spaces demonstrating fourth-order accuracy of the interfacial curvature and sixth-order accuracy for the extrapolated surface fields. We then show that the extrapolation scheme can be integrated into the closest point method for surface PDEs and present an example of computing geodesic curves on surfaces.

## Computation of Geodesics on the Stanford Bunny

<img src="../files/00Thesis/movies/bunny.gif" alt="computation of geodesics on the Standford bunny" width="500" height="500">
