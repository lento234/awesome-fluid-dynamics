<div align="center">

# Awesome Fluid Dynamics
[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme)
![CI](https://github.com/lento234/awesome-fluid-dynamics/workflows/CI/badge.svg)

A curated list of repositories related to fluid dynamics. 

*`Please send pull requests or raise issues to improve this list.`*

</div>

## Contents

- [Awesome Fluid Dynamics](#awesome-fluid-dynamics)
  - [Contents](#contents)
  - [1. Educational](#1-educational)
    - [Notebooks](#notebooks)
    - [Lecture series](#lecture-series)
    - [Books](#books)
  - [2. Computational fluid dynamics (CFD)](#2-computational-fluid-dynamics-cfd)
    - [Meshing](#meshing)
    - [Solvers](#solvers)
      - [Finite element methods (FEM)](#finite-element-methods-fem)
      - [Finite volume methods (FVM)](#finite-volume-methods-fvm)
      - [Spectral methods](#spectral-methods)
      - [Lattice Boltzmann methods (LBM)](#lattice-boltzmann-methods-lbm)
      - [Other techniques](#other-techniques)
    - [Machine learning / Deep Learning](#machine-learning--deep-learning)
  - [3. Experimental fluid dynamics](#3-experimental-fluid-dynamics)
    - [PIV / PTV](#piv--ptv)
    - [Machine learning](#machine-learning)
  - [4. Post-processing and data analysis](#4-post-processing-and-data-analysis)
  - [5. Visualization](#5-visualization)
    - [2D visualization](#2d-visualization)
    - [3D visualization](#3d-visualization)
  - [6. Benchmarks and datasets](#6-benchmarks-and-datasets)
    - [Dataset](#dataset)
    - [Benchmark](#benchmark)
  - [7. Reproducibility](#7-reproducibility)
  - [8. Related links](#8-related-links)

## 1. Educational

### Notebooks
- [barbagroup/CFDPython](https://github.com/barbagroup/CFDPython): A sequence of Jupyter notebooks featuring the "12 Steps to Navier-Stokes" ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/barbagroup/CFDPython/search?l=jupyter-notebook)
- [gpeyre/numerical-tours](https://github.com/gpeyre/numerical-tours): Numerical Tours of Signal Processing and other materials. ![MATLAB](logo/MATLAB.svg) ![Python](logo/Python.svg) ![Jupyter](logo/Jupyter.svg) ![julia](logo/julia.svg) ![R](logo/R.svg)

### Lecture series
- [Steve Brunton/Fluid Dynamics](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQWO3ESiccZmPssvUDFHL4M): Prof. Brunton's lecture series on Fluid dynamics. ![YouTube](logo/YouTube.svg)
- [Barry Belmont/NSF Fluid Mechanics Series](https://www.youtube.com/playlist?list=PL0EC6527BE871ABA3): A collection of NFS Fluid Mechanics lecutre series from mid 20th century. ![YouTube](logo/YouTube.svg)

### Books

- Brunton, S., & Kutz, J. (2019). Data-Driven Science and Engineering: Machine Learning, Dynamical Systems, and Control. Cambridge: Cambridge University Press. [:memo:](https://doi.org/10.1017/9781108380690)

## 2. Computational fluid dynamics (CFD)

### Meshing

- [nschloe/optimesh](https://github.com/nschloe/optimesh): Mesh optimization, mesh smoothing. ![Python](logo/Python.svg)
- [nschloe/pygmsh](https://github.com/nschloe/pygmsh): Gmsh for Python ![Python](logo/Python.svg)
- [nschloe/meshio](https://github.com/nschloe/meshio): I/O for exhaustive number of mesh file types ![Python](logo/Python.svg)
- [PyMesh/PyMesh](https://github.com/PyMesh/PyMesh): Geometry Processing Library for Python ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [cnr-isti-vclab/meshlab](https://github.com/cnr-isti-vclab/meshlab): The open source mesh processing system ![C++](logo/cpp.svg)
- [inducer/meshpy](https://github.com/inducer/meshpy): 2D/3D simplicial mesh generator interface for Python (Triangle, TetGen, gmsh) ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [gmsh](https://en.wikipedia.org/wiki/Gmsh): A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities ![C++](logo/cpp.svg) ![Python](logo/Python.svg) ![julia](logo/julia.svg)
- [CGAL/cgal](https://github.com/CGAL/cgal): The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry. ![C++](logo/cpp.svg)


### Solvers

#### Finite element methods (FEM)

- [JuliaFEM/JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl): The JuliaFEM software library is a framework that allows for the distributed processing of large Finite Element Models across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. ![julia](logo/julia.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/JuliaFEM/JuliaFEM.jl/search?l=jupyter-notebook)
- [FEniCS/dolfinx](https://github.com/FEniCS/dolfinx): Next generation FEniCS problem solving environment ![C++](logo/cpp.svg) ![Python](logo/Python.svg) 
- [deal.II](https://dealii.org/): An open source finite element library ![C++](logo/cpp.svg)
- [firedrakeproject/firedrake](https://github.com/firedrakeproject/firedrake): Firedrake is an automated system for the portable solution of partial differential equations using the finite element method (FEM) ![Python](logo/Python.svg)

#### Finite volume methods (FVM)

- [OpenFOAM/OpenFOAM-dev](https://github.com/OpenFOAM/OpenFOAM-dev): OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. ![C++](logo/cpp.svg)
- [su2code/SU2](https://github.com/su2code/SU2): SU2: An Open-Source Suite for Multiphysics Simulation and Design  ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [cselab/aphros](https://github.com/cselab/aphros): Finite volume solver for incompressible multiphase flows with surface tension ![C++](logo/cpp.svg)
- [code-saturne/code_saturne](https://github.com/code-saturne/code_saturne):  code_saturne public mirror ![C++](logo/cpp.svg) ![FORTRAN](logo/FORTRAN.svg) ![Python](logo/Python.svg)

#### Spectral methods

- [DedalusProject/dedalus](https://github.com/DedalusProject/dedalus):  A flexible framework for solving PDEs with modern spectral methods. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/DedalusProject/dedalus/search?l=jupyter-notebook)
- [FourierFlows/FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl): Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains ![julia](logo/julia.svg)
- [Nek5000/Nek5000](https://github.com/Nek5000/Nek5000): NEK5000 is an spectral element CFD code developed at the Mathematics and Computer Science Division of Argonne National Laboratory. ![FORTRAN](logo/FORTRAN.svg)
- [spectralDNS/shenfun](https://github.com/spectralDNS/shenfun): High performance computational platform in Python for the spectral Galerkin method ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/spectralDNS/shenfun/search?l=jupyter-notebook)

#### Lattice Boltzmann methods (LBM)

- [aromanro/LatticeBoltzmann](https://github.com/aromanro/LatticeBoltzmann): A 2D Lattice Boltzmann program ![C++](logo/cpp.svg)

#### Other techniques

- [jostbr/shallow-water](https://github.com/jostbr/shallow-water): Python model solving the shallow water equations (linear momentum, nonlinear continuity) ![Python](logo/Python.svg)
- [PavelDoGreat/WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation): Play with fluids in your browser (works even on mobile) ![JavaScript](logo/JavaScript.svg)
- [PyFR/PyFR](https://github.com/PyFR/PyFR): Framework for solving advection-diffusion type problems on streaming architectures using the Flux Reconstruction approach of Huynh. ![Python](logo/Python.svg)
- [precice/precice](https://github.com/precice/precice): A coupling library for partitioned multi-physics simulations, including, but not restricted to fluid-structure interaction and conjugate heat transfer simulations. ![C++](logo/cpp.svg)
- [cwrowley/ibpm](https://github.com/cwrowley/ibpm): Immersed Boundary Projection Method (IBPM) ![C++](logo/cpp.svg)
- [barbagroup/PetIBM](https://github.com/barbagroup/PetIBM): PetIBM - toolbox and applications of the immersed-boundary method on distributed-memory architectures ![C++](logo/cpp.svg)
- [vortexmethods/VM2D](https://github.com/vortexmethods/VM2D): VM2D: Open-Source Code for 2D Flow Simulation by Using Meshless Lagrangian Vortex Methods ![C++](logo/cpp.svg)
- [markstock/vic2d](https://github.com/markstock/vic2d): Two-dimensional semi-Lagrangian vortex method for very low viscosity fluid simulation ![C++](logo/cpp.svg) ![FORTRAN](logo/FORTRAN.svg)
- [Cantera/cantera](https://github.com/Cantera/cantera): Chemical kinetics, thermodynamics, and transport tool suite ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [NREL/EnergyPlus](https://github.com/NREL/EnergyPlus): EnergyPlus™ is a whole building energy simulation program that engineers, architects, and researchers use to model both energy consumption and water use in buildings. ![C++](logo/cpp.svg)
- [uDALES/u-dales](https://github.com/uDALES/u-dales): uDALES: large-eddy-simulation software for urban flow, dispersion and microclimate modelling ![FORTRAN](logo/FORTRAN.svg)
- [taichi-dev/taichi](https://github.com/taichi-dev/taichi):  Parallel programming for everyone. ![Python](logo/Python.svg)
- [DARcorporation/xfoil-python](https://github.com/DARcorporation/xfoil-python): Stripped down version of XFOIL as compiled python module ![Python](logo/Python.svg)
- [mdolab/dafoam](https://github.com/mdolab/dafoam):  DAFoam: Discrete Adjoint with OpenFOAM for High-fidelity Gradient-based Design Optimization ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [peterdsharpe/AeroSandbox](https://github.com/peterdsharpe/AeroSandbox): Aircraft design optimization made fast through modern automatic differentiation. Plug-and-play analysis tools for aerodynamics, propulsion, structures, trajectory design, and much more. ![Python](logo/Python.svg)
- [team-ocean/veros](https://github.com/team-ocean/veros): The versatile ocean simulator, in pure Python, powered by JAX. ![Python](logo/Python.svg)
- [CliMA/Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl): Julia software for fast, friendly, flexible, data-driven, ocean-flavored fluid dynamics on CPUs and GPUs ![julia](logo/julia.svg)

### Machine learning / Deep Learning

- [lululxvi/deepxde](https://github.com/lululxvi/deepxde): Deep learning library for solving differential equations and more. ![Python](logo/Python.svg)
- [SciML/NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl): Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations for Scientific Machine Learning (SciML) accelerated simulation. ![julia](logo/julia.svg)
- [google/neural-tangents](https://github.com/google/neural-tangents):  Fast and Easy Infinite Neural Networks in Python. ![Python](logo/Python.svg)
- [cornellius-gp/gpytorch](https://github.com/cornellius-gp/gpytorch): A highly efficient and modular implementation of Gaussian Processes in PyTorch. ![Python](logo/Python.svg)
- [google/jax-cfd](https://github.com/google/jax-cfd): Computational Fluid Dynamics in JAX. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/google/jax-cfd/search?l=jupyter-notebook)
- [isl-org/DeepLagrangianFluids](https://github.com/isl-org/DeepLagrangianFluids): Lagrangian Fluid Simulation with Continuous Convolutions. ![Python](logo/Python.svg)
- [tum-pbs/PhiFlow](https://github.com/tum-pbs/PhiFlow): A differentiable PDE solving framework for machine learning. ![Python](logo/Python.svg)

## 3. Experimental fluid dynamics 

### PIV / PTV

- [JHU-NI-LAB/OpenLPT_Shake-The-Box](https://github.com/JHU-NI-LAB/OpenLPT_Shake-The-Box): Open-source C++ code for Shake-the-box, particle tracking algorithm ![C++](logo/cpp.svg) ![MATLAB](logo/MATLAB.svg)
- [OpenPTV/openptv](https://github.com/openptv/openptv) OpenPTV - open source 3D-PTV software ![C++](logo/cpp.svg)
- [OpenPIV/openpiv-python](https://github.com/openpiv/openpiv-python): OpenPIV consists in a Python and Cython modules for scripting and executing the analysis of a set of PIV image pairs. ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/OpenPIV/openpiv-python/search?l=jupyter-notebook)
- [OpenPTV/pyptv](https://github.com/openptv/pyptv) Python GUI for OpenPTV - open source three-dimensional particle tracking velocimetry. ![Python](logo/Python.svg)

### Machine learning

- [erizmr/UnLiteFlowNet-PIV](https://github.com/erizmr/UnLiteFlowNet-PIV): Unsupervised learning of Particle Image Velocimetry. (ISC 2020) ![Python](logo/Python.svg)
- [shengzesnail/PIV-LiteFlowNet-en](https://github.com/shengzesnail/PIV-LiteFlowNet-en): Particle image velocimetry via a deep neural network (LiteFlowNet) ![C++](logo/cpp.svg) ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg)
- [yongleex/PIV-DCNN](https://github.com/yongleex/PIV-DCNN): Perform PIV image pair match using deep conv neural network. ![MATLAB](logo/MATLAB.svg) ![C++](logo/cpp.svg)

## 4. Post-processing and data analysis

- [numpy/numpy](https://github.com/numpy/numpy): The fundamental package for scientific computing with Python. ![Python](logo/Python.svg)
- [mathLab/PyDMD](https://github.com/mathLab/PyDMD):  Python Dynamic Mode Decomposition ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/mathLab/PyDMD/search?l=jupyter-notebook)
- [dynamicslab/pysindy](https://github.com/dynamicslab/pysindy): A sparse regression package with several implementations for the Sparse Identification of Nonlinear Dynamical systems. ![Python](logo/Python.svg)
- [ritchieng/eigenvectors-from-eigenvalues](https://github.com/ritchieng/eigenvectors-from-eigenvalues): This repository implements a calculation of eigenvectors from eigenvectors elegantly through PyTorch. ![Jupyter](logo/Jupyter.svg)
- [mengaldo/PySPOD](https://github.com/mengaldo/PySPOD):  A Python package for spectral proper orthogonal decomposition (SPOD).  ![Python](logo/Python.svg)
- [belson17/modred](https://github.com/belson17/modred): An easy-to-use and parallelized library for finding modal decompositions and reduced-order models. ![Python](logo/Python.svg)
- [Astroua/TurbuStat](https://github.com/Astroua/TurbuStat): Statistics of Turbulence Python Package. ![Python](logo/Python.svg)
- [SURGroup/UQpy](https://github.com/SURGroup/UQpy): UQpy (Uncertainty Quantification with python) is a general purpose Python toolbox for modeling uncertainty in physical and mathematical systems. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/SURGroup/UQpy/search?l=jupyter-notebook)
- [haller-group/LCStool](https://github.com/haller-group/LCStool): LCStool: LCS Tool is a computational engine for analyzing fluid flows by extracting their most influential material surfaces, Lagrangian Coherent Structures. ![MATLAB](logo/MATLAB.svg)
## 5. Visualization

### 2D visualization

- [matplotlib/matplotlib](https://github.com/matplotlib/matplotlib): matplotlib: plotting with Python ![Python](logo/Python.svg)
- [scikit-image/scikit-image](https://github.com/scikit-image/scikit-image): Image processing in Python ![Python](logo/Python.svg)
- [3b1b/manim](https://github.com/3b1b/manim): Animation engine for explanatory math videos. ![Python](logo/Python.svg)
- [garrettj403/SciencePlots](https://github.com/garrettj403/SciencePlots): Matplotlib styles for scientific plotting. ![Python](logo/Python.svg)
- [mwaskom/seaborn](https://github.com/mwaskom/seaborn): Statistical data visualization in Python ![Python](logo/Python.svg)

### 3D visualization

- [K3D-tools/K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter): K3D lets you create 3D plots backed by WebGL with high-level API (surfaces, isosurfaces, voxels, mesh, cloud points, vtk objects, volume renderer, colormaps, etc). ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/K3D-tools/K3D-jupyter/search?l=jupyter-notebook)
- [sciapp/gr](https://github.com/sciapp/gr): GR framework: a graphics library for visualisation applications ![C++](logo/cpp.svg) ![Python](logo/Python.svg)
- [QuantStack/ipygany](https://github.com/QuantStack/ipygany):  3-D Scientific Visualization in the Jupyter Notebook ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/QuantStack/ipygany/search?l=jupyter-notebook)
- [InsightSoftwareConsortium/itkwidgets](https://github.com/InsightSoftwareConsortium/itkwidgets):  Interactive Jupyter widgets to visualize images, point sets, and meshes in 2D and 3D ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/InsightSoftwareConsortium/itkwidgets/search?l=jupyter-notebook)
- [NVIDIA/ipyparaview](https://github.com/NVIDIA/ipyparaview):  iPython widget for server-side ParaView rendering in Jupyter. ![Python](logo/Python.svg) ![JavaScript](logo/JavaScript.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/NVIDIA/ipyparaview/search?l=jupyter-notebook)
- [Kitware/Vtk](https://gitlab.kitware.com/vtk/vtk): Visualization Toolkit ![C++](logo/cpp.svg)
- [Kitware/paraview](https://www.paraview.org/): An open-source, multi-platform data analysis and visualization application. ![Python](logo/Python.svg)
- [pyvista/pyvista](https://github.com/pyvista/pyvista): 3D plotting and mesh analysis through a streamlined interface for the Visualization Toolkit (VTK) ![Python](logo/Python.svg)

## 6. Benchmarks and datasets

### Dataset

- [shengzesnail/PIV_dataset](https://github.com/shengzesnail/PIV_dataset): PIV dataset ![MATLAB](logo/MATLAB.svg)
- [idies/pyJHTDB](https://github.com/idies/pyJHTDB):  Python wrapper for the Johns Hopkins turbulence database library. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/idies/pyJHTDB/search?l=jupyter-notebook)

### Benchmark

- [dionhaefner/pyhpc-benchmarks](https://github.com/dionhaefner/pyhpc-benchmarks):  A suite of benchmarks for CPU and GPU performance of the most popular high-performance libraries for Python ![Python](logo/Python.svg)
- [su2code/TestCases](https://github.com/su2code/TestCases): An extensive collection of common test cases for SU2. ![C++](logo/cpp.svg) ![Python](logo/Python.svg)

## 7. Reproducibility

- [iterative/dvc](https://github.com/iterative/dvc): Data Version Control | Git for Data & Models | ML Experiments Management. ![Python](logo/Python.svg) 
- [sphinx-doc/sphinx](https://github.com/sphinx-doc/sphinx): Sphinx is a tool that makes it easy to create intelligent and beautiful documentation for Python projects ![Python](logo/Python.svg) 

## 8. Related links

- [alexlib/awesome_piv](https://github.com/alexlib/awesome_piv); A curated list of repositories related to PIV (particle image velocimetry). ![Awesome](https://awesome.re/badge-flat.svg)
- [nschloe/awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing): Curated list of awesome software for numerical analysis and scientific computing. ![Awesome](https://awesome.re/badge-flat.svg)
- [qd-cae/awesome-CAE](https://github.com/qd-cae/awesome-CAE): A curated list of awesome CAE frameworks, libraries and software. ![Awesome](https://awesome.re/badge-flat.svg)
- [awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets):  A topic-centric list of HQ open datasets. ![Awesome](https://awesome.re/badge-flat.svg)
