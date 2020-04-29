---
title: "Meshing Utilities"
date: 2020-01-16
weight: 7
description: >
  Generating and manupulating quality meshes with the least effort possible using different meshing tools!
---

## Module lecture

{{< youtube C0DPdy98e4c >}}

## Learn more

- There is a 
  [Comprehensive Tour of `snappyHexMesh`](https://openfoamwiki.net/images/f/f0/Final-AndrewJacksonSlidesOFW7.pdf)
  , created by Engys Ltd. (Specifically: Andrew Jackson), so I see no point in
  replicated what they did there! **When** you absolutely need to learn
  how to work `snappyHexMesh`, use their presentation!!
- You can skim through this 
  [`cfMesh` User Guide](http://cfmesh.com/wp-content/uploads/2015/09/User_Guide-cfMesh_v1.1.pdf)
  to get a grasp of what's available.
- At this stage, It's recommended that you go through the detailed 
  [Meshing Tools Individual Assignment](https://classroom.github.com/a/EPCxH5LA) 
  to gain some hands-on experience meshing with `cfMesh`.

## Oh! There is a group assignment

To conclude this module, you are asked to participate in the **hunt**
for the best mesh that can be produced using OpenFOAM utilities
(`blockMesh`, `cfMesh`, `snappyHexMesh`, NO conversions) for a well-known
domain in your field of study.

### For Reservoir Engineering practitioners

Each group should pick a domain to mesh (we are **only** interested in the mesh
here) from the following list of cases:

- [The Egg Model](http://www.mufits.imec.msu.ru/example-egg-model.html) 
  from MUFITS examples page.
- [The Optimal well placement case](http://www.mufits.imec.msu.ru/example-well-placement.html) 
  from MUFITS examples page.
- [The Benchmark study for CO2 storage](http://www.mufits.imec.msu.ru/example-example-h3.html)
  from MUFITS examples page.
- [The Norne Field case](https://opm-project.org/?page_id=559)
  from OPM Open Datasets.

### For Other fields

- You are free to choose any geometry for any well-known problem in your field
  and mesh it using OpenFOAM utilities. The only requirement is that your
  meshing shouldn't be easy enough for **one newcomer** to OpenFOAM to build
  quickly. In short, look for challenging mesh requirements.

Follow this [Github Classroom](https://classroom.github.com/g/xyc8-k-T)
link to participate, get your meshing files and mesh stats into your repo
and wait for feedback and improvements :)
