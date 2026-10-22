---
layout: page
title: Software
permalink: /software/
---

#### Current Research Software

Primary author:

* [heart_valves](https://github.com/alexkaiser/heart_valves): First-principles model generation and fluid-structure interaction (FSI) for aortic and mitral valves. Includes code that calls IBAMR for FSI and visualization. Used in publications: 
[[Sim-Guided Design of Surgical Repair]](https://doi.org/10.1016/j.jtcvs.2023.12.027), 
[[Clinical Translation of Surgical Repair]](https://doi.org/10.3389/fcvm.2026.1957668), 
[[Rare Disease Physiology of Truncus Arteriosus]](https://doi.org/10.1016/j.jtcvs.2026.04.039), 
[[Mitral Elasticity-Based Design]](https://doi.org/10.1002/cnm.3240), 
[[Aortic Elasticity-Based Design]](https://doi.org/10.1007/s10237-021-01516-7),
[[Sim-Guided Design of Surgical Repair II]](https://doi.org/10.1016/j.xjon.2025.09.038), 
[[4D MRI Comparison]](https://doi.org/10.1007/s10439-023-03266-2), 
[[Bicuspid Flows]](https://doi.org/10.1007/s10439-022-02983-4).

Contributor:

* [IBAMR](https://ibamr.github.io/): Immersed boundary adaptive mesh refinement, fluid-structure interaction code suitable for simulating heart valve mechanics. Derived and implemented new delta function kernels with three continuous derivatives. Used in preprint: [[Gaussian-Like Kernels]](https://arxiv.org/abs/1505.07529v4) 

* [svZeroDSolver](https://github.com/SimVascular/svZeroDSolver): Lumped-parameter solver in C++ for blood flow and pressure in hemodynamic networks. Prototyped a two-hill chamber activation model and a parameter-tuning workflow, which served as drafts for features later added to the solver. 

* [svFSI](https://github.com/SimVascular/svFSI): Multi-physics finite element solver for patient-specific blood flow simulation, including fluid-structure interaction and cardiac electrophysiology. Helped establish the open-source svFSI repository from internal legacy code. 

* [SimVascular](https://simvascular.github.io/): Comprehensive tools for modeling and simulation of patient-specific vascular flows. Used for image segmentation and model construction; maintained a fork adding an option to disable reslice interpolation, so MRI planes display without blurring on oblique views or widely spaced slices. 

#### Earlier Work

Primary author:

* [mc_stretch](https://github.com/alexkaiser/mc_stretch): Fast, affine-invariant, GPU parallel MCMC. Developed in thesis: [[MS Thesis]](/pdfs/kaiser_computational_exp_mcmc_ms_thesis_2013.pdf)

* [SimplifySum](https://github.com/alexkaiser/SimplifySum): Automatic simplification of symbolic sums in Mathematica, over 1000x faster than built-in Mathematica algorithms on certain problems. Developed for and used in publication: [[Auto-Simplification]](https://doi.org/10.1016/j.jsc.2013.09.001)

Contributor:

* [ARPREC](https://www.davidhbailey.com/dhbsoftware/): Arbitrary precision arithmetic in C++ with overloaded operators. Handled library maintenance, documentation and user issues while at Lawrence Berkeley National Laboratory, 2009–2011; now mirrored by David H. Bailey.

* [QD](https://www.davidhbailey.com/dhbsoftware/): Double-double and quad double precision arithmetic in C++ with overloaded operators. Handled library maintenance, documentation and user issues while at Lawrence Berkeley National Laboratory, 2009–2011; now mirrored by David H. Bailey.

* MatrixFFT: Apple’s high-performance FFT library. Developed a mixed-language interface for it with the Advanced Computation Group in 2010; the library and the group appear to have since been discontinued.
