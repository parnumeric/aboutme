# Dmitry Nikolaenko

_Reseach Software Engineer_ for HPC <br>

[Email](mailto:dmitry.nikolaenko@yahoo.com) / [LinkedIn](https://www.linkedin.com/in/parnumeric/) / [GitHub](https://github.com/parnumeric/) / [Twitter](https://twitter.com/parnumeric/)

## Work Experience in HPC, numerical simulations and mathematical modelling

**Research Software Engineer** @ [University of Plymouth](https://www.plymouth.ac.uk/) (United Kingdom) _(Oct 2020 - Present)_ <br>
EXALAT Project of ExCALIBUR programme.
- Porting of the Particle Physics simulation suite _openQCD_ to GPU architecture
- Adapted data structures and their memory layout using CUDA Unified Memory to run the code on multiple GPU devices with CUDA-aware MPI communication of halo regions enabled thanks to NVIDIA GPUDirect
- Profiling MPI+CUDA code using performance analysis tool NVIDIA Nsight systems
- Debugging CUDA code using `cuda-gdb`
- **_Technologies used:_** CUDA, MPI, C.

**HiPEAC internship** @ [Shapelets](https://shapelets.io/) (Málaga, Spain) _(Nov. 2019 -- Feb. 2020)_
Research and development of parallel algorithms on GPU for time series analysis on a novel Big Data platform.
- Learning the open-source Python code [`Tigramite`](https://jakobrunge.github.io/tigramite/) for discovery of causal relationships in high-dimensional time series datasets and the company's flagship product [`Khiva`](https://khiva.readthedocs.io/en/latest/) for large-scale data analytics on GPU, based on Matrix Profile.
- Finding bottlenecks using profilers for Python: `py-spy`, `speedscope`, `pyinstrument`
- Parallelized Pearson correlation coefficient matrix using `ArrayFire` library
- Parallelized matrix-matrix, matrix-vector multiplication using `cuBLAS` library
- Added a new functionality in `Khiva` (in C++) and attempted to integrate it with `Tigramite` by means of Python binding
- Best practices of software development: package and environment management (`pip`, `conda`, `conan`), benchmarking (Google Benchmark), testing and code integration on GitHub (Travis, AppVeyor)
- Writing Python/C++ codes in modern IDEs (Microsoft Visual Studio 2019 / Code, JetBrains PyCharm, Jupyter Notebook)
- **_Technologies used:_** C++, Python, CUDA, ArrayFire, cuBLAS, CMake.

**Project Employee** @ Chair of Thermal Processing Technology, [Montanuniversität Leoben](https://www.unileoben.ac.at/) (Austria) _(Oct. 2016 -- Oct. 2018)_
Industrial Doctoral Program "Numerical investigation of steel oxidation during hot-dip galvanization process in industrial furnaces" (unfinished).
- Setting up, carrying out numerical simulations and evaluating CFD models for steel strips in industrial furnaces
- Adaptations of a multi-region conjugate heat transfer solver, which couples fluid and solid regions, in two cases for simulations of hot-dip galvanization: 1) cooling of moving steel strip; 2) turbulent combustion in a radiant tube burner with consideration of structural mechanics. In the latter case, flamelet modelling of turbulent combustion in the fluid region was combined with solving elastic deformation of the steel material in the solid region.
- Visualizing simulation results using ParaView.
- Literature review of combustion and turbulence models.
- **_Technologies used:_** C++, OpenFoam, ANSYS Fluent and ICEM CFD, Paraview.
- **_Research output:_** [Link](https://pure.unileoben.ac.at/portal/en/persons/dmitry-nikolaenko(bb711957-9c34-4f41-b689-5c9091336227)/publications.html)

**Project Employee** @ Institute for Mathematics and Scientific Computing, [University of Graz](www.uni-graz.at) (Austria) _(2007 -- 2010, 2013 -- 2016)_
Doctoral School "DK Numerical Simulations in Technical Sciences" and Doctoral Program "Multicore and manycore simulations for coupled physical systems" (unfinished).
- Worked on multigrid and multilevel techniques for coupled systems of PDEs for heat transfer and gas dynamics during combustion and implemented spatial and temporal adaptive algorithms for 1D evaluation of methane combustion within the 3D flame front from DNS (C++) (2010)
- Studied optimisation strategies and graph partitioning with SCOTCH
- Identified bottlenecks and explored scalability for the code `MercuryDPM` for granular flows and particle interactions realising discrete particle method
- Parallelization of the most time-consuming part in `MercuryDPM` - contact detection algorithm, based on a multilevel hierarchical grid - using standard `OpenMP` and a novel task-based `OmpSs` programming models
- Tuning and performance analysis and writing about it in a collaborative report as part of the co-design process in "Mont-Blanc 3" project (2016)
- **_Technologies used:_** Fortran, C++, MPI, OpenMP, OmpSs, Intel TBB, Intel Advisor and VTune Amplifier, MAQAO, Paraver, Extrae, UML, Doxygen.

## Education

**Summer schools, courses, workshops, hackathons** in high performance computing and HPC technologies <br>

**M.Sc. & B.Sc. in Applied Mathematics and Computer Science** @ [Nizhny Novgorod State Technical University](https://en.nntu.ru/) (Russia) _(2000 -- 2006)_
- Master Thesis: "Application of state-of-the-art computation technologies for a system of forest fire forecasting"

## Accomplishments

**DAAD Scholarship** for junior scientists @ [Saarland University](https://www.uni-saarland.de/en/) (Saarbrücken, Germany) _(2006 -- 2007)_
