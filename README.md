PhD thesis: Numerical solutions of inverse partial differential equation problems
========================

## Author(s)
*   Zhixuan Jia

--------------------------------------------------------------------------------

## Abstract
Many real-world processes such as fluid flow, heat and mass transport, wave motion and others involve quantities that vary in space and time and are governed by Partial Differential Equations (PDEs). If we know the governing equations, there are methods available to obtain their solution either analytically or numerically. In this thesis, we consider the inverse problem of finding the PDEs themselves and the parameters that appear in those equations if we happen to know the solution in the form of experimental or numerical data. For this purpose, we initially focus on Fisher's famous equation and some of its variants and on the special case of traveling wave solutions of those equations. In particular, we consider a modified Fisher's equation that includes a relaxation time in relating the flux to the gradient of the density, as well as one where the nonlinear term on the right-hand side is modified to include cubic or higher-order non-linearities. We show that these equations still possess traveling wave solutions. We do this using standard methods for nonlinear dynamical systems in which fixed points in the phase plane are found and their stability characteristics are classified. We then design parameter estimation/discovery algorithms for this system including a few based on machine learning algorithms. In the end, instead of relying on traveling wave solutions, we applied a network-based model to solve PDEs. We also designed a PDE discovery model with the help of a resampling method. These algorithms contain several components: ensemble learning models that combine learning algorithms and neural networks when the nonlinear right-hand side function is known, optimization problems for both cubic right-hand side functions with an extra unknown parameter and general functions with k extra unknown parameters, physics-informed neural networks for solving PDEs, and a resampling model with the library $\Phi$ for PDE discovery.

## Keywords

*   Machine learning, Deep learning, Physics-informed neural network, Optimization, Ordinary differential equations, Partial differential equations.
