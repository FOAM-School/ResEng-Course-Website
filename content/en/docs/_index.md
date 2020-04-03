---
title: "Course Content"
linkTitle: "Course"
permalink: "/course"
weight: 20
menu:
  main:
    weight: 20
---

{{% pageinfo %}}
The course is packaged in two **parts**:

- _Part 1:_ For those who never used OpenFOAM before, requires no (to little) programming skills
- _Part 2:_ For those who are already efficient in dealing with C++ code and have some experience
  with OpenFOAM cases.

It's recommended that you open a **LinuxOne-Community** Account before beginning the course

Enjoy!
{{% /pageinfo %}}

## This is an Opinionated course!

**Every single** tool that will be used throughout the course is of course replaceable; I work
with what's convenient for me - but it might not be the perfect choice for you!

That said, there are some assumptions I make on your background:

- You are running a Recent Linux Distribution (Ubuntu-Like preferred). It's not a requirement!
  But you're on your own if you're running something else!
- You've read the first few (Five or so) sections of OpenFOAM's User Guide.
- You are willing to write code, debug it and share it with others.
- You do have some programming experience in some language (C++ and Python are preferred).
- You have a Github account and know how to use Git.

## Course workflow

1. The course is divided into two parts, each contains a set of modules.
2. Each module has a set of lecture videos, individual and/or group assignments.
3. Individual assignments involve answering quiz-like questions.
4. Group assignments are mini-projects to apply what you've learned in the module:
  You can join a group of at most 3 individuals to carry these projects out.
5. At the end of each part, going through a capstone project is suggested.
  You can join a team of up to 5 individuals.
6. Many assignments will automatically open "pull requests" for me to provide
  feedback on your work.

It's recommended that you use the labs environment (we will help you set it up) but it's 
completely optional.

## Rules for engaging in group activities

- We use Github repos for the assignments: you can contribute to, review and improve the code 
  posted by your teammates.
- Joining existing groups should be preferred over creating new ones.
- Please don't meddle with the repos' history (no ``squashes``, no ``fixups``) while working in a group!
  It breaks things for your teammates and makes them angry for no reason.
- Use Pull Requests to merge branches (or at least, use the `--no-ff` option on the command line).
  It's important to keep track of who did what!
- Forking code posted by another group is in fact **encouraged**! But you should make significant
  improvements to their version. Keep in mind that anyone can also fork your code too!

## Contributions

Spotted a **typo**? Or do you think something may be a little "clearer" if said (written) in a different way?
Just hit the "Edit this page" link on the top-right of this page, make your changes,
and commit them with a useful message. I'll review your changes and accept them if feasible.

Do you think there is an issue in the course content you're viewing? Hit the ``Create course issue``
button on the top-right of this page to open a Github issue. Explain what's the problem there.

At advanced stages of the course, you may be using some classes from my Open Reservoir Simulation
Research (OpenRSR) toolkit. If you notice there is an issue (eg. Usage of outdated code in the course,
or simply have a suggestion) you can open a project issue by clicking on `Create a project issue` button.
