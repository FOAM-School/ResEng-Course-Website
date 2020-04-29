---
title: "OpenFOAM Mesh Quality"
date: 2020-01-15
weight: 6
description: >
  Discussing what makes a mesh a "good mesh" from OpenFOAM's perspective
---

## Module lecture

{{< youtube C0DPdy98e4c >}}

## Learn more

- Each software package has (should have) its own "set of mesh quality
  standards", based on the numerical methods used to solve the equations.
  The metrics explained here along with their "calculation methods" are
  **OpenFOAM-specific**.
- If you want a **second-order**-accurate FVM simulations (which are 
  usually hard to achieve when it comes to reservoir simulations), stick
  with the following metrics:
  - For hex-based meshes:
      * Maximal Non-Orthogonality < 70 degrees
	  * Maximal skewness < 4  for internal faces
	  * Maximal skewness < 20 for boundary faces
  - For tetrahedral meshes, you can allow up to 80 degrees as the maximal
  Non-Orthogonality.
