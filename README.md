# Potential Options for Numerical Open-Source Codes in <span style="color:blue">Engineering</span>

This document describes a potential open-source codes on GitHub or GitLab that could be used to find publications for engineering tasks to evaluate performance of agentic LLMs.


The next phase of task design will be to select of few of the ***most widely used open-source*** codes and identify some new (past 2024) papers that cite the original paper. From these papers engineering sub-tasks can be extracted and designed.

## :hammer: Selected Engineering Disciplines included

These codes are collated from a broad range of selected engineering disciplines:

- 💦 Fluid Dynamics, this includes
	- porous media 
	- 🔥 thermal 
	- multiphase
	- porous media 
	- reacting flows with surface- and/or gas-phase chemistry
- ✈️ Aeronautical/Aerospace (e.g., basic aircraft design)
- 🪨 Solid Mechanics
- 🔋 Electrochemistry (e.g., batteries)
- 🧪 Chemical engineering 
- ⚡️ Electronics

## Open-Source Numerical Solvers

Links to ***23x*** codes are provided below, as well as the original paper. Additionally, metrics for number of GitHub stars, number of citations, and age of code have been provided to assess how widely used/developed the code is. This is a non-exhaustive list.

### Multiphysics Flow Solvers

| Code Name | Description | Paper link | Origin date | #️⃣ GitHub Stars 🌟 | #️⃣ Citations | Y24/25 Papers |
|:--------:|--------|:------------:|:---------:|:---------------:|:--------------:|:--------------:|
| [OpenFOAM](https://github.com/OpenFOAM/OpenFOAM-dev) | OpenFOAM is a free, open source multiphysics computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. It has a large user base across most areas of engineering and science including automotive, marine energy and aviation| [🔗 Paper DOI](https://www.researchgate.net/profile/Hrvoje-Jasak/publication/230605842_Error_Analysis_and_Estimation_for_the_Finite_Volume_Method_With_Applications_to_Fluid_Flows/links/558958d908ae2affe714ae30/Error-Analysis-and-Estimation-for-the-Finite-Volume-Method-With-Applications-to-Fluid-Flows.pdf) | ~2007 | ![GitHub Repo stars](https://img.shields.io/github/stars/OpenFOAM/OpenFOAM-dev?style=social) | 2432 | 5700 |
| [OpenLB](https://gitlab.com/openlb/release) | The OpenLB project is a C++ package for the implementation of lattice Boltzmann methods addressing a vast range of transport problems| [🔗 Paper DOI](https://doi.org/10.1016/j.camwa.2020.04.033) | 2021 | 4 GitLab stars | 160 | 115 |
| [SU2](https://github.com/su2code/SU2) | SU2 is a multiphysics computational fluid dynamics solver capable of solving reacting flows, adjoint design optimization, turbomachinery flows, linear elasticity, heat, and electrodynamics equation coupled with fluid flow| [🔗 Paper DOI](https://doi.org/10.2514/1.J053813) | 2013 | ![GitHub Repo stars](https://img.shields.io/github/stars/su2code/SU2?style=social) | 1063 | 605 |
| [Fluidity](https://github.com/FluidityProject/fluidity) | Fluidity is an open source, general purpose, multiphase computational fluid dynamics code capable of numerically solving the Navier-Stokes equation and accompanying field equations on arbitrary unstructured finite element meshes in one, two and three dimensions. It is parallelised using MPI and is capable of scaling to many thousands of processors. Other innovative and novel features include the use of anisotropic adaptive mesh technology, and a user-friendly GUI and a Python interface which can be used to calculate diagnostic fields, set prescribed fields or set user-defined boundary conditions | ... | 2013 | ![GitHub Repo stars](https://img.shields.io/github/stars/FluidityProject/fluidity?style=social) | 47 |  |
| [PyFR](https://github.com/PyFR/PyFR) | This is a high-order computational fluid dynamics solver for highly-resolved direct numerical simulations and large eddy simulations | [🔗 Paper DOI](https://doi.org/10.1016/j.cpc.2014.07.011)  | 2013 | ![GitHub Repo stars](https://img.shields.io/github/stars/PyFR/PyFR?style=social) | 356 |  104  |
| [DuMuX](https://github.com/dumux/dumux) | For multiphase, multicomponent, multiscale and multiphysics flow and transport modelling in porous media. This also includes modelling shallow water wave equations in 2D | [🔗 Paper DOI](https://doi.org/10.1016/j.advwatres.2011.03.007)  | 2011 | ![GitHub Repo stars](https://img.shields.io/github/stars/dumux/dumux?style=social) | 603 | 106 |
| [PySPH](https://github.com/pypr/pysph) | PySPH is an open source framework for Smoothed Particle Hydrodynamics (SPH) simulations. This is typically used for free surface fluid flows (such as in oceanography or sloshing tank of a liquid with air above) or solid mechanics | [🔗 Paper DOI](https://doi.org/10.1145/3460773)  | 2019 | ![GitHub Repo stars](https://img.shields.io/github/stars/pypr/pysph?style=social) | 56 | 22 |
| [SpectralDNS](https://github.com/spectralDNS/spectralDNS) | spectralDNS contains a classical high-performance pseudo-spectral Navier-Stokes high-fidelity direct numerical simulation solver for triply periodic domains. The most notable feature of this solver is that it's written entirely in Python using NumPy, MPI for Python (mpi4py) and pyFFTW. | [🔗 Paper DOI](https://doi.org/10.1016/j.cpc.2016.02.005)  | 2016 | ![GitHub Repo stars](https://img.shields.io/github/stars/spectralDNS/spectralDNS?style=social) | 82 | 36 |


### Chemistry/Electrochemistry (Batteries)

| Code Name | Description | Paper link | Origin date | #️⃣ GitHub Stars 🌟 | #️⃣ Citations | Y24/25 Papers |
|:--------:|--------|:------------:|:---------:|:---------------:|:--------------:|:--------------:|
| [PyBaMM](https://github.com/pybamm-team/PyBaMM) | PyBaMM (Python Battery Mathematical Modelling) is an open-source battery simulation package written in Python. Our mission is to accelerate battery modelling research by providing open-source tools for multi-institutional, interdisciplinary collaboration. Broadly, PyBaMM consists of (i) a framework for writing and solving systems of differential equations, (ii) a library of battery models and parameters, and (iii) specialized tools for simulating battery-specific experiments and visualizing the results. Together, these enable flexible model definitions and fast battery simulations, allowing users to explore the effect of different battery designs and modeling assumptions under a variety of operating scenarios | [🔗 Paper DOI](https://doi.org/10.5334/jors.309) | 2019 | ![GitHub Repo stars](https://img.shields.io/github/stars/pybamm-team/PyBaMM?style=social) | 335 |  201  |
| [Cantera](https://github.com/Cantera/cantera) | Cantera is an open-source collection of object-oriented software tools for problems involving chemical kinetics, thermodynamics, and transport processes | [🔗 Paper DOI](https://doi.org/10.5281/zenodo.14455267) | 2015 | ![GitHub Repo stars](https://img.shields.io/github/stars/Cantera/cantera?style=social) | 3173 | 2290 |
| [PeleC](https://github.com/AMReX-Combustion/PeleC) | An adaptive mesh refinement solver for compressible chemically reacting flows (mainly combustion). It is highly scalable and can be run on GPUs or CPUs | [🔗 Paper DOI](https://doi.org/10.1177/10943420221121151) | 2021 | ![GitHub Repo stars](https://img.shields.io/github/stars/AMReX-Combustion/PeleC?style=social) | 77 |  195 |

### Solid Mechanics

| Code Name | Description | Paper link | Origin date | #️⃣ GitHub Stars 🌟 | #️⃣ Citations | Y24/25 Papers |
|:--------:|--------|:------------:|:---------:|:---------------:|:--------------:|:--------------:|
| [FEniCS](https://github.com/FEniCS/dolfinx) | FEniCS is a popular open-source computing platform for solving partial differential equations (PDEs) with the finite element method (FEM). FEniCS enables users to quickly translate scientific models into efficient finite element code| [🔗 Paper DOI](https://doi.org/10.1145/2566630) | 2014 | ![GitHub Repo stars](https://img.shields.io/github/stars/FEniCS/dolfinx?style=social) | 705 | 1630  |
| [FreeFEM](https://github.com/FreeFem/FreeFem-sources) | FreeFEM is a partial differential equation solver for non-linear multi-physics systems in 1D, 2D, 3D and 3D border domains (surface and curve). Problems involving partial differential equations from several branches of physics, such as fluid-structure interactions, require interpolations of data on several meshes and their manipulation within one program. FreeFEM includes a fast interpolation algorithm and a language for the manipulation of data on multiple meshes| [🔗 Paper DOI](https://hal.sorbonne-universite.fr/hal-01476313v1) | 2012 | ![GitHub Repo stars](https://img.shields.io/github/stars/FreeFem/FreeFem-sources?style=social) | 4315 |  |
| [NGSolve](https://github.com/NGSolve/ngsolve) | Finite element analysis library often used in solid mechanics e.g., to get stress distribution in a body | [🔗 Paper DOI](https://doi.org/10.1007/s00158-020-02742-w)  | 2020 | ![GitHub Repo stars](https://img.shields.io/github/stars/NGSolve/ngsolve?style=social) | 41 | 185 |



### Aerospace Design and Geometry/Mesh Generators

Open-source engineering design tools are less prevalent. Most design tools are closed-source or are primarily driven by a GUI rather than through coding/scripting.


| Code Name | Description | Paper link | Origin date | #️⃣ GitHub Stars 🌟 | #️⃣ Citations | Y24/25 Papers |
|:--------:|--------|:------------:|:---------:|:---------------:|:--------------:|:--------------:|
| [AeroSandbox](https://github.com/peterdsharpe/AeroSandbox) | AeroSandbox is a Python package that helps you design and optimize aircraft and other engineered systems | [🔗 Paper DOI](https://dspace.mit.edu/bitstream/handle/1721.1/131194/ICAT-2021-03_ICAT%20Report%20Peter%20Sharpe_Thesis.pdf?sequence=1&isAllowed=y)  | 2021 | ![GitHub Repo stars](https://img.shields.io/github/stars/peterdsharpe/AeroSandbox?style=social) | 21 |  |
| [CADQuery](https://github.com/CadQuery/cadquery) | CadQuery is an intuitive, easy-to-use Python module for building parametric 3D CAD models. Using CadQuery, you can write short, simple scripts that produce high quality CAD models. It is easy to make many different objects using a single script that can be customized. | [🔗 Paper DOI](https://doi.org/10.5281/zenodo.10513848)  | 2019 | ![GitHub Repo stars](https://img.shields.io/github/stars/CadQuery/cadquery?style=social) |  |  |
| [Gmsh](https://gmsh.info/) | A CAD geometry and mesh generator that can be scripted with code (rather than with GUI) |  | 1997 |  |  |  |
| [PyMesh](https://github.com/PyMesh/PyMesh) | PyMesh is a rapid prototyping platform focused on geometry processing. It provides a set of common mesh processing functionalities and interfaces with a number of state-of-the-art open source packages to combine their power seamlessly under a single developing environment |   |  |  ![GitHub Repo stars](https://img.shields.io/github/stars/PyMesh/PyMesh?style=social)  |  |  |
| [PyVista](https://github.com/pyvista/pyvista) | 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK) |   |  |  ![GitHub Repo stars](https://img.shields.io/github/stars/pyvista/pyvista?style=social) |  |  |
| [NeuralFoil](https://github.com/peterdsharpe/NeuralFoil) | NeuralFoil is a tool for rapid aerodynamics analysis of airfoils, similar to XFoil. NeuralFoil is a hybrid of physics-informed machine learning techniques and analytical models, leveraging domain knowledge. Its learned core is trained on tens of millions of XFoil runs. |   | 2023 | ![GitHub Repo stars](https://img.shields.io/github/stars/peterdsharpe/NeuralFoil?style=social) |  | |
| [ParaBlade](https://github.com/NAnand-TUD/parablade) | ParaBlade is an open-source Python library for the parametrization of turbomachinery blades design using gradient-based optimization algorithms. | [🔗 Paper DOI](https://doi.org/10.1016/j.cad.2020.102987)  | 2021 | ![GitHub Repo stars](https://img.shields.io/github/stars/NAnand-TUD/parablade?style=social) | 47 |  |



### Electronics

| Code Name | Description | Paper link | Origin date | #️⃣ GitHub Stars 🌟 | #️⃣ Citations | Y24/25 Papers |
|:--------:|--------|:------------:|:---------:|:---------------:|:--------------:|:--------------:|
| [KiCad](https://github.com/KiCad/kicad-source-mirror) | KiCad is a free software suite for electronic design automation (EDA). It facilitates the design and simulation of electronic hardware for PCB manufacturing. It features an integrated environment for schematic capture, PCB layout, manufacturing file viewing, ngspice-provided SPICE simulation, and engineering calculation |   | 2019 | ![GitHub Repo stars](https://img.shields.io/github/stars/KiCad/kicad-source-mirror?style=social) |  |  870 |
| [PyPSA](https://github.com/PyPSA/PyPSA) | PyPSA is an open source toolbox for simulating and optimising modern power and energy systems that include features such as conventional generators with unit commitment, variable wind and solar generation, storage units, coupling to other energy sectors, and mixed alternating and direct current networks. PyPSA is designed to scale well with large networks and long time series. | [🔗 Paper DOI](https://arxiv.org/pdf/1707.09913)  | 2017 | ![GitHub Repo stars](https://img.shields.io/github/stars/PyPSA/PyPSA?style=social) | 715 | 189 |


