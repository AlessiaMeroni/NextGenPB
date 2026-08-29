# NextGenPB 
-----------  
Copyright (C) 2021-2025 Vincenzo Di Florio

Copyright (C) 2019-2025 Carlo de Falco

Copyright (C) 2020-2021 Martina Politi

This software is distributed under the terms
the terms of the GNU/GPL licence v3

# Overview
----------

**NextGenPB** is a high-performance solver for the linearized Poisson–Boltzmann equation (PBE), built on an adaptive octree mesh.
It efficiently computes electrostatic potentials in heterogeneous dielectric media using a flexible, hierarchical discretization scheme.

The equation solved is:


$$
-\mathrm{div} \left( \varepsilon_0 \varepsilon_r \nabla \varphi \right) + \kappa^2 \varphi = \rho^f
$$

on a rectangular domain.

# Documentation & Tutorials
---

Comprehensive installation instructions, examples, and usage guides are available here:

[NextGenPB Tutorial and Guide](https://vdiflorio.github.io/nextgenpb_tutorial/)

For this branch (`mesh-repartitioning`) specifically — the new load-balancing strategy for the surface-energy computation, the `--strategy` option, and full build and testing instructions for both a laptop and an HPC cluster — see [INSTALL.md](INSTALL.md).

---

# Citation

If you use **NextGenPB** in your research, please cite the following article:

>Di Florio, V., Ansalone, P., Siryk, S. V., Decherchi, S., De Falco, C., & Rocchia, W. (2025). NextGenPB: An analytically-enabled super resolution tool for solving the Poisson-Boltzmann Equation featuring local (de) refinement. Computer Physics Communications, 109816.
