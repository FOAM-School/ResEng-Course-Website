---
title: "Part 1: Basic OpenFOAM Usage"
linkTitle: "Part 1"
weight: 1
description: >
  For OpenFOAM beginners to step up their game and acquire Advanced-Level skills
  (as OpenFOAM users)
  by learning every step in OpenFOAM's workflow 
---

## What does this part prensent?

This part of the course is optimized for OpenFOAM beginners (which are usually also Linux-novices)
so that they get comfortable running OpenFOAM cases and processing their results.

The whole part is an introduction to the course's core (the second part). So it may seem "fast-paced"
for some learners.

The part mainly introduces the software packages used throughout the course and helps
you set up a production labs environment to follow along and solve the assignments.

Then, it tries to present a One-Thousand-Foot view of a general simulation workflow
by comparing manual and OpenFOAM-based solution workflow for a simplified transport problem.
This is what the module **OpenFOAM Simulation in a nutshell** is for.

After that, we'll dig a little deeper in each simulation workflow step:

- The meshing step: Where we investigate some mesh tools and the quality of generated meshes.
- Equation discretization: Where we discuss finite volume schemes (from a practical point of
  view) and their usage in Reservoir Engineering context.
- OpenFOAM Case preparation and processing of generated results: Where we explore the usefulness
  of `functionObjects` from a user's perspective, and even the powerful SWAK4FOAM package.

At this point, the learner can already consider himself an intermediate-user (if he has enough 
experience of course), but there is more!

Towards the end-goal of performing design-optimization studies, we first introduce PyFOAM,
a Python-based package which can incredibly simplify the process of automating the
simulation workflow steps  learned up to this point (If you know some Python of course).

Once we're done with that, we get into **Parameterization and Optimization of OpenFOAM Cases**
where you'll learn to parametrize OpenFOAM cases using both PyFOAM and DAKOTA.

I would call anyone who has survived this far an **advanced OpenFOAM user**. But for this user to
become an advanced **reservoir-engineering-minded** OpenFOAM user, he has to go through the last
(but completely optional) module: Porous Media Simulations.

## Why do I want to go through this part?

- **What is it good for?**: Becoming an advanced OpenFOAM user. Looking at the Reservoir Engineering
  side of things is not compulsory. So, even if you have nothing to do with this field, you
  can still benefit from this part.

- **What is it not good for?**: There is little-to-no OpenFOAM-coding here, take a look at the second part if 
  that's what interests you.
  - Unless you consider medlling with SWAK4FOAM and PyFOAM "coding".
  Take a look at those modules if unsure.

## Potentially Useful tools

- **A text editor**: You'll need a decent text editor to effectively edit case files. Preferably, one
  that can easily edit files on remote servers (over SSH connections). I prefer (neo)VIM because it's
  available on most systems by default, but there are many options: Emacs, Atom and Sublime Text to 
  name a few.
- **Docker**: Running things in "containerized" Linux instances is common practice across fields.
  It's more secure and convenient. Whenever you need to play with Docker Containers, head over to
  [Play-With-Docker](https://labs.play-with-docker.com/)
- **Shell Workspace Management**: After a while, typing the same commands over and over again may get tedious.
  So, most OpenFOAM users setup some shell scripts for common tasks; while this works, I prefer
  to use a shell management tool (like [desk](https://github.com/jamesob/desk)) which manages which OpenFOAM version I load and defines 
  some convenience shell functions ... etc


## Where should I go next?

Of course you should continue to the second part.
