---
layout: post
title: "Auxetics and Foams"
img: flexshape-icon.jpg # Add image post (optional)
date: 2022-09-01 00:00:00 +0000
description: # Add post description (optional)
tag: #none 
---
I spent the summer of 2022 working at CSAIL (Computer Science and Artificial Intelligence Lab, MIT) participating in researching auxetics of various designs and testing the material properties of celled "foams". 

### Project 1: Handed Shearing Auxetics

This project dealt with flattened shapes which expand diagonally on living hinges. I used Rhino + Grasshopper design program to change the parameters of the living hinges and printed them out of FPU on a resin printer, then tested each design to determine which set of parameters best contributed to the expansion of the auxetic shapes. 

{HSA print image}

The shapes were tested on a mechanical testing rig that I designed, built and programmed with Arduino to repeatedly stretch the shapes. 

{rig image} 

### Project 2: Flipping Shapes

Regular polyhedra each have duals. It's possible to connect the vertices of a polyhedron to the vertices of its dual in such a way that the shape can be "flipped inside-out", which has been put to use in color-flipping toys such as the Hoberman Flip Out. 

This project reconstructed a tetrahedron-tetrahedron flipping shape, as well as a cube-octohedron one, in order to investigate possible methods of actuation. 

![Tetrahedral 3d-printed shape](../../../assets/img/flex-tetra.jpg)

I designed the hinge and vertex system for this shape, which scales to the cube-octohedron shape as well, in Solidworks before printing it in a combination of FDM and SLA parts. 

![Model on Solidworks](../../../assets/img/flex-sw.jpg)


### Project 3: Foams

There's continual research into the use of different materials, or differently arranged materials, for use in the bodies of soft robots. In this case, my lab was testing different parameters, such as cell density and chord thickness, of structures called "foams" which were printed from a highly elastic rubber material. 

