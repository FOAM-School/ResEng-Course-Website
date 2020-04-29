---
title: "OpenFOAM Workflow: The meshing step"
linkTitle: "OpenFOAM Workflow: The meshing step"
date: 2020-01-13
weight: 6
description: >
  A deeper look on how the meshing process should be carried out.
---

{{% alert title="Note" %}}
Make sure you went through all mesh-related assignments (at least up to the intermediate-level) of the previous 
modules before attempting to continue!

Typically, you should have attempted at least one meshing process with `blockMesh` at this point.
{{% /alert %}}

In this module, we'll

- Discuss meshing for Reservoir Engineering tasks and meshing for FVM simulations.
- Assess mesh quality according to OpenFOAM metrics.
- Use `cfMesh` meshing workflows to mesh a pore-scale representation of a sample porous medium
- Learn about different meshing utilities (generators and manipulators) that are available in 
  Foam-Extend.

Let's get started.
