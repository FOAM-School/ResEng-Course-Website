---
title: "OpenFOAM Vocabulary"
date: 2020-02-28
weight: 8
description: >
  Learn basic terminology used by CFD practitioners ...
---

CFD
: **C**omputational **F**luid **D**ynamics, I don't have to explain what that is, right?

-----

Mesh
: Is the discretized version of continuous domain:
  - A line is _meshed_ into a set of a finite number of segments,
  - A 2D plane can be meshed into a set of a finite number of squares, triangles, 
    and/or any other (preferably) regular 2D geometries
  - And, a volume is meshed into a finite number of cells of any shape (hexahedral, tetrahedral, polyhedral ...etc).

-----

Discretization
: It's a Math word, refers to the transition from the continuous state (of something, 
  eg. an equation, a function) to a discrete representation.

-----

Discretization scheme
: The algorithm which handles the discretization of a specific term in an equation through a discrete domain.

-----

Pre-Processing
: An important stage in CFD analysis: Describe the problem as an OpenFOAM model (case)

-----

Simulation
: The process of solving the PDEs (or ODEs) on the meshed domain: Gives nothing but a set of text 
  files containing (usually) a huge amount of data.

-----

Post-Processing
: Processing the data resulting from the simulation: May include building new data (new calculations) 
  and visualizing some of its features.

-----

BCs
: (Boundary Conditions) The same as in Fluid Dynamics: Constraints applied on physics fields (p, U, T, ... etc)
  at some mesh boundaries.

-----

ICs
: (Initial Conditions) Values of physics fields at internal cells of the mesh at 
  simulation's starting time.

-----

OpenFOAM case
: A directory (frequently called "a folder" on Windows!) containing all the necessary information 
  to successfully run the desired fluid flow simulation.

-----

Function Objects
: What you would call "User Defined Functions" (UDFs) in commercial software packages.
  For advanced users: C++ objects having function-like behaviour, allowing them to run
  at solver run-time.

-----

OpenFOAM Fork
: When someone makes his own "version" of an open-source software package, it's called a fork.
  The word "version" is reserved for the "versions" produced by the original owner of
  the software.
