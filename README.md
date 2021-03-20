<div align="center">

# Awesome Fluid Dynamics
[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme)
![CI](https://github.com/lento234/awesome-fluid-dynamics/workflows/CI/badge.svg)

A curated list of repositories related to fluid dynamics. 

*`Please send pull requests or raise issues to improve this list.`*

</div>


- [Awesome Fluid Dynamics](#awesome-fluid-dynamics)
  - [1. Computational fluid dynamics (CFD)](#1-computational-fluid-dynamics-cfd)
    - [1.1 Educational](#11-educational)
    - [1.2 Meshing](#12-meshing)
    - [1.3 Solvers](#13-solvers)
      - [Finite element methods (FEM)](#finite-element-methods-fem)
      - [Finite volume methods (FVM)](#finite-volume-methods-fvm)
      - [Spectral methods](#spectral-methods)
      - [Others](#others)
  - [2. Experimental fluid dynamics](#2-experimental-fluid-dynamics)
    - [2.1 PIV / PTV](#21-piv--ptv)
    - [2.2 Machine learning / AI](#22-machine-learning--ai)
  - [3. Visualization, analysis and post-processing](#3-visualization-analysis-and-post-processing)
    - [3.1 2D plotting](#31-2d-plotting)
    - [3.2 3D plotting](#32-3d-plotting)
    - [3.3 Analysis](#33-analysis)
  - [4. Benchmarks and datasets](#4-benchmarks-and-datasets)
    - [Dataset](#dataset)
    - [Benchmark](#benchmark)
  - [Related](#related)

--------------------------------


## 1. Computational fluid dynamics (CFD)

### 1.1 Educational
- [barbagroup / CFDPython](https://github.com/barbagroup/CFDPython): A sequence of Jupyter notebooks featuring the "12 Steps to Navier-Stokes" ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/barbagroup/CFDPython/search?l=jupyter-notebook)

### 1.2 Meshing
- [nschloe / optimesh](https://github.com/nschloe/optimesh): Mesh optimization, mesh smoothing. ![Python](logo/Python.svg)
- [nschloe / pygmsh](https://github.com/nschloe/pygmsh): Gmsh for Python ![Python](logo/Python.svg)
- [PyMesh / PyMesh](https://github.com/PyMesh/PyMesh): Geometry Processing Library for Python ![cpp] ![Python](logo/Python.svg)
- [cnr-isti-vclab / meshlab](https://github.com/cnr-isti-vclab/meshlab): The open source mesh processing system ![cpp]
- [inducer / meshpy](https://github.com/inducer/meshpy): 2D/3D simplicial mesh generator interface for Python (Triangle, TetGen, gmsh) ![cpp] ![Python](logo/Python.svg)
- [Gmsh](https://gmsh.info/): A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities ![cpp] ![Python](logo/Python.svg) ![julia]
- [CGAL / cgal](https://github.com/CGAL/cgal): The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry. ![cpp]


### 1.3 Solvers
#### Finite element methods (FEM)
- [JuliaFEM / JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl): The JuliaFEM software library is a framework that allows for the distributed processing of large Finite Element Models across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. ![julia] [![Jupyter](logo/Jupyter.svg)](https://github.com/JuliaFEM/JuliaFEM.jl/search?l=jupyter-notebook)
- [FEniCS / dolfinx](https://github.com/FEniCS/dolfinx): Next generation FEniCS problem solving environment ![cpp] ![Python](logo/Python.svg) 
- [deal.II](https://dealii.org/): An open source finite element library ![cpp]

#### Finite volume methods (FVM)
- [OpenFOAM / OpenFOAM-dev](https://github.com/OpenFOAM/OpenFOAM-dev): OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. ![cpp]
- [su2code / SU2](https://github.com/su2code/SU2): SU2: An Open-Source Suite for Multiphysics Simulation and Design  ![cpp] ![Python](logo/Python.svg)

#### Spectral methods

- [DedalusProject / dedalus](https://github.com/DedalusProject/dedalus):  A flexible framework for solving PDEs with modern spectral methods. ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/DedalusProject/dedalus/search?l=jupyter-notebook)
- [FourierFlows / FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl): Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains ![julia]
- [Nek5000 / Nek5000](https://github.com/Nek5000/Nek5000): NEK5000 is an spectral element CFD code developed at the Mathematics and Computer Science Division of Argonne National Laboratory. ![fortran]
- [spectralDNS / shenfun](https://github.com/spectralDNS/shenfun): High performance computational platform in Python for the spectral Galerkin method ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/spectralDNS/shenfun/search?l=jupyter-notebook)

#### Others

- [aromanro / LatticeBoltzmann](https://github.com/aromanro/LatticeBoltzmann): A 2D Lattice Boltzmann program ![cpp]
- [jostbr / shallow-water](https://github.com/jostbr/shallow-water): Python model solving the shallow water equations (linear momentum, nonlinear continuity) ![Python](logo/Python.svg)
- [PavelDoGreat / WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation): Play with fluids in your browser (works even on mobile) ![javascript]
- [PyFR / PyFR](https://github.com/PyFR/PyFR): Framework for solving advection-diffusion type problems on streaming architectures using the Flux Reconstruction approach of Huynh. ![Python](logo/Python.svg)

## 2. Experimental fluid dynamics 

### 2.1 PIV / PTV

- [JHU-NI-LAB / OpenLPT_Shake-The-Box](https://github.com/JHU-NI-LAB/OpenLPT_Shake-The-Box): Open-source C++ code for Shake-the-box, particle tracking algorithm ![cpp] ![MATLAB](logo/MATLAB.svg)
- [OpenPTV / openptv](https://github.com/openptv/openptv) OpenPTV - open source 3D-PTV software ![cpp]
- [OpenPIV / openpiv-python](https://github.com/openpiv/openpiv-python): OpenPIV consists in a Python and Cython modules for scripting and executing the analysis of a set of PIV image pairs. ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg) (https://github.com/OpenPIV/openpiv-python/search?l=jupyter-notebook)
- [OpenPTV / pyptv](https://github.com/openptv/pyptv) Python GUI for OpenPTV - open source three-dimensional particle tracking velocimetry ![Python](logo/Python.svg)

### 2.2 Machine learning / AI

- [erizmr / UnLiteFlowNet-PIV](https://github.com/erizmr/UnLiteFlowNet-PIV): Unsupervised learning of Particle Image Velocimetry. (ISC 2020) ![Python](logo/Python.svg)
- [shengzesnail / PIV-LiteFlowNet-en](https://github.com/shengzesnail/PIV-LiteFlowNet-en): Particle image velocimetry via a deep neural network (LiteFlowNet) ![cpp] ![Python](logo/Python.svg) ![MATLAB](logo/MATLAB.svg)
- [yongleex / PIV-DCNN](https://github.com/yongleex/PIV-DCNN): Perform PIV image pair match using deep conv neural network ![MATLAB](logo/MATLAB.svg) ![cpp]


## 3. Visualization, analysis and post-processing

### 3.1 2D plotting

- [matplotlib / matplotlib](https://github.com/matplotlib/matplotlib): matplotlib: plotting with Python ![Python](logo/Python.svg)
- [scikit-image / scikit-image](https://github.com/scikit-image/scikit-image): Image processing in Python ![Python](logo/Python.svg)

### 3.2 3D plotting

- [K3D-tools / K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter): K3D lets you create 3D plots backed by WebGL with high-level API (surfaces, isosurfaces, voxels, mesh, cloud points, vtk objects, volume renderer, colormaps, etc). ![Python](logo/Python.svg) ![javascript] [![Jupyter](logo/Jupyter.svg)](https://github.com/K3D-tools/K3D-jupyter/search?l=jupyter-notebook)
- [sciapp / gr](https://github.com/sciapp/gr): GR framework: a graphics library for visualisation applications ![cpp] ![Python](logo/Python.svg)
- [QuantStack / ipygany](https://github.com/QuantStack/ipygany):  3-D Scientific Visualization in the Jupyter Notebook ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/QuantStack/ipygany/search?l=jupyter-notebook)
- [InsightSoftwareConsortium / itkwidgets](https://github.com/InsightSoftwareConsortium/itkwidgets):  Interactive Jupyter widgets to visualize images, point sets, and meshes in 2D and 3D ![Python](logo/Python.svg) ![javascript] [![Jupyter](logo/Jupyter.svg)](https://github.com/InsightSoftwareConsortium/itkwidgets/search?l=jupyter-notebook)
- [NVIDIA / ipyparaview](https://github.com/NVIDIA/ipyparaview):  iPython widget for server-side ParaView rendering in Jupyter. ![Python](logo/Python.svg) ![javascript] [![Jupyter](logo/Jupyter.svg)](https://github.com/NVIDIA/ipyparaview/search?l=jupyter-notebook)
- [Kitware / Vtk](https://gitlab.kitware.com/vtk/vtk): Visualization Toolkit ![cpp]
- [Kitware / paraview](https://www.paraview.org/): An open-source, multi-platform data analysis and visualization application. ![Python](logo/Python.svg)

### 3.3 Analysis

- [numpy / numpy](https://github.com/numpy/numpy): The fundamental package for scientific computing with Python. ![Python](logo/Python.svg)
- [mathLab / PyDMD](https://github.com/mathLab/PyDMD):  Python Dynamic Mode Decomposition ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/mathLab/PyDMD/search?l=jupyter-notebook)

## 4. Benchmarks and datasets

### Dataset

- [shengzesnail / PIV_dataset](https://github.com/shengzesnail/PIV_dataset):  PIV dataset ![MATLAB](logo/MATLAB.svg)
- [idies / pyJHTDB](https://github.com/idies/pyJHTDB):  Python wrapper for the Johns Hopkins turbulence database library ![Python](logo/Python.svg) [![Jupyter](logo/Jupyter.svg)](https://github.com/idies/pyJHTDB/search?l=jupyter-notebook)

### Benchmark

## Related

- [alexlib / awesome_piv](https://github.com/alexlib/awesome_piv); A curated list of repositories related to PIV (particle image velocimetry). ![Awesome](https://awesome.re/badge-flat.svg)
- [nschloe / awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing): Curated list of awesome software for numerical analysis and scientific computing. ![Awesome](https://awesome.re/badge-flat.svg)
- [qd-cae / awesome-CAE](https://github.com/qd-cae/awesome-CAE): A curated list of awesome CAE frameworks, libraries and software. ![Awesome](https://awesome.re/badge-flat.svg)
<!--- custom badges -->

[cpp]: https://img.shields.io/badge/C/C++-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADIAAAA4CAYAAAC%2FpKvXAAAG50lEQVR42tWYA3gkTRPH%2B7VtfrZtxznbTvLaPE6cnH1ZnG3b%2B8VeXWzvZsO16q3t57yYmUXwf55%2FMD3bXb%2FuqppJSKA0RySLiBLKzqO7r%2Fuc4xoZLIoSFv8wSig9joGDKyPMhdli6c%2FJQNXb62XPYKApaBMaWGyJFsgEMzcVvkAGihgG7p0jkk7D4NrQwNMaPL0PGeby%2FaQ%2FhQD%2FxWCkaPDRJf1SP7PFyu9HiWT7aBD%2B9fmYNOVPSaA1dZv0sWiBlMEFjWgIkM140quiBflPBawO8PhbAgbg3N3aHfUzdt%2B%2B%2B4g%2FhCfwJ5w4Cw39YexuhTFpsn%2F6Usiv445sw8nsaOh%2FS49jTN%2FhcQL5j16vAz0aBphNjvp5f3XFk8StAO7BYxyLN9f5sliMSA4Jhypg85UGOFbQBmelajgjVcHh3FbYhNeY%2FeX0Hh%2BBmrCGoh21e9cpyL%2BHg9m%2BTL70eBVklXeC3mQFNmmNVvh%2FiQZSj1X5CpQ1a5Psu9drQf6SL91oCQJUq3TgrcqatZBytNKn06GvOlFC%2BTpvJnh3kwIkuKt28F12nOSivJ3OyTMOfViy5MojM7ctJQ4ivhCf7yiBhnYD%2BFn0ZD%2Fdfo1TDONW5mY%2BMWt7I5koBnQT8QZC1WOCQEnVbYJPd7iHmbGhuOSN9w9IKcDt5gPx3mYFNGoMEGjVqvV0rbue9Jq%2FLjp39Z5JYisN3AcQ2pX6SLSr3Xj3ilySfvXBqZu7nQG8AFl1ugb4SqM1Q2WrDmpUetAarPwaAJo5UKJ4evaOOg8A%2FECiRTJo7jQCFxktNjhZ1Abz9pY5zbMAr12Qq8FotoEn4VqmGHFWGTsAT5D152q55Tbu%2FJc7S1jnm49ADS5qrddgsQvOV1Q8MGWThQbnbxBpXQ%2Bn1snjOUDvrb%2Fewq02O1xWqhtffWd3Bw3KG3PoVHQhT8LXEtqW%2BbbyuXtKcZO6O%2F8Zd4qtDnwHWcmhyI%2FktfKGmJVWXPPzz45n%2BgbAA%2BRATgtrd%2FliJ4%2FTEMi6%2Fhl78cp9UzYZ3QX14NRNcFHRBMKLpU5jz8zZTsdWnFLwA7mibAdPauowcIWwjV6Rnf7otG1qtt19ZPpmQGHaaZzGXn57Jx2TlLTwA8mu6ARPUtT3sEJMWZdf9ELMHk7tNK9KjZujA4csVhv9Oe1CCR0rbe6Clk49HTNZ6Bi%2Bfcu4geSwgMg9gMwWFDf9%2Bv096SQkMYeMTeNS0DTYXoMZHLLZ7fTnbZIKxxgNXGu03Oh0dGztWSXH1LqmAU9q1LhMLW3QglNX7gtNNJCgOLhuM4lIuUomCLv7JbUOshW7HeCzW2%2Br9tFL0tMfG7qkjQbvysFxGjJs2VVc3OoO5KFpmyG%2FWg27Miqdxp6L2k7HsBHwA1nN3n5pZ5uxrkjx2uQNcrcATkAJJWT02uI%2Ba7%2Fvb1GAjeWBiHlreWHMUjsNkIffmLgS9ktK1N99f1dzoEGoFQ09wCaJrA4eDEvkDPFQeCJklzSCQ3ojFu3xgtrHpm3WBhREcKEOUJxgXhyzjBXizUmrKMTdatb0Wt9Nu1iKfzzZAgFC%2Fw%2FV1mUELursNcBX4ovwyrjlLlMpfocEND168KSCihb9PxccrvA7yByBtJXZk68E7qLPAGWtCk7lVMCFwmqobumkvZ%2FP5%2F%2F%2B8TYpGS9o8geIKTLx0tUHw5J7HDu676oS%2Bko7LshunKSORCy%2BQiaI9F6BTFqZk%2FvUyOX1t6fGU8NTobS%2BHQIteU2bY6272nV8Mxm%2BMh2DtnMCmbm%2BqPRbU4XF7gr125NXQ6O6BwKlelU3rSV36yPQNTJ6fZkrkFZaB0KZ5q9fHLl6T3Ccla3rfGvyKiipV4O%2FJa1qhdevQ7DYRsKS08l4oeo6SAuZkybdQOsgPKmbz8PsiWEpNI%2F9pY2ni%2BicPB%2BqWlo%2FkzauJeS%2FCa%2FhBTUavHHY1ztpTnurgvJmCP1qJ53LS6tIMPMqofof81MSFC%2F3djJMRxgyfzccSi8Bg8kCbNIazLD7koJuAn7WewiMmcZ%2BhxjmXhychm5Dg7d%2BOCIJ%2Fv3pVnh39SlYuj8LBCcKqJN3p8M7eO0vH2yCRyKTfAieugOL%2FkPyb%2BZ%2B4laRyc%2BQoNgUvNmEhgFmC1pAwpNeIJz1P%2BaH%2BKETAwjiAvoXxGsFxQeR4DhFPwKUk%2BDYscQv%2Bp3gAZqTQXGdfQjQiynOkPDVDxG%2FK5R5Fk9nFS5iDSCADbNgG%2Flf4ksk0MKFfoILng4AxGUSGvcr0ucKiR2Ki1f5AaCetv5%2B1Vjmwev10%2B0FgJbWwb%2BZh8mAUWjiK7THc6sfO6bnPhLEvEkGrP7L%2FBYDlXiAyCX%2Fi%2FsLGRyCezDYCY6g0Rbq4NgcxzU6FgB9A0T9f5VBrS%2FNAAAAAElFTkSuQmCC

[fortran]: https://img.shields.io/badge/FORTRAN-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADwAAAA8CAMAAAANIilAAAACxFBMVEUAAAAAAEQAWnwsLCw%2BK1JPNGtpVI1rXHttUJxxTZVxUJdzTpd0S5Z0TZN0T5d0UJV0UJZ1TJB1Tpd2T5d4UomDW0KUUpV2TphyT5lyUJdzTpRzT5dzT5dzTpZzT5ZyT5ZzT5dyUJdzUJZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZyT5ZzT5ZzT5ZzT5ZzUJZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZzT5ZtRJNuR5NwS5RxTJVxTZVyTZVyTZZyTpVyTpZzTpZzT5Z0UJd1UZd1UZh2Uph2U5h3VJl3VZl4Vpp4V5p5Vpp5V5t6V5t6WZt7W5t8XJx8XZx%2BYZ2BZaCDZqGHbqSIcKONdaiOdqiSequSe6uSfKqVf62Xg66ZhbCfj7Snl7qqmryqm7yqnLytob6uob6xosGzpsO0psS1p8W1qcS2qcW2qsa4q8e4rMe5rci6rsi6r8m9scq9scu%2Bssu%2Bssy%2Bs8y%2FtMzBts7Bt83Bt87DudDEu8%2FFu9HGvNHGvNLGvdLGvtHHvdLHvtPIvtPIv9TIwdPJv9TJwNTJwdPKwdTKwdXKwtTLwtXLwtbMw9fMxNXNxNfNxdfNxdjOxtjPx9jPx9nQx9nQyNnRydrSytvSy9vTzNzUzd3Uzt3Vzd3Vzt3W0N7Y0t%2Fa1OHb1eLb1uLc1%2BLd2OTe2OTf2ubf2%2BXh3ebi3efj3ujj3%2Bnk3%2Bnl4Orl4erl4evn4%2Bvn4%2Bzp5e3p5u3q5u%2Fq5%2B%2Fs6vDt6fDv7PPw7fPx7%2FTy8PXz8PXz8fb08vf29Pj29fj39vn49vr59%2Fr6%2Bfv6%2Bfz7%2Bvz8%2B%2F38%2FP3%2B%2Fv7%2B%2Fv%2F%2F%2F%2F%2F8fj9eAAAAVHRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAECAgcJCgsSFBcaGx4gJS00OkNFSU1UWWlqeICBlZeqrLC2ub7Dx87P0dTW2t%2Fg4eXp7fHy8%2Fb3%2BPr7%2FP6laoTqAAACUUlEQVR42rTWA3BcQRjA8a1t27Zt2zh9tc3U5tV2nNSpU9u2bezYjjbzHd4sk%2F4Hdw%2B%2FZ5H4UqUtV7cjKNe9afWCKUliuYvU6QV6tSibjdk0pZqDdp0q5Im3ecu0A4O6lM9ASM7ibcCo9iUzkgINwbAG%2BUgV9q%2F%2Fxmjljg5lphJpzP70fUiV%2BzGamYakmznuQsAcQ7Jg27KgoPATd39T7ObOhIKCIiKiTl979ImLsanfcZbV4JNt5lUZhscWjDl3yfA9PgbXLQm%2BI8AQ8E%2BMb4uw874YX7dg15xFcU1J%2BL9GjK9YsP0VjWthwv9pYnzZgsd89uARn4T4kgVPph7c74kQn7fguV7YeUGIz1rwKS8MkUIc7Y%2FHffXGbiE%2B6Y1xUxDPE%2BJjiN19eo%2BcseQu9cGz3r17%2F%2FHNKA6OQvz57ZcffykLMQwcPHTYcODgg9QSYoyHDyQF70sKjkgefMgdefH5Ly0cingpgMM2ccsfDRyCeAUktFIDByNeBQm5PqjjIMRr8VZRxnsQrwPWcnW8G%2FFmYAWY4G3AmvDTYJ93AGvIe4OjHQisAS%2B%2BxbVA7zyHQWJjx8c1RO%2FG2A%2FCxA%2BDw%2Fr4DOLj%2BvgG4nNOXWx7jfipFnba%2Bk3aTj0dmT7I5lTC%2FfY%2BePb2J%2FXt76eXD%2B%2FMF2Pxp9Sm%2F4U7y%2FAGru1B6snwei5uScr1Yudo8VZOs7m4FklfGwzrUIykKNzMzPaqmpWQ7CXaGuHYGQkyAAGLijPpWoMMuRnAgF3OglS9LlrCDFDAK6Fj7Ue8Tj9bfWkekD4AUtc0wt9wgCkAAAAASUVORK5CYII%3D


[imagej]: https://img.shields.io/badge/ImageJ-white.svg


[Java]: https://img.shields.io/badge/Java-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAABFFBMVEUAAAD%2BvGH%2BuWT9ezz%2BjEO968n8aDH%2Bi0b%2BsVb5Wir%2BhkL8bTP%2BgUD5WSn9ymv6YC37ZjG89er9dTj8cDj5Xiz9dTn5XCv7Yi39lkn%2Bdzz9yW77ajT8ajL9dDnA89%2F9hT%2F6YS37bTb9bzP7ajL%2BhUFoyPU7iNI6gMl6z%2Fas7vtFk9c9jdJoxfFMm%2BE6gMYub7w2e8ZduvBBidAxdME8hctRouU5f8Y5gcVXquMucL8%2Bhc44ecSi8f6i6f6g2fh32fkubbo2e8Y0eMMyd8Mwc8E%2BjNI5gMhHmuFnwPI6gslWqelGkNVCitBCic85gdM2fcc6gshHktUvcsA%2Fhc1Gk9o2dr5fvulJlNz4WCn4WCoubLgubbjC8FcCAAAAWHRSTlMADRhYLgG6NCb4O6FO%2FBHnxwZriex489MkZAmuqHIDRd%2BSfbZAKG6SFQlcZCNNwfvPLn3umT3IvDX4qOAOERob%2Ftfk6vO%2BtEYaojhmdoNywq1w9oxU5ziO7qeVwQAAA0tJREFUeNqkldWBg2AQhHG3GB7Xkvj6b%2BTY88ew%2F0TQWRfrPdiOZQbXM%2BP7QWgmIIoTMwPSycyFLI8LE75TUvkG%2FFUAa5MAbGBr4oGbw86AH9bQ2Hp%2BW4JJETgNRg7YFZD6cupHXbaY3wfA0IukropHe3EBDMA48%2Ft9Sb1eXEuHFPLNYU5EA42nKKCJ2vXnQqghVSRyDfVROikGsWMpkphcwu5sYVTw7ROc5SSFWjMQL9%2B8ooZRwT%2Bc4ConR2CjKeH424MOOVGEoP4noDkoJFwhkOMNyDUTNcmpi29TSC0Fzt%2BDcARijQl9xUnqN8yVJvjOiYscU6DsLQW8bd1%2BrjXII0uDWz34XwmZVAKkEW9fbRk72qU4ziYkE9VhSfTuj%2Bfrt6R9seCjt7LYchSIwjAjrEbZjrCKFYHGoWmoUAUMHrdzct%2F%2FPaYq7RIZ%2FVY4l18o3usbkNIbqkdbpF3oOwM9PPTm6%2FsH503L1h108H7XAwB%2FIBzjMoAr%2BcD0lg4AYXSzJ0sowqNY5YywdHeZB8Q9ML%2FDH0BCz%2FcvPI%2BGSZoFgU4YepD96N4%2FAJxDAqq93CZwD7s1S4y83yvKu6kHGUAlHAbVTTtmWJNG0VwzRk%2B%2FtwXQXeH3UW0g1nGVu%2BKxAadAxvLRJIQ67Q8LM46QxOBO4AjJNw%2BVZqC3J1bJOVdxx4W30zS1s0UQLLLUqwXOEuzVySw3NjxFpy3af57uq8JpSstLdbJ3cWHTi8rSYvHmTC2f2Sg0Uk3T7I7wYxdF4f8hyvJvvw5ZuRGuGWFoTGfVsl3Vg19anMqnLuwgoIrwC5hTHZ5gF2fFfJ5fiXsBTCsPF2S3h2T0qhmcvlsu8gDW7v0%2BVjeFphUbFT8WAKOXKzQlAF55%2Bj1K%2BmKWVwEPnnZcbKSu%2BlSvXpxgvpdNN5x5oUaS%2BDAPCI%2B67mq%2BnBkpIYlzeSA3l0sjAA4TLaGen3PYr5GGaaYzOQFIkrc1OpY97A75axYEHkF0m%2Bb9SRFL%2FKJ41Z%2BG26MqYTZw01pjRttTNLc7QCI%2FHqlFz%2BFj0kYSTiFh1saNy2xcKewf269yI%2BGTkcxwitO3z70k03cPCVI6nfXblYnPapgcu6thb8LoDZVVUXdHkXTI4J%2BBCs8ToaFwLgAAAABJRU5ErkJggg%3D%3D

[javascript]: https://img.shields.io/badge/JavaScript-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACgAAAAyCAMAAAAZbWmiAAABj1BMVEUAAADWujLbwkvYvTrYvjzTuDHZwEPWujHUuDHWujLWujHWujLXvDXWuzTWujLXuzXWujHXvDjWujLWujLWujLWujLWujHWujLWujLWujLWujLWujHWujLWujHVujTWujHWujLWujHWujHWujHWujHWujHWujLWujLWujLWujLVujHYvj3XuzTWujLWujL%2F%2F%2F%2F%2F2j7%2F%2Fvv%2F2kDVuTHs7vf%2F2DLVuS%2F%2F%2F%2F3j2KT40zHVtynr7O3%2F6ozp59vWujPXvDzr6%2Bn10jvUtyf31Dv%2F2Tb%2F2jv%2F8rr%2F5Xj%2F3D751T3dwDTs7fTUtiX%2F4WX%2F3Un82D3k2qvwzznXuzX%2F1y%2F%2F%2FO7%2F6IX%2F5nvcyWnaxFXryzjYvDLtyzDzzy7%2F99X%2F9cz%2F7qn%2B5HP%2F4GD%2F4Vr%2F31b%2F3ELXvkDmxjbhwjTavTPnxzLu8v%2F%2F%2FPP%2B%2BeT%2F9ML%2B8LL%2F5W%2Fdym%2F%2F4mf%2F42PZwlH%2F3k7%2F%2BuXq6eP%2B%2BN%2Fp6N%2Fo5dXo48%2F%2F7J3i1pzh1Zr%2F7Jfg0Yr%2B6Inezn%2F%2F6H3bxmH61DHAZCJOAAAALnRSTlMA%2FAIEjfwF%2Ff34meuLCHFWTT0zKiAR4NrQyb5fGAz98eW1qaGEfEhBOtSumGNoHFp97QAAA3FJREFUeNqN1QV78zYUBWA5XrDMzNxuV0lDxZDtMjMzfwxjhh%2B%2BI9%2BA%2B9SDU25ek3SkiP%2BfmrEv%2FjNjVYBfkkb%2FEY3KAYcoqP1HglQJWEsvEn0enLENsF574TaNrDNLAaoGbO9ymqj6trgQdmQBsAawopv89DxG2Jn1hyjVCWTECVNI1AiPlxJeP4oG64XwiBbH%2BERzudwUGVa8FGuRqKxBCF30OODW%2Fv77g4RxvTdfyN61oVFjhYJ9JZhIfxN72shNzsiI5CTlHyed1CyE8IlyJ5zNLE9MKZjkROS7Ey%2B1Cg%2FgAMMow%2BkYQ5mM2JEfj700KnRAx2Q7Yf7KkSvAEJhPVLnDszk7b9cevdQPpqMVfuKknPBqO24nfOelSkCPaoUb%2FGDmB%2FzeS202rA%2BS26VXzfGwHbsTOmBD2X%2FCYTCPqGgkzR2qcCfAkOao3w3Gzfj2dtxSnWgHxGdrYcSfw%2FHLi5nzs5nJFDrBcBTw5VN%2FvZOU%2BPHLZCc1%2BQSii5DbPUKpWZS76ESL8HArXGESDJ3YszvBsNIFAvFcv8NU9wrdvnSbG5Ty1ekcvqvyhPKwWsFUCeYmd1%2B%2FnfnwOb4WQXnsTjCsUSSXwLJiuLJ4Y8W3Tcu8TMpXnwErbegRdXC3%2B%2BlcLkF5GFbL8Ma8lHJnDZ2oYohWpKYOlmc33t%2BuJBjCYSGau1K%2BHsdUDzJEK1JTnzLTseXvNn6fzSgItXZx%2Fm0yKU8twFogFV%2BTgsh0LJYBzC2u7c7tqMFBz82HqMadwLdmXDo2neE8W1zyzV9b0a52hjpaEbjdmF2GLUFEjfc5OtHdUYC9pCVy6f2J75djy4V1LdGI0x9Xb7IaNeFRSq1IJXK5rT9%2F%2FmGad4rkzpvfrq1tM5wNqE7YZ%2FSJftKiRCnYldTBT79OTe7NXaxheDBKC5te6hF8Sr3UitRWdGolYe9mFlYBsnDopT6GjlawVRuprZB1BcuLcJCh2467gOU%2FIHx5OOwOF8Lrm3dHQfqKoQet8JOm%2BZ1QqcXN%2B6OAN6BFuROQoiNURgUb5XcF43CJvN4A%2FtHVUw%2BCMK0ONRICC7ppK3U7Zb1V7TyKDNWpK4ZCTUTk1zSKsuruq1YLWmfH0qPbdrh8hPJpDA12qCcFA3RQAYv%2F6LUDLUF%2Fc3lNBSuEnUOq8%2FrUf2trcHo%2BThTZ3wXJNxi0L3gjAAAAAElFTkSuQmCC

[julia]: https://img.shields.io/badge/julia-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADwAAAApCAYAAABp50paAAAG%2FUlEQVR42tyUA3RjaRiGv7F1MHY0NWLc9CZFaic1grpd27a3ccY2k7W9YRmtbVv%2F%2FnecLLPevOc84dVzPsD%2FJRnbAETWlWO4ZuZMnom%2BXGCmTxVekw5xGb6JCZI7kiaILYk3F6wTflu%2BiUSKtfyPROaEXoEpcQzEWwQmFghNrKtU2xRIvbsSte6uOPxevkmGhGZWeYo1GeIqhIE%2BFlf0DUo0Gqk15R6qA%2BIqfCNzVtF6yQfRsuo9lUi2Ot0tiDdhjpkFWbY0V8vu8gjhxp0lSGxONMVdhSV3sEBgZIgL1gk%2Ba9pVilp2lR%2BWzVnNfp1vpC%2BaKZwJfzpZOj%2BQmgBINYGphNo%2FH79Pl7WPgrTVD391mEzmYWg0GixZsmQMBrzSdHiS4MOz4vRZzwrT5r8InAmpFkYSXlKrSVvaY0Iz82aaFeYbKg9N7a%2FZP%2F9O1cFp%2FfUHQV97EGLOKtkdUGrzAanzNxT3hkaqzgh%2FVtIXCpG6wKmLLAjI1hH4s1m5ciXQ6fTDkgwGYwFGgbFgyvAXcBLsCa4s3tXeouyXvWWKT90Kqcspysy%2B4JpEwLJQ0l8BhtqDGqvG4V%2Fbec9nVq0jgGU71jc4xtypOgQxRdbwAmC5QuVZYdR%2BxYuoA0O91537HMrS%2BDtk2j9fZSxGocQ8hnkXgyhwpdst7DRwSrnXDtZVohFtIxrRNaERTQPyluR%2B6SLYafr6Q9Bfc0C5vve%2B73ec%2Fwg6xobe%2B5C%2B7kCjXmmPUVjnH6PoDN5NSZ5MGwZXPCiqeO0vaWMsuPGY6MnCoVzReE9xzleUbATqeuQiOBZnLgmWVscT28%2BjRCOxqO1P3aHaPwFiCZ7XsYU9waGOKynRSCpOC78p0wVn%2FEXCG35O2EewF%2FgqCw9LRuOSC%2B%2BBs9B4m84RiJTFXPAIsunuev5O1YHpEEvkuMK5HYEdusujKoy%2FF3SH3PL2Yfg7hSG1CTwF5PvRskMttcgpzrzhYNm1YG6237393IcjhKmKm1vs9%2FUr7eNiE9YGgNQG0spPC3%2BiveyIrA6%2F4%2BX1BaEOKGS6wN8qfGFKIjglbO1AVfEP1OxSssNY1pNPvuaUcOffXuuAfuV%2BwZqOuz%2FZdlSakl%2FTcc8XeGNL%2B1UHIKbMXlIA2VhKqglm5HUG9%2BINPajoCt4t1fhJuSYMOH%2BrMAaGhKvAKc6ocudKHvEUyAZcpGC9i8hc%2FqSQDVT6Gw7Anar9fHOT%2FSDe1IO44vZ%2B1X7x7Uo76JU7IOZwuTdBtjoAWZoQ5PS8Mz4z5zagL4Vp%2BKEmy%2BVy6oGjoQR%2BbhP%2F3HG%2FKfwMkQHPEpnwGJ8DCCF4lpcMS2i0OXBSDLX74eqKtUBlX7sL5v3YjTnA2tVEUfg827Zt2zbi339t240a1whqm3Ft27bt9nFNum9zMplnnnuSL3PvXoO93hvd42Fqg7bOOO6sVePjc%2FMM0xnJEvNHw0FgF3iB78Hp6emss%2Flgi4xtwENgeDTYytXLbsow%2FVEsQCU%2BLwGP8Xm0LD%2BmmyM%2BDBwAr8BH8Al8AC%2FBHtDD3d1d29LSsknDBqh8CtTIEvqBQUJSUlJYQjdZjCNCYHiToF6vZhieDKpArUyb8Gv2xbD8ejBj8tzACXBD3oa4gPr2%2BAc2aphN3%2FvUoFMN%2B%2Fn5MW2OQJtAff7DaT%2BhRdEUZvo4gekdQFOJhnXBGU67BuS5a%2BP7d7494laKMwx02FLjtJ3Ilx%2F3sWDcEMUZJi0PvKb4W5Du7%2B%2F%2F%2B0cJjXtfnJ%2FCDAMpIiKC6SbI0YWVLMba0KkSiNhE8FktDPOXF6prC0bzO7R6GCajAQEBrI4jmAV%2ByupVgyPgvdpMaXppUArecnXuQS9TuzUMUlkunH4W2AGJeNBuhrOyslpieGN7GkZeOmzKcloViKCzuP0N023mqqDDRNxbJfawaRcYGKiJ2IF2vnhYgBpO%2B4pjSY9Sb3%2FD1OF6QYfLgBaQqJxO8fY0bCnorwpaHHJWbWap7XosUbIZoErQ6V4wkcq6DjCs38Dsug7%2BBktBbbseS0x3c3NjSc3gdJ4v4EUH3LT%2BaWLcKqL9DEOXnJycNBDrCe4JOj8IYhrYpXuT4VUCU31JmyfQJrFxw8LC2Lj9wEtB33dBMXgi0CJbbBgEyl%2BmU3ImKJNQ9gE9QAjQYRqwAW4cxrTxWXNxd5WG0pJvh%2Fpmqk2J1qoVyAMDQH%2BQinom1N6J7xtx3ZYa%2FgbcRPVpqnGvVTr2SU5OpjEBgZOhiVa0Hulnl05wcLDKsLHA8EfU05aU%2FMAYWw9DwT0y%2BE9oaKiE0hQ85wzvA5LSDbtxpmrAnyCUizPKPDw8FG%2FYmo4Pflt%2FzcUWjRkzRtFe5W8IYmm6VnMmP4Mj4E%2BgTZuRsh8zMzOVaS3amV1RetJxYgC0gKQuTz1r56rftpKlAwAAAABJRU5ErkJggg%3D%3D
