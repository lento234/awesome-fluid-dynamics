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
- [barbagroup / CFDPython](https://github.com/barbagroup/CFDPython): A sequence of Jupyter notebooks featuring the "12 Steps to Navier-Stokes" ![python] [![jupyter]](https://github.com/barbagroup/CFDPython/search?l=jupyter-notebook)

### 1.2 Meshing
- [nschloe / optimesh](https://github.com/nschloe/optimesh): Mesh optimization, mesh smoothing. ![python]
- [nschloe / pygmsh](https://github.com/nschloe/pygmsh): Gmsh for Python ![python]
- [PyMesh / PyMesh](https://github.com/PyMesh/PyMesh): Geometry Processing Library for Python ![cpp] ![python]
- [cnr-isti-vclab / meshlab](https://github.com/cnr-isti-vclab/meshlab): The open source mesh processing system ![cpp]
- [inducer / meshpy](https://github.com/inducer/meshpy): 2D/3D simplicial mesh generator interface for Python (Triangle, TetGen, gmsh) ![cpp] ![python]
- [Gmsh](https://gmsh.info/): A three-dimensional finite element mesh generator with built-in pre- and post-processing facilities ![cpp] ![python] ![julia]
- [CGAL / cgal](https://github.com/CGAL/cgal): The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry. ![cpp]


### 1.3 Solvers
#### Finite element methods (FEM)
- [JuliaFEM / JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl): The JuliaFEM software library is a framework that allows for the distributed processing of large Finite Element Models across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. ![julia] [![jupyter]](https://github.com/JuliaFEM/JuliaFEM.jl/search?l=jupyter-notebook)
- [FEniCS / dolfinx](https://github.com/FEniCS/dolfinx): Next generation FEniCS problem solving environment ![cpp] ![python] 
- [deal.II](https://dealii.org/): An open source finite element library ![cpp]

#### Finite volume methods (FVM)
- [OpenFOAM / OpenFOAM-dev](https://github.com/OpenFOAM/OpenFOAM-dev): OpenFOAM is a free, open source computational fluid dynamics (CFD) software package released by the OpenFOAM Foundation. ![cpp]
- [su2code / SU2](https://github.com/su2code/SU2): SU2: An Open-Source Suite for Multiphysics Simulation and Design  ![cpp] ![python]

#### Spectral methods

- [DedalusProject / dedalus](https://github.com/DedalusProject/dedalus):  A flexible framework for solving PDEs with modern spectral methods. ![python] [![jupyter]](https://github.com/DedalusProject/dedalus/search?l=jupyter-notebook)
- [FourierFlows / FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl): Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains ![julia]
- [Nek5000 / Nek5000](https://github.com/Nek5000/Nek5000): NEK5000 is an spectral element CFD code developed at the Mathematics and Computer Science Division of Argonne National Laboratory. ![fortran]
- [spectralDNS / shenfun](https://github.com/spectralDNS/shenfun): High performance computational platform in Python for the spectral Galerkin method ![python] [![jupyter]](https://github.com/spectralDNS/shenfun/search?l=jupyter-notebook)

#### Others

- [aromanro / LatticeBoltzmann](https://github.com/aromanro/LatticeBoltzmann): A 2D Lattice Boltzmann program ![cpp]
- [jostbr / shallow-water](https://github.com/jostbr/shallow-water): Python model solving the shallow water equations (linear momentum, nonlinear continuity) ![python]
- [PavelDoGreat / WebGL-Fluid-Simulation](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation): Play with fluids in your browser (works even on mobile) ![javascript]

## 2. Experimental fluid dynamics 

### 2.1 PIV / PTV

- [JHU-NI-LAB / OpenLPT_Shake-The-Box](https://github.com/JHU-NI-LAB/OpenLPT_Shake-The-Box): Open-source C++ code for Shake-the-box, particle tracking algorithm ![cpp] ![matlab]
- [OpenPTV / openptv](https://github.com/openptv/openptv) OpenPTV - open source 3D-PTV software ![cpp]
- [OpenPIV / openpiv-python](https://github.com/openpiv/openpiv-python): OpenPIV consists in a Python and Cython modules for scripting and executing the analysis of a set of PIV image pairs. ![python] [![jupyter]](https://github.com/OpenPIV/openpiv-python/search?l=jupyter-notebook)
- [OpenPTV / pyptv](https://github.com/openptv/pyptv) Python GUI for OpenPTV - open source three-dimensional particle tracking velocimetry ![python]

### 2.2 Machine learning / AI

- [erizmr / UnLiteFlowNet-PIV](https://github.com/erizmr/UnLiteFlowNet-PIV): Unsupervised learning of Particle Image Velocimetry. (ISC 2020) ![python]
- [shengzesnail / PIV-LiteFlowNet-en](https://github.com/shengzesnail/PIV-LiteFlowNet-en): Particle image velocimetry via a deep neural network (LiteFlowNet) ![cpp] ![python] ![matlab]
- [yongleex / PIV-DCNN](https://github.com/yongleex/PIV-DCNN): Perform PIV image pair match using deep conv neural network ![matlab] ![cpp]


## 3. Visualization, analysis and post-processing

### 3.1 2D plotting

- [matplotlib / matplotlib](https://github.com/matplotlib/matplotlib): matplotlib: plotting with Python ![python]
- [scikit-image / scikit-image](https://github.com/scikit-image/scikit-image): Image processing in Python ![python]

### 3.2 3D plotting

- [K3D-tools / K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter): K3D lets you create 3D plots backed by WebGL with high-level API (surfaces, isosurfaces, voxels, mesh, cloud points, vtk objects, volume renderer, colormaps, etc). ![python] ![javascript] [![jupyter]](https://github.com/K3D-tools/K3D-jupyter/search?l=jupyter-notebook)
- [sciapp / gr](https://github.com/sciapp/gr): GR framework: a graphics library for visualisation applications ![cpp] ![python]
- [QuantStack / ipygany](https://github.com/QuantStack/ipygany):  3-D Scientific Visualization in the Jupyter Notebook ![python] [![jupyter]](https://github.com/QuantStack/ipygany/search?l=jupyter-notebook)
- [InsightSoftwareConsortium / itkwidgets](https://github.com/InsightSoftwareConsortium/itkwidgets):  Interactive Jupyter widgets to visualize images, point sets, and meshes in 2D and 3D ![python] ![javascript] [![jupyter]](https://github.com/InsightSoftwareConsortium/itkwidgets/search?l=jupyter-notebook)
- [NVIDIA / ipyparaview](https://github.com/NVIDIA/ipyparaview):  iPython widget for server-side ParaView rendering in Jupyter. ![python] ![javascript] [![jupyter]](https://github.com/NVIDIA/ipyparaview/search?l=jupyter-notebook)
- [Kitware / Vtk](https://gitlab.kitware.com/vtk/vtk): Visualization Toolkit ![cpp]
- [Kitware / paraview](https://www.paraview.org/): An open-source, multi-platform data analysis and visualization application. ![python]

### 3.3 Analysis

- [numpy / numpy](https://github.com/numpy/numpy): The fundamental package for scientific computing with Python. ![python]
- [mathLab / PyDMD](https://github.com/mathLab/PyDMD):  Python Dynamic Mode Decomposition ![python] [![jupyter]](https://github.com/mathLab/PyDMD/search?l=jupyter-notebook)

## 4. Benchmarks and datasets

### Dataset

- [shengzesnail / PIV_dataset](https://github.com/shengzesnail/PIV_dataset):  PIV dataset ![matlab]
- [idies / pyJHTDB](https://github.com/idies/pyJHTDB):  Python wrapper for the Johns Hopkins turbulence database library ![python] [![jupyter]](https://github.com/idies/pyJHTDB/search?l=jupyter-notebook)

### Benchmark

## Related

- [alexlib / awesome_piv](https://github.com/alexlib/awesome_piv); A curated list of repositories related to PIV (particle image velocimetry). ![Awesome](https://awesome.re/badge-flat.svg)
- [nschloe / awesome-scientific-computing](https://github.com/nschloe/awesome-scientific-computing): Curated list of awesome software for numerical analysis and scientific computing. ![Awesome](https://awesome.re/badge-flat.svg)
- [qd-cae / awesome-CAE](https://github.com/qd-cae/awesome-CAE): A curated list of awesome CAE frameworks, libraries and software. ![Awesome](https://awesome.re/badge-flat.svg)
<!--- custom badges -->

[cpp]: https://img.shields.io/badge/C/C++-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAADIAAAA4CAYAAAC%2FpKvXAAAG50lEQVR42tWYA3gkTRPH%2B7VtfrZtxznbTvLaPE6cnH1ZnG3b%2B8VeXWzvZsO16q3t57yYmUXwf55%2FMD3bXb%2FuqppJSKA0RySLiBLKzqO7r%2Fuc4xoZLIoSFv8wSig9joGDKyPMhdli6c%2FJQNXb62XPYKApaBMaWGyJFsgEMzcVvkAGihgG7p0jkk7D4NrQwNMaPL0PGeby%2FaQ%2FhQD%2FxWCkaPDRJf1SP7PFyu9HiWT7aBD%2B9fmYNOVPSaA1dZv0sWiBlMEFjWgIkM140quiBflPBawO8PhbAgbg3N3aHfUzdt%2B%2B%2B4g%2FhCfwJ5w4Cw39YexuhTFpsn%2F6Usiv445sw8nsaOh%2FS49jTN%2FhcQL5j16vAz0aBphNjvp5f3XFk8StAO7BYxyLN9f5sliMSA4Jhypg85UGOFbQBmelajgjVcHh3FbYhNeY%2FeX0Hh%2BBmrCGoh21e9cpyL%2BHg9m%2BTL70eBVklXeC3mQFNmmNVvh%2FiQZSj1X5CpQ1a5Psu9drQf6SL91oCQJUq3TgrcqatZBytNKn06GvOlFC%2BTpvJnh3kwIkuKt28F12nOSivJ3OyTMOfViy5MojM7ctJQ4ivhCf7yiBhnYD%2BFn0ZD%2Fdfo1TDONW5mY%2BMWt7I5koBnQT8QZC1WOCQEnVbYJPd7iHmbGhuOSN9w9IKcDt5gPx3mYFNGoMEGjVqvV0rbue9Jq%2FLjp39Z5JYisN3AcQ2pX6SLSr3Xj3ilySfvXBqZu7nQG8AFl1ugb4SqM1Q2WrDmpUetAarPwaAJo5UKJ4evaOOg8A%2FECiRTJo7jQCFxktNjhZ1Abz9pY5zbMAr12Qq8FotoEn4VqmGHFWGTsAT5D152q55Tbu%2FJc7S1jnm49ADS5qrddgsQvOV1Q8MGWThQbnbxBpXQ%2Bn1snjOUDvrb%2Fewq02O1xWqhtffWd3Bw3KG3PoVHQhT8LXEtqW%2BbbyuXtKcZO6O%2F8Zd4qtDnwHWcmhyI%2FktfKGmJVWXPPzz45n%2BgbAA%2BRATgtrd%2FliJ4%2FTEMi6%2Fhl78cp9UzYZ3QX14NRNcFHRBMKLpU5jz8zZTsdWnFLwA7mibAdPauowcIWwjV6Rnf7otG1qtt19ZPpmQGHaaZzGXn57Jx2TlLTwA8mu6ARPUtT3sEJMWZdf9ELMHk7tNK9KjZujA4csVhv9Oe1CCR0rbe6Clk49HTNZ6Bi%2Bfcu4geSwgMg9gMwWFDf9%2Bv096SQkMYeMTeNS0DTYXoMZHLLZ7fTnbZIKxxgNXGu03Oh0dGztWSXH1LqmAU9q1LhMLW3QglNX7gtNNJCgOLhuM4lIuUomCLv7JbUOshW7HeCzW2%2Br9tFL0tMfG7qkjQbvysFxGjJs2VVc3OoO5KFpmyG%2FWg27Miqdxp6L2k7HsBHwA1nN3n5pZ5uxrkjx2uQNcrcATkAJJWT02uI%2Ba7%2Fvb1GAjeWBiHlreWHMUjsNkIffmLgS9ktK1N99f1dzoEGoFQ09wCaJrA4eDEvkDPFQeCJklzSCQ3ojFu3xgtrHpm3WBhREcKEOUJxgXhyzjBXizUmrKMTdatb0Wt9Nu1iKfzzZAgFC%2Fw%2FV1mUELursNcBX4ovwyrjlLlMpfocEND168KSCihb9PxccrvA7yByBtJXZk68E7qLPAGWtCk7lVMCFwmqobumkvZ%2FP5%2F%2F%2B8TYpGS9o8geIKTLx0tUHw5J7HDu676oS%2Bko7LshunKSORCy%2BQiaI9F6BTFqZk%2FvUyOX1t6fGU8NTobS%2BHQIteU2bY6272nV8Mxm%2BMh2DtnMCmbm%2BqPRbU4XF7gr125NXQ6O6BwKlelU3rSV36yPQNTJ6fZkrkFZaB0KZ5q9fHLl6T3Ccla3rfGvyKiipV4O%2FJa1qhdevQ7DYRsKS08l4oeo6SAuZkybdQOsgPKmbz8PsiWEpNI%2F9pY2ni%2BicPB%2BqWlo%2FkzauJeS%2FCa%2FhBTUavHHY1ztpTnurgvJmCP1qJ53LS6tIMPMqofof81MSFC%2F3djJMRxgyfzccSi8Bg8kCbNIazLD7koJuAn7WewiMmcZ%2BhxjmXhychm5Dg7d%2BOCIJ%2Fv3pVnh39SlYuj8LBCcKqJN3p8M7eO0vH2yCRyKTfAieugOL%2FkPyb%2BZ%2B4laRyc%2BQoNgUvNmEhgFmC1pAwpNeIJz1P%2BaH%2BKETAwjiAvoXxGsFxQeR4DhFPwKUk%2BDYscQv%2Bp3gAZqTQXGdfQjQiynOkPDVDxG%2FK5R5Fk9nFS5iDSCADbNgG%2Flf4ksk0MKFfoILng4AxGUSGvcr0ucKiR2Ki1f5AaCetv5%2B1Vjmwev10%2B0FgJbWwb%2BZh8mAUWjiK7THc6sfO6bnPhLEvEkGrP7L%2FBYDlXiAyCX%2Fi%2FsLGRyCezDYCY6g0Rbq4NgcxzU6FgB9A0T9f5VBrS%2FNAAAAAElFTkSuQmCC

[fortran]: https://img.shields.io/badge/FORTRAN-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAMgAAADICAYAAACtWK6eAAANoElEQVR42u2dBXjbSPrG9cdjZmamB46ZubLT3fIy825sBcrcpXIi2SlzsCk3nHIbTpkxzMzgOX0%2BzG2dC0kzst73eX5bdjzf6hd5NCSZkZecnk8rTu0lxaEecDm0O26H1q3DhgkAHW5Zu%2BF2eI64ndrC0BDtZxMmJPyPZNW4HN4%2F6g06qDes36CCAVCiM0MJ8XzQOmI4o3%2Blv%2BlTJhYJgFaX7Jmr%2FPb1twkrRsS4mE%2B6HGoyxyIBUK44PCFCiTFv3rz%2FdjvUUP3NtYlQJAAUWdsa%2BSftPQL0M9RPuJ1alpCFAuifjFO%2Fw00O3dI%2F6W%2BiQdQCAeByaO2KQ5tqshrsv%2FQvGmGRp1MA%2BBSnOs8UNUInLH%2BLFTviALhkbQV9czdQjnXvdcvaMRQbWFiSdYZIEvpnz8f0L3AZRQbW75eoq8ZUDvf46E%2FRED%2BKC4IFRVYXjN1jXId2G0UNNoDi0B4elRzTQ6Lfp7%2FIRRQzSAE9Lln9xchGx8fFvFV%2FgRwUMcgB1dS%2FHvY4h%2F4PY1E8mwBOPPFEzP8NWQ8aBETRbAVwaguHJEeY7PmR%2Fg%2F6UDSbAXpDnZ7vDirHMxPUt%2Bt%2F8TqKZUcAPZCaNyHh%2FwOPdzg8KgplczBNPuzu4x0h3m%2Fho5UGQEu4HPXRN949nGq60V98x%2FJMdvr49VEBQFREsrFTUZxq1AA5aHcIM%2BzMTi5iCDLabF2abvS12jVgbMTt1HZCEASCDFho9YpEoc9b1PeAIAgEGUClf%2FBQcaqPvuEPIQgCQRjt66YLoiVAEASC3AWnZ6Wk%2F%2BQCBEEgyF0pIkEaIQgCQe5KAwnCIAgCQe4OBEEgCARBIAgEQSAIBEEQCIIgEGQMgkAQCIIgEARBIMjSF%2BPZ9uUZLFE9PCjJa46y%2FZtP%2BUmPL2AnUy%2Bwczk3WdmNWtbb3cdETvnNWrbltTRDSBi8XnclI6GAZe8s8tcwN%2BOif8HR%2Bdxb7OaFClZ5p541N7RzqykEMYCwEA9bpot2YGsOqyptYKLlUuEdSy41nTV1PVv6Qjxbv%2FCAX7ictAus5FoN6%2B3pgyBWRXF6WOzKLNbV2QNBDGL6pLVs45IUlp91me40EMSKREUms76%2BfghiMHPv38gyEwtJFAhiNU6mnIcgJrH4iW3Uh4EgVmLDkhQIYiJh473s0K5iCGIVPLP3QBAO7N1wAoJYgVVhOyEIJ9Ji8yGI6Lz%2BfBwE4Ujx0WsQRGQWP74VgnBkxuS1rLaiCYKIyvyHN0MQzmgzdjOfD4IIyZz7N0AQASg4dAWCiMjMKesgiAAsemwrTU%2BBIKIROXENBBGEEwfPQRDRCB%2FvhSACjbT39%2FsgiGj4fBBEFC7k3YIggkETFiGIGND6FQgiGj1dvRBEnD4hLUOAICLR2d4tkCCg8PBVCCISbc2dAgkC1i86CEFEorm%2BTSBBQPg9XvqYBUFEobG21baC3Lw4ugVMPp%2FPkPd1pbgUgohCfXWLbQVpaewQUpCUbbkQRBTqKpttKQjNpKWIKEh05C4IIgo15Y22FGS5K1FYQagfQo%2FfIQh%2FaJ8sOwpCg3LCCkJcO1sGQQSAdgq0pSAp23OFFuTw7tMQRATKb9XZUpD87MtCCxK3OhuCiEDZ9RpbCnL7cpXQgqxUkiCICJRcs6UgNINAaEFo%2B1J6fQjCF%2FpOajtBZk1bzygiC0LUVTVDEN7culRpO0HUGbstIQitD4EgnLlxvtx2guz0HrWEICPfphSCcHzebn1B8jIvWUKQXWuPQRDeXD1TajtB6quaLSHIxpdTIAhvLheV2EqQhY9tYRQrCLLSnQhBOEMXp60E2b3uuGUEmfvARgjCmwv5t%2B0kCB1iYxlBFKdGJ1NBEJ6cz7lpG0GWPLmNLmrxBQmwHAGCcODMyRviC8LtsSl%2FQa6fL4cgHKEzwG0hCI2ed7R2WU4Q%2Bv8DQYQ%2FxMX6ghxK9t89LCfI8f3nIIjYW%2B9bX5DXnoulzq4lBUndngtBOEKH3Qe1IBH3xrDSgFP6xRckSTsMQThC0y6CVhDF6TG0j2WGIBuXpEAQnuSkXQhGQahTHmCMx1qC0EnEEIQjJ1ODS5AFj2xmB7fmsNamDkaxuiB0TB4EEfZkI%2FEFoTvFuoUHWFZSEa1tCTAQaF1BiI62LgjCi2P7zwovCHW05z%2B0iUVP38Xio7JZVmIhO3PiOu3IYoIQ%2FAWJikhm3jl72dr5%2B2m7ogHQ5g6J6uF%2FQGtd9m8%2BNYCM%2BAK27MV4CDISju49wziHjmCgJ00DoP26mhvaWU93LxMkgQUB%2FAXhsP8SAkEgSHZyEUMgCAQJAH2eRyAIBAkAdeAQCAJBApAOQSDIIECQuHyGQBAIEoC0WAgCQQYBguQxBIJAkACk7oAgEASCjOggGQSCQJBtEASCQJCA0NRwBIJAkAAcgCAQZBAgyJZTDIEgECQAtF4AgSCBgCCbIAgEgSAB2bfxJOOdiwV3aCUcTXuhTST8R4%2BVXK1mzfVtrL%2FfB0EgCD%2F2bjjBeIeW%2FQZ6f2HjvfpGDFto2SktMfWP29BukGU3amkzuKAXBIJAENo4YkTvPfweL4nj%2F5h49XTp2N9tIAgE2bOevyCn0i6MSVvmPbTJL3xTXRsEgSCcTlwyILkZF8e0TZET1%2FjHd%2Fp6%2B60vCASBIHlZl4zZLicymbU0tEMQCGL8UcMGhnaYN6x9tB9UV2cPBBkZECR5zVHGO0VHrhrZRtpV0LqCQBAIUnzsmuHtvFJcCkEgyPChATreoXMSDd8lXUmCICMAgniOMN45l3PTlLaW36qDIBBkeCTxF4Smlgi6OAyCQBDtsBBzscxo69IX4yEIBBkeiSp%2FQa4Ul5jWXpoACUEgyJBJEECQq2dKBT0XHoJAkOhDjHeunysXc%2BYABIEg8VH8Bbl5ocK09q50J0KQ4QBBshnv0NmCZrWX1pcMeeoJBIEgcav4C3LnarWpbb52pgyCDA0IErsqi3EOnUko6LFzEASCrOQvSPnNWnPvmquzIcjQgCA7VmQy3qm4XRf4PXKdlwVBIMhy%2FoLQkc9mtnnGpLX6xQ1BIIhFPmLVlDWa3u6GmhYIAkGsIUhdZbPp7ab5XxAEgljiMW99dYvp7T5%2B4BwEgSDWGChsrG0Vf9NuCAJBeKW5oV388R8IgsmKvNLa1GF6uze%2BnAJBIIg1pru3t3Sa3u6YuXshCASxxorCjrYu09vtnQ1BIIhF1qR3dfRAkEBAEOxq0tPda3q7X38%2BjlYXjhYIEeyCJMccZZxDm0wLWh%2BAvXnXHGO809%2BPjyrig82ruUZx4sKCIDhhKmDCQjzi1QdAEDpoRoDQcWri1QdAkLTYfCZA6FQo8eoDIEhmYiETITOnrBOvPgCCHNpVzETI3Ac2ilcfAEGO7TvLRMjix7eKVx8AQU6mXmAi5LVnY8WrD4AgdMKsCFnhShSvPgCCnM%2B9xURIdOQu8eoDIMiti5VMhMTM3SdefQAEoT2pRMiGJSni1QdAEFruKkBoh0exagMgSOSENbTDoBDZt%2BmkWPUBEIQerYqSo3vPiFUfAEHWLzrIRMmN8%2BW4uCAIppkESm9PH5tz%2FwYxagMgSPh4L2uqa2Ui5dj%2Bs2LUB0CQ9PgCJlp8PkYb2fGrC4AgMyavpSPI6GIUNnmZl9iSJ7cZXw8AQWZNW89Whe30nw9O29TQHlRWSdmNWnbi4Dn%2FxhK0E%2BLCx7Zg7ToECXx8MXVi6TsrTezzztnLNr%2BSSuec%2B8cQspKK2Km0C%2BzMiev%2BJ0I15Y3%2B%2FaaCLdSm%2BqpmdvtylX8eWU76RZYRX%2BDffGLr0nR%2FXegbwtIX4tmSJ7ax2dPWs4h7Y4L1YoQgabF5rLuzhyGj31qoo7WL7d98KpguRgiSnVzExi4I3W0C1BpAECR9EEEABIEgcfmBag0gCJIWO4ggAIJAkLxAtQYQBEndMSJBAASBIACCQJDtubiITRCkF4JYMylmCAJBPKUQxKKCbDNYENBDgmRCEGvm4NYcXMTGUiEpshYGQayZA4YKAlxOT6EU9mfvF%2FRf%2BCCIBQXZYuRkRaDImiZR9F9kQBDrxdjZvEBxaFMlikvWZAgCQcAAel%2BU135I%2Bnv03zgFQSwmyCbDBAGytk%2F61ygO7ddGf9EFj2ymFYRjBJj30CZcyMZ10O%2BR%2Fj36H%2ByyfXEAcGpX5%2F183v%2B%2BQZBwOeqj%2Bl9osnNxAHDJ2n1SoLgc2rM2Lg4AZyZMSPgfKXDYf1EHxYaFAaBfCfH%2BQPpPocdb%2Bl%2ButllxAFgtDTVhsudH%2Bj%2FotklhADg3b1zMW6XhRHFqL9mgMAC0vRSifkUaSVyyti6ICwNAv3%2FMY6ShHr3%2BAruDszgAqKHSaPPMBPXt%2BovlBlVhAJDVpdJYJWJCzLvcTi0vOIoDgGe5NNYJnbDuvfqLF1m6MADInlclo%2FKSc8W7dfuOWLAwAPS5ndrzktGZ9%2FONb3Y51GQLFQaAJkXW%2FiSZF%2FZfikOLoMdkghcGgKJQWf28xCNuh3qv%2FgZahSwMwBiHQ11Fn3gknlHGRX0G%2FRIgGNddsvoLSZTQgKIuSaTLobVzLAoATW6nGu6%2Fa4iY8PGrP66%2FyS3omwCzxdB5zT0u5v2SFRI6LvprblmLwR0FGL25m1tWXwyX179DsmIi%2F6S9R5E9k91ObZPeoPM6jSMoBAA%2BnWqdczqxisPzQrisfUkyOH8Bt7Aqix%2FlNoYAAAAASUVORK5CYII%3D


[imagej]: https://img.shields.io/badge/ImageJ-white.svg


[Java]: https://img.shields.io/badge/Java-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAABFFBMVEUAAAD%2BvGH%2BuWT9ezz%2BjEO968n8aDH%2Bi0b%2BsVb5Wir%2BhkL8bTP%2BgUD5WSn9ymv6YC37ZjG89er9dTj8cDj5Xiz9dTn5XCv7Yi39lkn%2Bdzz9yW77ajT8ajL9dDnA89%2F9hT%2F6YS37bTb9bzP7ajL%2BhUFoyPU7iNI6gMl6z%2Fas7vtFk9c9jdJoxfFMm%2BE6gMYub7w2e8ZduvBBidAxdME8hctRouU5f8Y5gcVXquMucL8%2Bhc44ecSi8f6i6f6g2fh32fkubbo2e8Y0eMMyd8Mwc8E%2BjNI5gMhHmuFnwPI6gslWqelGkNVCitBCic85gdM2fcc6gshHktUvcsA%2Fhc1Gk9o2dr5fvulJlNz4WCn4WCoubLgubbjC8FcCAAAAWHRSTlMADRhYLgG6NCb4O6FO%2FBHnxwZriex489MkZAmuqHIDRd%2BSfbZAKG6SFQlcZCNNwfvPLn3umT3IvDX4qOAOERob%2Ftfk6vO%2BtEYaojhmdoNywq1w9oxU5ziO7qeVwQAAA0tJREFUeNqkldWBg2AQhHG3GB7Xkvj6b%2BTY88ew%2F0TQWRfrPdiOZQbXM%2BP7QWgmIIoTMwPSycyFLI8LE75TUvkG%2FFUAa5MAbGBr4oGbw86AH9bQ2Hp%2BW4JJETgNRg7YFZD6cupHXbaY3wfA0IukropHe3EBDMA48%2Ft9Sb1eXEuHFPLNYU5EA42nKKCJ2vXnQqghVSRyDfVROikGsWMpkphcwu5sYVTw7ROc5SSFWjMQL9%2B8ooZRwT%2Bc4ConR2CjKeH424MOOVGEoP4noDkoJFwhkOMNyDUTNcmpi29TSC0Fzt%2BDcARijQl9xUnqN8yVJvjOiYscU6DsLQW8bd1%2BrjXII0uDWz34XwmZVAKkEW9fbRk72qU4ziYkE9VhSfTuj%2Bfrt6R9seCjt7LYchSIwjAjrEbZjrCKFYHGoWmoUAUMHrdzct%2F%2FPaYq7RIZ%2FVY4l18o3usbkNIbqkdbpF3oOwM9PPTm6%2FsH503L1h108H7XAwB%2FIBzjMoAr%2BcD0lg4AYXSzJ0sowqNY5YywdHeZB8Q9ML%2FDH0BCz%2FcvPI%2BGSZoFgU4YepD96N4%2FAJxDAqq93CZwD7s1S4y83yvKu6kHGUAlHAbVTTtmWJNG0VwzRk%2B%2FtwXQXeH3UW0g1nGVu%2BKxAadAxvLRJIQ67Q8LM46QxOBO4AjJNw%2BVZqC3J1bJOVdxx4W30zS1s0UQLLLUqwXOEuzVySw3NjxFpy3af57uq8JpSstLdbJ3cWHTi8rSYvHmTC2f2Sg0Uk3T7I7wYxdF4f8hyvJvvw5ZuRGuGWFoTGfVsl3Vg19anMqnLuwgoIrwC5hTHZ5gF2fFfJ5fiXsBTCsPF2S3h2T0qhmcvlsu8gDW7v0%2BVjeFphUbFT8WAKOXKzQlAF55%2Bj1K%2BmKWVwEPnnZcbKSu%2BlSvXpxgvpdNN5x5oUaS%2BDAPCI%2B67mq%2BnBkpIYlzeSA3l0sjAA4TLaGen3PYr5GGaaYzOQFIkrc1OpY97A75axYEHkF0m%2Bb9SRFL%2FKJ41Z%2BG26MqYTZw01pjRttTNLc7QCI%2FHqlFz%2BFj0kYSTiFh1saNy2xcKewf269yI%2BGTkcxwitO3z70k03cPCVI6nfXblYnPapgcu6thb8LoDZVVUXdHkXTI4J%2BBCs8ToaFwLgAAAABJRU5ErkJggg%3D%3D

[javascript]: https://img.shields.io/badge/JavaScript-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACgAAAAyCAMAAAAZbWmiAAABj1BMVEUAAADWujLbwkvYvTrYvjzTuDHZwEPWujHUuDHWujLWujHWujLXvDXWuzTWujLXuzXWujHXvDjWujLWujLWujLWujLWujHWujLWujLWujLWujLWujHWujLWujHVujTWujHWujLWujHWujHWujHWujHWujHWujLWujLWujLWujLVujHYvj3XuzTWujLWujL%2F%2F%2F%2F%2F2j7%2F%2Fvv%2F2kDVuTHs7vf%2F2DLVuS%2F%2F%2F%2F3j2KT40zHVtynr7O3%2F6ozp59vWujPXvDzr6%2Bn10jvUtyf31Dv%2F2Tb%2F2jv%2F8rr%2F5Xj%2F3D751T3dwDTs7fTUtiX%2F4WX%2F3Un82D3k2qvwzznXuzX%2F1y%2F%2F%2FO7%2F6IX%2F5nvcyWnaxFXryzjYvDLtyzDzzy7%2F99X%2F9cz%2F7qn%2B5HP%2F4GD%2F4Vr%2F31b%2F3ELXvkDmxjbhwjTavTPnxzLu8v%2F%2F%2FPP%2B%2BeT%2F9ML%2B8LL%2F5W%2Fdym%2F%2F4mf%2F42PZwlH%2F3k7%2F%2BuXq6eP%2B%2BN%2Fp6N%2Fo5dXo48%2F%2F7J3i1pzh1Zr%2F7Jfg0Yr%2B6Inezn%2F%2F6H3bxmH61DHAZCJOAAAALnRSTlMA%2FAIEjfwF%2Ff34meuLCHFWTT0zKiAR4NrQyb5fGAz98eW1qaGEfEhBOtSumGNoHFp97QAAA3FJREFUeNqN1QV78zYUBWA5XrDMzNxuV0lDxZDtMjMzfwxjhh%2B%2BI9%2BA%2B9SDU25ek3SkiP%2BfmrEv%2FjNjVYBfkkb%2FEY3KAYcoqP1HglQJWEsvEn0enLENsF574TaNrDNLAaoGbO9ymqj6trgQdmQBsAawopv89DxG2Jn1hyjVCWTECVNI1AiPlxJeP4oG64XwiBbH%2BERzudwUGVa8FGuRqKxBCF30OODW%2Fv77g4RxvTdfyN61oVFjhYJ9JZhIfxN72shNzsiI5CTlHyed1CyE8IlyJ5zNLE9MKZjkROS7Ey%2B1Cg%2FgAMMow%2BkYQ5mM2JEfj700KnRAx2Q7Yf7KkSvAEJhPVLnDszk7b9cevdQPpqMVfuKknPBqO24nfOelSkCPaoUb%2FGDmB%2FzeS202rA%2BS26VXzfGwHbsTOmBD2X%2FCYTCPqGgkzR2qcCfAkOao3w3Gzfj2dtxSnWgHxGdrYcSfw%2FHLi5nzs5nJFDrBcBTw5VN%2FvZOU%2BPHLZCc1%2BQSii5DbPUKpWZS76ESL8HArXGESDJ3YszvBsNIFAvFcv8NU9wrdvnSbG5Ty1ekcvqvyhPKwWsFUCeYmd1%2B%2FnfnwOb4WQXnsTjCsUSSXwLJiuLJ4Y8W3Tcu8TMpXnwErbegRdXC3%2B%2BlcLkF5GFbL8Ma8lHJnDZ2oYohWpKYOlmc33t%2BuJBjCYSGau1K%2BHsdUDzJEK1JTnzLTseXvNn6fzSgItXZx%2Fm0yKU8twFogFV%2BTgsh0LJYBzC2u7c7tqMFBz82HqMadwLdmXDo2neE8W1zyzV9b0a52hjpaEbjdmF2GLUFEjfc5OtHdUYC9pCVy6f2J75djy4V1LdGI0x9Xb7IaNeFRSq1IJXK5rT9%2F%2FmGad4rkzpvfrq1tM5wNqE7YZ%2FSJftKiRCnYldTBT79OTe7NXaxheDBKC5te6hF8Sr3UitRWdGolYe9mFlYBsnDopT6GjlawVRuprZB1BcuLcJCh2467gOU%2FIHx5OOwOF8Lrm3dHQfqKoQet8JOm%2BZ1QqcXN%2B6OAN6BFuROQoiNURgUb5XcF43CJvN4A%2FtHVUw%2BCMK0ONRICC7ppK3U7Zb1V7TyKDNWpK4ZCTUTk1zSKsuruq1YLWmfH0qPbdrh8hPJpDA12qCcFA3RQAYv%2F6LUDLUF%2Fc3lNBSuEnUOq8%2FrUf2trcHo%2BThTZ3wXJNxi0L3gjAAAAAElFTkSuQmCC

[julia]: https://img.shields.io/badge/julia-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAIMAAABZCAYAAAAdOJcvAAAMnElEQVR42uybdXQiWxLGs%2B7ubsi44E4T13GCRRjsubuPrPsmg3RcdnzmD4g8d39AnAGi6%2B4a9G5ddsk4dHb3RXq6zvnGpU%2FVr%2Bt%2BVZcUrKBgggkmNvVsepfYw1on8nA2KztYH2EycgWGtIWllpKcJ6RubkLi4aCspCT3jMTDvprYR7yZ5ilgAhdZQnKaceGLOnjJ3UeKkPFEJTKdqEa1x0pReZcEA5GUkWsCQuf6j9M4FUxI3WyPlFyT2H2kGJlP77yUAI4qpGrdGJd6uBF5O%2Fc9NEwDE2IPp1Li5qA9RzMg5FTdyRokJ9fFJSTbRcNUMCH1rBkq7RImcbGpaOdhDZJ6OEk%2BufYTtEoEczxwPgU%2BIY19AVUYGk%2FvQOAdEtBN7LRKBtMVOEXYNDac2k4ZBixN%2B5aY2MP%2BHq2SwfgF7naYItLwti8KhqIOPh4925gM0gkGF0sCRcUj5KJgULdtmIcJ5ACTQRpFRRPrbQDDP3YcJiiDYDpZjfD0AcdECZNBmgXA0KJo3RBrPEXtqCjvEqdh1%2FAzPsl%2FC5M9moW8mftJMJJ%2FLusSpsx5vMOuw4WZrgCr6V1M5mgaYpKrgbd9vrBjaxJvGi%2BEAE8bVd0yhM2mxMU%2ByGSM5iEhWTxpC76Q4qZhdIxXdktQJQBQ0ilI4b0C7h4SN9vMZOpKiX0Fb8yMm25OK9xVvIK3k3CLeVpMchxE5%2Bffvzpv4a4NvVtjiTaobeFujS3yosYafpSwRpvVtjPggNEbaPkZhE2b3vXFL37xs5f7fVRQ8Iagilf4moL%2FA7%2BS%2F6hfKXjJr%2BD1vKbkmV%2BQy99DmZd9%2B97oNHjLnTqf02nwPeYy%2Bl44pO%2Frcur6TGRN3ztXVFIAAAMA8HtQsuq6yeTOW6bQ9pumUPk10RhhDSONPTKiMoc30gEADofzRTabfRPocdA8%2FHz%2Fpf4cQLDWrxQGAAQ0VCyPDVcVoeGaEhQsUyf9KkESwPijXyFoKMgTbr13q1PfN%2B7S96XJxoF4u%2F0R1OF4BLWaB5Iugy8Jv%2Fcb0J6VAsK9uOA7b55E1n2zyHFg7jyZH5hFFddNJghb5B9qW1S52oq%2FZs2aD7FYLC0UngT9BITO1aVggEKLQH8NligS4%2FVaFLLWnaeJvUY0UlOKMCgBOf%2ByiyRnrVcDBf9n696HE0dvewqduOfZ83TsrmdQO4Dh1PvSLl3frcsLgjVcQ1gjad2d07jwl5X9wCyquWEypbFG%2FkiYQyv%2BgxrQ%2BtkQB0CvglIXAJAThldFog8BCL8NlhPJkMWEi39ZjWpr%2Fg2Egq%2B98BmaTIOfhiPhz%2B22h1O48LnUc93jCGBIN9f2ly3TJ3WefrPGFv3RtpumUrjg%2BWTbN4eKHZE4eAnPKjgK7s0BQE4Y%2FHLedwNqUTxkMeKC59VIdXEa4PnlVAXrbef%2BO4cMfR1kXX%2Fs%2BN244PnVZhtMOY2%2BKewvljxhhbZIIT4e9j6YORooqfaOaQS%2B4u8VN0y9jY4wnNBq3wSF%2FfPIrkpKIGBNmPW4M6QDSn5V9t%2FBphBa%2F3zP9U9QAgHr6O1P4%2BMCNdd65UvfGWzhfSVXReepgoBleWgWwbGCCNsZCR1hCCp5m%2FzQ9sfraynDAMIGc94vF3xzoSvUelW4sMfufIYyDFju%2Bv75Q3rfvUvvFyxRsvL6aGIxMNhBhCWS1tjCu2gKQxmGYSLrFShquEKdAhh6F4yjvk8HfiHrFSirxTwYh7%2FbvBzm8TsVMDouCob9%2F%2BkMlsliOsIA7V6RgcFsWBQMwVJVHIyka6Ez6HzVh%2FRedOLuxXUGGD2hM%2FR9dckTBm%2B3Q2MPJxz7qcNQf%2B9MBgbV3unP0BGGUdmmjwIM6TH9DuqeAeRXieIA0o0LnUHrZeFj4vCtT1GHAYxmZu%2Bg62tY8oSVWCKfhFExpb97mjIM226cSsG%2BYYzW04RS8MpQBZGkCsOobjvCAL2qEn3h3H8HChuBBRPlowKbTegKiSbt4PJ8NRaMiS1FMC5a9%2BUHwQRdQW3FfiGync4wBGT8Urw7GNPl7w74OAkQ4jgA1HvhM7h0Xi1eJv3wlrzdAYzm08ht6ovD8dK0bEkrdsy8D3YN06VXR%2BOWHCOm6Z4ZBMdKAu4qOgsgaAxD1js4YRWdyAXERKMeBYvk8YBS8GO8qLrUc8CbfhiMZOLwzU%2FmHCk99QNx%2BHMRp%2FbEu5f3gso29WnCHh0DKOBOYhrV3zeDrDBCWh6aQ0aAoPqGqSTeR4BXaOU7Am%2B5EmB4miDenAEC30vAXcQYHAW4%2BCHQuGk3Gt5WijAsAaUw9DKx5fOXe46misG3ARA92Ey2WQdTvTc9gY7d8Uxm5Dx8y5Oo46pHwCf04fuJIFl3emV8TYVWG3orFPsmOAJ%2BhA1iVmpbBDxC%2BCUwmheuSWkNQzZeU24tgiPg%2BYCcl8JgLAi6AcByW2brSCFcem8VFP1VvHLGxjIr%2BLUZuMC6jnSQK%2FMlK3aEPktYogq1PSpUXDP2geyv0xuG3DFMbHl%2FUMHj49FzSLb1c%2F%2Ftc7VpH%2FkgXGML8ZYR312susQyMFwYTHI%2FDNJD8mD%2FzsBAgKfgcrlyuBq%2F6394zDfh29V%2FtXcNwLYkMfSZa9u2bXsLa%2FPbtm3btm3btm1bJ1Wpqql5uOnH6X7pqrP7%2F0yS2zd9fivpvrDxKfA96vE%2FkAt1%2BptD7h8Dj9NnZbc%2FIx988MEX6ctyEsh5dlxtX6j4WjyrIwH0K5pUAPIlpLbvu%2B%2B%2B2zKbDPQZkP0D6AccYt1DJj6F%2FFtUX%2Fh1PvRPCet4FlgCneb4%2Fzuwk%2FlRTTD9fmIm0A8fejhZx%2FnIAMLcTc%2BF2G9IhnVS26j7MxlNhrvuuise7z5iwi2A7KVkdA9JkmsgWx7YRToZgG0gxj%2BZQgoY%2FhUfsF7oOOfJQL0d94an%2FbKGZIiEb4tC7gTJZgIWwv5dGU2GBmwcUDI8%2Fvjjt%2FtlTMlwzz33XA%2B%2FzhDYOA%2BMhWxDHkp7AAdMegmadygZAkoGzC2uo2FFoL8JQ8gjyQzXV%2BNdFwO%2FzqNeSMkQQDLgeW%2BJboiVWQTeTzXwbR4lQ8DIQEtB4JKkexcsjz83qMdMJUPwyFBYqDsu1Pen1QzkLgjtXaR5ipIhWGSoJtGDz9sLfbDJ3AdKhkCQAX%2F%2FT0iGSkIfLCZ5oc1PlAwBIgN8eTOeHxPU902hD%2BYa%2BPfLgJFBVxMcwzmfit4AFlUyuE4G9ssbNEkEznlXEJCvAn%2FHKhkcJUMI38YCd9EWt8l3J3nofUsEUjI4QQbz0%2BIUFYXd4cAZuV%2BVDE6Q4cknn7wKdv4Cpsj3FJQMTpEBuu8AnYHjcv8pGZwiA%2BVHyCeFSgYnyQC5Lyi6aOCrnUBhYKmSwREyUKoc%2FDvYwN5uID%2F04nRp6RAZ8O4VyOwR2roE%2BZbeJagjZFAy4PnbeH9SaOcI2uBrNzeddDv6AYPUtX3Ac%2B7uQCoZRgv1zwHvuLsdrVHLdw380VZjE24nt7QxyD94zSky0H66QWVPGJJhs4VkWGNQ5zucIgNKOJ6flurff%2F%2F99wo3aXKRvIVkOG6g%2B7JrZKAKL5dXOPSPcHAuwGkLyRDO5yKl9f47VEIs2matbWSoJtXnRn4nlbp86j2OZmHPsM0wvT08hR7hVWC1VbEJdvxjlKptSIhSd9xxR4L3FBHsNPKki9lKhhEm9Ybva%2FpPU9Ezjx%2FsIoN3Fm2Ik3wecbrgeLot2dH%2Fp6H%2BQ4EKHNI%2BbGvU0pukcQPe70hPg7pABj74slWq71QI22fnScgcFNiRbtMesXEHkm9duZSjycC2Xgh1CkiAybQGtzxQVTYDGrctsMRaMniu9ulmOKkk7KVYPkxEuhDCxvtfgKNpIMFBupnFqn0Ggd0ngK6C7n4dUIFm0r4GXQAckoCGKN9nF5XqAmW9utgYu1WqS72g4B6o2iQr8O8uWlHRrq6HUBPkPsji43VAtbTcjEYXW3EaVw2gLV9ylQ94ISxnlEjaccR3L4TvXIt8QODldCFKhOE9h2ws5mQo72praTEnQ%2BEwLUoGAi2b1GNKBnEMXovFBY3cWHpVDB0HU49ZVCgAxPcQ9%2BMbwwYAhdGQMSn0DO2EZFiq3rWry38wlc2ahckdDcfzXsIhopZ62J4SLti%2BnEbBFB8ZZkuGCL6J1JKivcILwu5%2BBA0ZnnuSzwh2Hvuqh20p5mna4%2FjuobEC2SOcu2hL0UL%2FyuVhXzHO8dEvC4v2Dr9Ko4UCHORImMVFCfFJOrNtzgKdOK%2Ff9qLlxRdfjEaD%2Fgz0BraFyLw5wlfi98D%2Fc9HFlupBhwstJ%2Fl08HP021P4%2F%2BP0M0Ro%2BGvUO1ocLVquAOxejrNuHQybAAAAAElFTkSuQmCC

[jupyter]: https://img.shields.io/badge/Jupyter-notebook-orange?logo=Jupyter

[python]: https://img.shields.io/badge/Python-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAMAAAC6V%2B0%2FAAACClBMVEUAAABAgL83erM4ebA2eK43d603dqs3dak2dKg3c6Q5erM4ebA3d643caI3ebA3ea0AgIA3dqs3cKA3d643d603d6s3cJ44dq42dqs2dKk2dKc2cqU2cqM2bpw2ebQ3ebA3eK43d603dqs3dqk3dKg3c6U3cqQ3caI2bZr%2F2Ev%2F2Ej%2F1kf%2F1EU3erE4ebA2bJn%2F2Uj%2F0kI3eLA2a5f%2F1kb%2F0T83eK42a5T%2F1UT%2Fzz83caI4b6A4b542bpw2bps2bJk2a5c1apX80kb%2F00Q3dqs3cqM3cKH%2F31H%2F3k%2F%2F3E7%2F3Ez%2F2Ur%2F10r%2F1kf%2F1UU4dak3caL%2F4FH%2Fyzo3c6c4b6D%2F3k7%2FyTk1c6U3cJ7%2F3E7%2Fyjn%2Fxzg3caM3b543bp3%2F20z%2F00T%2F0kL%2F0UH%2F0D%2F%2Fzj%2F%2FzTz%2Fyzr%2Fyjn%2Fxzj%2F2kv%2F00P%2F0EL%2F0ED%2Fzj7%2FzDz%2F2En%2Fzj7%2FzTz%2Fyzv%2F10f%2Fzj7%2FzDP%2Fyjz%2Fyjr%2F1Ub%2F1ET%2FzDv%2FyTf%2F1UL%2F0UH%2F0ED%2Fzj7%2FzTz%2FzDz%2Fyzn%2Fyjj%2Fv0A3d603dqs3dak3dKc3c6U3cqQ3caI3cKA3b542bpw3eK42bZr%2F1kf%2F1UX%2F00Q2bJn%2F0kI3cqM2a5f%2F0UD%2F0UH%2Fzz%2F%2Fzj3%2F1ET%2FzDz%2F3k%2F%2F3E7%2F20z%2F2Ur%2F2En%2F1Ub%2FzTz%2F10f%2Fzj7%2Fyzr%2F2Uv%2F0kP%2F0D%2F%2F00P%2F0ED%2F%2F%2F9ywrbbAAAAhXRSTlMABGu%2F6vn25bJUkOWrfs%2BDAu%2Fbz%2FbV4G6IiIiI%2BOA9uMzMzMzMzMz84HDu5ncu%2BeB4VaHRe73fda%2F00K6qqqqqoldQ%2FPX%2BVFiou7u7u7vU4b9r8KiOwLA%2Bi836N2Hugs3NzMzMzMzMskDNioiIiHjN0vDiyPsKb%2BJm%2FrmdQqXY7vHjuWkEM28rJQAAAO9JREFUGNNVkK1OA1EYROfcO5emWTYNxeMRhFoUmhB4AhDFoUhwJHVYFBgUCo0hQZUXQKAIkkcogrTkErJB7C4sI8%2FM95NBkkSrT0mSJUl9OAPg%2FEOSQm3ZFwCkTjLBKQDuQMMVnECvgWt0VKwDL95gvPhloccYbpwOO8wGgoMXAGXNok2I9htAedvuJJgjj4BpnQT2syG4gLJgD%2BB9mLOhf2dTzg1AHOZslqvo4OkcG4hVw%2B4TOnjYhZ2vWD22n10jSTreilV%2BBrj8a2kpVrnc3Lb%2FFVLlwWzlKVEP1sn0Opitfo9SU11tadIemUjSD%2Bs0MpPwiOyPAAAAAElFTkSuQmCC

[matlab]: https://img.shields.io/badge/MATLAB-white.svg?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABYAAAAUCAYAAACJfM0wAAAD3klEQVQ4y53UT4hVdRTA8e%2B5v%2Fvv3ffnzrw3M%2FiH0RjmT2PhkGZM9mdRL80MRWzjQhEXIZK6yBZBBS2iRRJChYsEg4yocBIUMfq3CDFKRWcMnJmmpkHnDTO%2BnJk3f9597977a%2FGQMhQZz%2BZszvlwOHCOsIDIb9uG6minmmvc0PXFkYOPFH4%2FnBszPiouEr1jaOq2WmMhMN3dVNo6FttDQ292ZQsrOlao16ZzstJTAP79wfkDB2D%2FfpFC4eVk36Xuzq45lq5hmeey65cR5PM2Fg7n162D9nY4dOgp48bE7uxwv9T7QmYxuC6bVi2h1ZQFwvmWFsjnYXi4Bct61%2BzvX9RYKeGGgmuBl2S5afCcI3Cs1b83nAfymzdDQ4PDyMhaUqmP9djYWq%2FvMnUJwQpAheAlEWXwYikkYf1navOOaLkMZ89CLtfG%2BfNvMzq6nomJrDEwgD9VJL1YkACMALwUKIM1lqbTEC7eMtT%2F0QSwbHoafeFCs5RKRygUNtHXl2B8HLf%2FKkvCWZbVC63NkErC7A0oTuBFMYOOcG5jvUvP38G%2FE%2B%2F94ze4fh1c1zbm5h6%2B9vWp16d6ep7h5k0QQTIZMlNFUq7g2qBDoAKOC7YN5QrrpyMOm8IcgLH32iB7tQatc2SzW4HP4jA80%2FTYqpey7S3IzAxYFvZYAV9iPIsaHAFVcJwabgirLKFTya0dz893MXTlBaJoC1G0kihyiGNM16Hp6ccxEgmKP%2F9KpjRJ2hE8CxwbtIY4BNMCNwHKIGdo8o5w4Virj0Ecr6dSeZUgWEMQOFSrEEWgNVopqhq8wij1piZpQtKtwQA6BtOEhFfLBmwoRWRMAYMwfJ9KZSfl8mWCACoViCJ0HHPjr1HKP%2FxILiyTMYWkDclEbRUCxDEoVYMdBwxhtSk8qgQMJidDJidPUa1upVr9lDCsRGEYTVwf1zMnT5MrjpO1hbQFGQ%2FStxADNGAo%2FrRtTpsW%2FcogpYQtvbOI8cETeejtg1JpSObn90TK3DWt7O0z33z3TtPw4EyTI9TZkE1D1gc%2FDZ4LSqG15rgy2eh5bI5CnhfhqCE8u9KjTe50ILsb0xTL2mrz1cH6BPsafGisg3of%2FBRkkpBwOZ6w2RPHjJsOfP8ViJAOY96KNaNyt5M%2ButonjHjwgaWcWdTE8pQHtgmmAjQ%2FodkBDDsW1L1X%2B8UnOnyAdKzpvivct9Nn3yfIqQ855ObYJ1XQ0xBOcmWuxHbT5FIQQMPB2x%2F88XYfQO4Ka%2B3DABDyJD4nCahjkIsM8QrNnIt7Qb0xxX2FHvHRV%2F2UnvBP6Dn%2FS93vP6S1j%2F7Wv2fvPzd4aYILeYaYAAAAAElFTkSuQmCC
