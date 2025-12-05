# AMPL models collection


## [AMPL](https://ampl.com/) Overview
AMPL (A Mathematical Programming Language) is a high-level algebraic modeling language designed for describing and solving large-scale optimization problems. It was developed in the 1980s at Bell Laboratories by Robert Fourer, David Gay, and Brian Kernighan.

### What AMPL Does
AMPL allows you to express mathematical optimization problems in a natural, algebraic notation that closely resembles the mathematical formulation you'd write on paper. Instead of writing complex code to define optimization problems, you can express them in a way that looks very similar to the mathematical equations themselves.

### Key Features
AMPL separates the model (the mathematical structure of your problem) from the data (the specific numbers you're working with). This means you can define a general optimization problem once and then solve it with different datasets without rewriting the model.
The language supports various types of optimization problems including linear programming, nonlinear programming, integer programming, and mixed-integer programming. It can interface with numerous solvers like CPLEX, Gurobi, MINOS, and others, acting as a bridge between your problem description and the computational engine that solves it.

### Practical Use
AMPL is widely used in operations research, supply chain optimization, production planning, financial modeling, and engineering design. Its strength lies in making complex optimization accessible—you focus on describing what you want to optimize rather than how the computer should solve it. The language handles the translation of your model into a form that specialized solvers can work with efficiently.




## [AMPL Book Examples](https://dev.ampl.com/ampl/books/ampl/examples/index.html)
AMPL models form the book: R. Fourer, D.M. Gay, B.W. Kernighan [AMPL: A Modeling Language for Mathematical Programming](https://ampl.com/wp-content/uploads/BOOK.pdf), 2003


## [AMPL Optimization Tests](https://github.com/ampl)
The AMPL global-optimization repository on GitHub includes constraint satisfaction test problems with polynomial systems, including chemical equilibrium problems and other polynomial optimization test cases. These problems are part of a broader collection that includes multiple problem sets designed for testing global optimization solvers. 


## [COPS Large-Scale Optimization Problems](https://www.mcs.anl.gov/~more/cops/)
The primary purpose of this collection is to provide difficult test cases for optimization software. Problems in the current version of the collection come from fluid dynamics, population dynamics, optimal design, mesh smoothing, and optimal control. 


## [NETLIB AMPL Models Collection](https://netlib.org/ampl/models/)
This collection includes sample models from older papers and several subdirectories:
+ **nlmodels**: A collection of nonlinear programming test problems assembled by Elena Bobrovnikova, including problems from the Hock-Schittkowski collection and various benchmark problems like Rosenbrock, Powell, and others
+ **compl**: Sample complementarity problems documented in papers about expressing complementarity problems in algebraic modeling languages.
+ Classic models like DIST, EGYPT, and various production planning problems with multiple data instances.


## [Vanderbei's Nonlinear Optimization Models](https://vanderbei.princeton.edu/ampl/nlmodels/)
This collection includes various problem categories with graphical visualizations and 3D models, covering antenna array synthesis, the brachistochrone problem, catenary problems, data envelopment analysis, FIR filter design, and many other applications. The collection also includes the CUTE test set problems translated to AMPL format.


## [COCONUT Benchmark](https://arnold-neumaier.at/glopt/coconut/Benchmark/Benchmark.html)
The COCONUT benchmark is a test set for continuous global optimization problems. Library 2 specifically consists of global optimization problems from the CUTE subcollection of Nonlinear Optimization Models in AMPL, collected by Bob Vanderbei.


## [MINLPLib (Mixed-Integer Nonlinear Programming Library)](https://www.minlplib.org/)
Since 2001, MINLPLib has provided algorithm developers with a large and varied set of both theoretical and practical test models. The primary format is GAMS, but instances are provided in multiple formats including AMPL where conversion is possible. The collection includes a translation server that can transform models from GAMS format into other formats including AMPL


## [AMPL Global Optimization Test Set](https://github.com/ampl/global-optimization?tab=readme-ov-file)
Available on GitHub, this collection includes multiple problem sets: CSP (constraint satisfaction test problems), CUTE test set, GLOBAL library, Hansen's univariate Lipschitz optimization problems, models by János D. Pintér, and models from the AMPL repository on Netlib with modifications.


## [MIPLIB (Mixed Integer Programming Library)](https://miplib.zib.de/)
MIPLIB 2017 is the sixth edition of the standard library for mixed integer programming, containing 1065 instances with a benchmark subset of 240 instances specifically selected for solver performance testing. Many MIPLIB instances were originally modeled through AMPL, and some contributors provided model files in AMPL format. While primarily in MPS format, AMPL models exist for many problems.


## [GAMS World](https://github.com/GAMS-dev/gamsworld)
This collection of models originates with the GAMS World Initiative and in particular the Performance World Libraries. The purpose of these collections is to provide users with an established and varied set of both theoretical and practical test models. Models from various sources (AMPL, MOSEL, MPL, ...) have been made available in as GAMS models and generated as scalar models. The GAMS World web site has been closed down but this useful collection of models found a new home here. 


## [MacMOOP (Multi-Objective Optimization Problems)](https://wiki.mcs.anl.gov/leyffer/index.php/MacMOOP)
This is Sven Leyffer's collection of multiobjective test problems, with all models written in AMPL. The GAMS models were translated by Andre Savitsky from the original AMPL source. The collection includes problem characteristics showing the number of variables, constraints, and objectives for each test problem.


## [MacMPEC (Mathematical Programs with Equilibrium Constraints)](https://wiki.mcs.anl.gov/leyffer/index.php/MacMPEC)
This directory contains a collection of Mathematical Programs with Equilibrium Constraints (MPEC) test problems in AMPL. MacMPEC is a test suite of MPEC problems coded in AMPL with over 100 problems including modeling applications from economics, transportation, structural design, and optimum packaging problems, with problems ranging from four variables to 5900 variables.


## [MacMINLP (Mixed Integer Nonlinear Programming )](https://wiki.mcs.anl.gov/leyffer/index.php/MacMINLP)
MacMINLP page contains a collection of Mixed Integer Nonlinear Programming (MINLP) test problems in AMPL.


## [AMPL problems from Robert Vanderbei's webpage](https://github.com/mpf/Optimization-Test-Problems)
The CUTEst collection (successor to CUTEr) is available in AMPL format. The Constrained and Unconstrained Testing Environment contains test problems for linear and nonlinear optimization. This is one of the most widely-used standard test sets in the optimization community.


## [Derivative-Free Optimization (DFO) Test Problems](https://sahinidis.coe.gatech.edu/dfo)
This collection provides test problems in multiple formats including GAMS and C/Fortran, with models from GLOBALLib and PrincetonLib available in C source code. The benchmarking collection includes source files for 22 CUTEr problems in both Fortran and MATLAB, designed specifically for derivative-free optimization testing.


## [QPLIB (Quadratic Programming Library)](https://qplib.zib.de/)
QPLIB provides 319 discrete and 134 continuous quadratic programming instances in multiple formats including AMPL (.mod), GAMS (.gms), CPLEX (.lp), and a specialized QPLIB format. The library was created by extending scripts initially developed for MINLPLib and offers instances with rich metadata.


## [Revised Hock and Schittkowski models](https://www.stfmc.de/fmc/rhs/x/tlf.html)
The revised Hock-Schittkowski models are available in AMPL, APM, FMCMAC, and FMCMAP formats with high-quality reference results. 


## [OR-Library (Operations Research Library)](https://www.brunel.ac.uk/~mastjjb/jeb/info.html)
OR-Library is a collection of test data sets for a variety of Operations Research problems, originally described by J.E. Beasley. The library includes problems across numerous categories including capacitated facility location, bin-packing, vehicle routing, assignment, graph coloring, frequency assignment, data envelopment analysis, and many others. 


## [SteinLib (Steiner Tree Problem Library)](https://steinlib.zib.de/steinlib.php)
SteinLib is a library of data sets for the Steiner tree problem in graphs, extending former libraries with many new interesting and difficult instances, most arising from real-world applications. The library collects freely available instances of Steiner tree problems in graphs and variants, providing information about their origins, solvability and characteristics.


## [Maros-Mészáros Quadratic Programming Test Set](https://github.com/qpsolvers/maros_meszaros_qpbenchmark)
The Maros-Mészáros test set is a collection of 138 convex quadratic programming examples from various sources, available in QPS format which is a subset of the SIF format used by CUTEst. The problems are classified according to the CUTE classification system and have been reformatted for consistency, with problems organized from the CUTE library, Brunel optimization group, and miscellaneous sources


## [Hans Mittelmann's Benchmark Problem Sets](https://plato.asu.edu/bench.html)
Hans Mittelmann maintains extensive benchmark collections at plato.asu.edu/bench.html covering various optimization problem classes including AMPL-NLP benchmarks, mixed integer QPs and QCPs, QPLIB benchmarks (binary/discrete/continuous, convex/non-convex), and MINLP benchmarks. These benchmarks test state-of-the-art solvers on over 1000 test problems in up to 1000 variables, with problems available online in AMPL format and translators available through the COCONUT environment.


## [CMU-IBM Cyber-Infrastructure for MINLP collaborative site](https://www.minlp.org/)
This collaborative site has as a major goal to promote the optimization of linear and nonlinear models with one or several alternative model formulations involving discrete and continuous variables through mixed-integer nonlinear programming (MINLP), or generalized disjunctive programming (GDP).


