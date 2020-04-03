---
title: "Useful Shortcuts"
date: 2020-02-28
weight: 7
description: >
  So you don't get tired while working on the terminal!
---

While working on OpenFOAM cases, you can use some shell aliases to get around faster
(These are shell commands):

`run`
: Changes the working directory to the `$FOAM_RUN` directory, which is supposed to hold your
  OpenFOAM cases

``tut``
: Changes the working directory to the `$FOAM_TUTORIALS` directory, which contains standard
  OpenFOAM tutorials for all standard solvers.

``src``
: Changes the working directory to the `$FOAM_SRC` directory, which contains the source code
  for all OpenFOAM (standard) libraries and solvers.

``doc``
: Changes the working directory to the directory containing code documentation (and the user
  guide) for the current OpenFOAM version.

``wm32`` and ``wm64``
: Toggle between compiling for 32-bits and 64-bits machines (A bit advanced, but keep it in mind).

-----

These are just examples: run the `alias` command to figure out the rest ...

-----

I also recommend using a shell-workspace manager, something like [Desk](https://github.com/jamesob/desk), to manage OpenFOAM commands.
Some benefits include:

- Easy to work with multiple versions/forks of OpenFOAM.
- Local commands history, so OpenFOAM commands don't get mixed up with your other 10000 commands.
- Definition of convenience shell functions only inside that specific workspace (scoping is always good).

We'll help you build your first OpenFOAM desk just after we perform our very first simulation!
