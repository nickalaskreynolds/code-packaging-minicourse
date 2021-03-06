# code-packaging-minicourse
Materials related to the graduate mini-course on code development and packaging at the University of Toronto

## Table of Contents

* [Logistics](#logistics)
* [Assignments](#assignments)
* [Lecture notes](#lecture-notes)
* [Lecture slides](#lecture-slides)
* [Code package examples](#code-package-examples)

## Logistics

* **Meeting time / room**: Tue/Fri 11:10 - 12:30pm / AB 113; meetings on Feb. 25, Mar. 3, Mar. 10, Mar. 24, and a TBD date.

* **Instructor**: Jo Bovy, AB229

* **Email**: jo - dot - bovy - at - utoronto - dot - ca

* **Syllabus**: Full details can be found in the [syllabus](syllabus/syllabus-codemini.pdf)

## Assignments

* **Assignment 1**: available [here](assignments/assignment1.pdf), due on Mar. 3

* **Assignment 2**: TBP

* **Assignment 3**: TBP

* **Assignment 4**: TBP

## Lecture notes

A set of lecture notes will be sent to students taking the class by email; these will appear here at the end of the class.

## Lecture slides

* **Week 1**: TBP

## Code package examples

As part of this course, you will develop a scientific software package, learning how to use git/GitHub to host it, how to test and document it, how to use automatic documentation/building/testing tools, how to release the package, and how to deal with issues and pull requests. If you have a software package related to your research, please use this and we can turn it into a full-featured software package. If you do not have a personal software package that you want to use, here are some ideas for simple packages to use for the course's assignments:

* A *cosmological distances package*: create a simple package that computes different cosmological distances for different cosmologies, for example, following [Hogg (1999)](https://arxiv.org/abs/astro-ph/9905116).

* A *cosmology calculator*: similar to the above, but create a Python package that provides similar functionality as [Ned Wright's cosmology calculator](http://www.astro.ucla.edu/~wright/ACC.html).

* A *transit light curve package*: compute the transit lightcurve of an exoplanet orbiting a star, e.g., following [Mandel & Agol (2002)](https://arxiv.org/abs/astro-ph/0210099).

* A *simple stellar model package*: implement the simple polytropic model of stellar structure, computing models for different polytropic indices, following, e.g., [these notes](https://www.astro.princeton.edu/~gk/A403/polytrop.pdf).

* A *simple observation planner*: a package to help plan observations of celestial objects, answering such questions as "When is a target at a given (RA,Dec) best observable from a given location?", "How long is the object in question above the horizon on a given day?", "Which of a given set of observatories is best to observe a target from on a given day (or during a given period)?".

* A *package for inspecting the cosmic history of star formation and stellar mass growth*: implement the results from [Behroozi et al. (2012)](https://arxiv.org/abs/1207.6105), available [at the bottom of this page](https://www.peterbehroozi.com/data.html). For example, implement the stellar-mass vs. halo-mass relations and allow them to be evaluated at any redshift/halo mass using interpolation.

Whichever example you choose or when you bring your own package, it's important that your package implements both classes and functions so we can learn about documentation and testing features for both of these.



