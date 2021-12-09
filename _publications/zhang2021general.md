---
title: "  A general computational framework for the dynamics of single‑ and multi‑phase vesicles and membranes"
collection: publications
permalink: /publications/zhang2021general
venue: "Journal of Computational Physics"
date: 2021-12-20
---
<b>Tiankui Zhang</b> and Charles W Wolgemuth

[[pdf]](http://tiankuizhang.github.io/files/10paper/zhang2021general.pdf)

## Abstract
The dynamics of thin, membrane-like structures are unbiquitous in nature. They play especially important roles in cell biology. Cell membranes separate the inside of a cell from the outside, and vesicles compartmentalize proteins into functional microregions, such as the lysosome. Proteins and/or lipid molecules also aggregate and deform membranes to carry out cellular functions. For example, some viral particles can induce the membrane to invaginate and form an endocytic vesicle that pulls the virus into the cell. While the physics of membranes has been extensively studied since the pioneering work of Helfrich in the 1970's, simulating the dynamics of large scale deformations remains challenging, especially for cases where the membrane composition is spatially heterogeneous. Here, we develop a general computational framework to simulate the overdamped dynamics of membranes and vesicles. We start by considering a membrane with an energy that is a generalized functional of the shape invariants and also includes line discontinuities that arise due to phase boundaries. Using this energy, we derive the internal restoring forces and construct a level set-based algorithm that can stably simulate the large-scale dynamics of these generalized membranes, including scenarios that lead to membrane fission. This method is applied to solve for shapes of single-phase vesicles using a range of reduced volumes, reduced area differences, and preferred curvatures. Our results match well the experimentally measured shapes of corresponding vesicles. The method is then applied to explore the dynamics of multiphase vesicles, predicting equilibrium shapes and conditions that lead to fission near phase boundaries.

## 3D simulation of  Single Phase Vesicles

### relaxation of an oblate and a prolate
<img src="../files/00Thesis/movies/Oblate3D.gif" alt="relaxation of an oblate to a discocyte" width="250" height="250"><img src="../files/00Thesis/movies/Prolate3D.gif" alt="relaxation of an prolate to a gourd" width="250" height="250">

### pinching of an oblate and a prolate under the effect of spontaneous curvature
<img src="../files/00Thesis/movies/OblatePinch.gif" alt="pinching of an oblate under the effect of spontaneous curvature" width="250" height="250"><img src="../files/00Thesis/movies/ProlatePinch.gif" alt="pinching of an prolate under the effect of spontaneous curvature" width="250" height="250">

### deformation of vesicles under effects of osmotic pressure and constrained reduced area difference
<img src="../files/00Thesis/movies/tube.gif" alt="relaxation of a prolate to a tube" width="250" height="250"><img src="../files/00Thesis/movies/torus.gif" alt="pinching of an oblate to a torus" width="250" height="250">

<img src="../files/00Thesis/movies/Starfish2.gif" alt="deformation of an oblate into starfishes" width="250" height="250"><img src="../files/00Thesis/movies/starfish3.gif" alt="deformation of an oblate into starfishes" width="250" height="250"><img src="../files/00Thesis/movies/starfish4.gif" alt="deformation of an oblate into starfishes" width="250" height="250">

<img src="../files/00Thesis/movies/stomatocyte.gif" alt="deformation of an oblate into a stomatocyte" width="250" height="250"><img src="../files/00Thesis/movies/Pear.gif" alt="deformation of an prolate into a pear" width="250" height="250"><img src="../files/00Thesis/movies/necklace.gif" alt="deformation of an prolate into a necklace" width="250" height="250">

## 3D simulation of  BiPhasic Vesicles

### bidomain biphasic vesicles with different ratio of area for different phases

<img src="../files/00Thesis/movies/bidomain76.gif" alt="ratio 76" width="250" height="250"><img src="../files/00Thesis/movies/bidomain76_2D.gif" alt="ratio 76" width="250" height="250">

<img src="../files/00Thesis/movies/bidomain84.gif" alt="ratio 84" width="250" height="250"><img src="../files/00Thesis/movies/bidomain84_2D.gif" alt="ratio 84" width="250" height="250">

<img src="../files/00Thesis/movies/bidomain98.gif" alt="ratio 98" width="250" height="250"><img src="../files/00Thesis/movies/bidomain98_2D.gif" alt="ratio 98" width="250" height="250">

### domain coarsening under the effect of line tension
<img src="../files/00Thesis/movies/coarsen.gif" alt="domain coarsening" width="250" height="250">

### incompressible vs compressible vesicles
<img src="../files/00Thesis/movies/Compressible.gif" alt="compressible" width="250" height="250"><img src="../files/00Thesis/movies/InCompressible.gif" alt="incompressible" width="250" height="250">

### external and internal budding of vesicles
<img src="../files/00Thesis/movies/externalBudding14.gif" alt="external budding" width="250" height="250"><img src="../files/00Thesis/movies/internalBudding14.gif" alt="internal budding" width="250" height="250">
