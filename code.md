---
layout: default
title: Code
---

# Programming

<hr>
## Math for biomedical modelling
### Computational Fluid Dynamics
* [**Navier-Stokes benchmark**](https://gitlab.com/piemollo/cfd/
ns-validation); FreeFem code to validate and benchmark an unsteady NS
solver.
* **Dropipe**; [currently private] FreeFem code to validate pressure
drop in CFD simulation.
* **Cerebral Venous Network**; [currently private] FreeFem, Python and
Octave codes to pre-process raw data from medical acquisitions,
simulate the venous blood flow and post-process results. 
* **2D Bifurcation sandbox problem**; [currently private] FreeFem and 
Octave codes to validate new approaches. 

### Physiological modelling
* **Flow rate manager**; [currently private] Octave application to 
process and resample data set (e.g. from real acquisitions).
* **Center lines**; [currently private] Octave capplication to
load, display and manage center line from vessel networks.

<hr>
## Reduced Order Modelling
### Reduced Basis Methods
* [**Proper Orthogonal Decomposition**](https://gitlab.com/piemollo
/rom/rbm/pod); 
(**Octave version**).
code to perform POD on data array composed of snapshot of a 
parametric model. 
* [**Reduced Basis Suite**](https://gitlab.com/piemollo/rom/rbm/rbs);
FreeFem code to manage RB items.
* [Old Reduced Basis Code](https://gitlab.com/piemollo/rom/rbm/old-rbm); FreeFem code to run RBM problems

### State estimation
* [**Empirical Interpolation Method**](https://gitlab.com/piemollo
/rom/eim/ffeim);
([**Octave version**](https://gitlab.com/piemollo/rom/eim/eim-oct)).
code to perform EIM on data array composed of snapshot of a 
parametric model. 
* **Parametrized-Background Data-Weak**; [currently private] 
Octave code to perfom PBDW.

<hr>
## Numerical Analysis
* **Radial Basis Function**;
[currently private] Octave code to perform RBF interpolation with
several kernel functions.
* **Non-Parametric Estimation**;
[currently private].

<hr>
## Tool boxes
* [**Extended Linear Algebra FreeFem**](https://gitlab.com/piemollo/
tb/elaf); FreeFem code to perform standard LA operations between
arrays and matrices.
* [**FF Matlib**](https://gitlab.com/piemollo/tb/ffmatlib);
FreeFem and Octave code to interface both languages
(forked project, original [here](https://github.com/samplemaker
/freefem_matlab_octave_plot).
* [**Statistical Display Matlab**](https://gitlab.com/piemollo/tb/
statistical-display-matlab-octave);
Matlab(c) code to display distributed data over several categories.
* **Grid Manager**; [currently private] Octave/Matlab(c) codes 
to manage 2D grid in 3D environment. Useful step to provide 
_in silico_ MRI measurements.
