# QG vertical modes
<p>The following JuPyter notebooks contain details about the calculations and provide the codes used in Rocha, Young, and Grooms. [submitted to JPO](http://crocha700.github.io/pdfs/galerkin_qg_submitted_twocols.pdf). An index  notebook is available <a href="http://nbviewer.ipython.org/github/crocha700/qg_vertical_modes/blob/master/index.ipynb">here</a>.</p>

<p>Even if you do not have python installed on your computer, you can still reproduce our results. The simplest way is to open a free <a href="https://wakari.io" target="_new">Wakari</a> account, and run our notebooks in the cloud.</p>

<p>If you have trouble installing numba, just comment out the lines with @numba.jjit. This is a simple decorator to speed up the code.</p>

<p>If you have any questions please contact Cesar B. Rocha (crocha@ucsd.edu). You are also encouraged to contact Rocha if you find a mistake (or even better you could submit a pull request)</p>

## Abstract
We study the representation of approximate solutions of the three-dimensional quasigeostrophic (QG) equations using Galerkin series with standard vertical modes. In particular, we show that standard modes are compatible with nonzero buoyancy at the surfaces and can be used to solve the Eady problem. We extend two existing Galerkin approaches (A and B) and develop a new Galerkin approximation (C). Approximation A, due to Flierl (1978), represents the streamfunction as a truncated Galerkin series and defines the potential vor- ticity (PV) that satisfies the inversion problem exactly. Approximation B, due to Tulloch and Smith (2009b), represents the PV as a truncated Galerkin series and calculates the streamfunction that satisfies the inversion problem exactly. Approximation C, the true Galerkin approximation for the QG equations, represents both streamfunction and PV as truncated Galerkin series, but does not satisfy the inversion equation exactly. The three approximations are fundamentally different unless the boundaries are isopycnal surfaces. We discuss the advantages and limitations of approximations A, B, and C in terms of mathematical rigor and conservation laws, and illustrate their relative efficiency by solving linear stability problems with nonzero surface buoyancy. We emphasize that standard vertical modes form a complete basis for representing solutions of the QG equations, regardless of nonzero surface buoyancy boundary conditions. We recommend approximation C for constructing solutions to the QG equations using Galerkin series with standard vertical modes.
