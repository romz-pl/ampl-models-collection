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
