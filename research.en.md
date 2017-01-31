---
layout:    page
title:     Research
key:       research
lang:      en
order:     2
icon:      search
permalink: /en/research/
---
I work with computational mathematics, mostly with nonlinear optimization.
Some topics of my interest:

  - Unconstrained minimization methods;
  - Box-constrained minimization;
  - Large-scale methods;
  - Julia language;
  - Comparison and benchmarking of optimization methods;
  - Reproducible science;
  - Free open source tools.

I have interest in, or am working at, the following projects.
If you are a student looking for a research topic, this is a good start.

# Framework for Nonlinear Optimization in Julia

This is a joint work with [Dominique Orban](https://www.gerad.ca/~orban/),
and is comprised of two main parts:

  - The models to define the problems -
    [NLPModels.jl](https://github.com/JuliaOptimizers/NLPModels.jl),
    [CUTEst.jl](https://github.com/JuliaOptimizers/CUTEst.jl), and
    [AmplNLReader.jl](https://github.com/JuliaOptimizers/AmplNLReader.jl).
  - The methods to solve these problems -
    [Optimize.jl](https://github.com/JuliaOptimizers/Optimize.jl)

There is work to be done on all these parts, and we still haven't release a
stable version.

  - Keywords: Nonlinear Optimization, Julia, Framework, CUTEst

# CUTEst.jl

[CUTEst.jl](https://github.com/optimizers/CUTEst.jl) is a Julia interface for
the CUTEst repository.
This interface provides many ways to access the CUTEst functions, allowing a
work-now-improve-later workflow for nonlinear optimization.
Despite being part of the framework above, CUTEst can be improved independently,
due to its high usage in the field.

 - Keywords: CUTEst, Julia, Nonlinear Optimization

# Reproducible Science and Free Open Source Software

When the next "best optimization algorithm ever" comes around, I want to be able
to verify the claim.
This is only possible through reproducible science.
The data and steps that describe a research should be available to the peers.
Some easy steps can be taken to improve the reproducibility and availability of
a research project, and I think believe this should be of greater concern that
it is.
Furthermore, when dealing with reproducible science, I believe that free
software should be considered whenever possible.
The reproducibility of a project is limited when using proprietary software.

 - Keywords: Reproducible Science, Open Science, Open Source, Free Software

# Computational Tools for Researchers and Software Carpentry

In the spirit of good and reproducible science, some tools are very important,
and useful, for a researchers.
Despite the field, a researcher may find that some tasks would be better left
for the computer, such as renaming thousands of files.

One organization that helps in that endeavor is
[Software Carpentry](http://software-carpentry.org/).
Software Carpentry provides researchers with a short introduction class to
several of these tools. Whenever possible, instructors are taken from the same
field as that of the researcher.

Some noteworthy tools are Git, LaTeX, Bash, Python, Julia and Markdown.

 - Keywords: Computational Tools, Software Carpentry
