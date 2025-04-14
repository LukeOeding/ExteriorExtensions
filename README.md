# ExteriorExtensions.m2
A package for Macaulay2 that constructs extensions of Lie algebras via exterior algebras

This package builds a graded algebra that equivariantly extends the Lie
    algebra sl_n via the non-zero graded piece of the exterior algebra by
    defining the bracket products. Constructs matrix representations of
    adjoint operators. Computes ranks of blocks coming from the grading.,
    Keywords => {"Lie Algebras", "Jordan Decomposition", "Tensor invariants"}
    
To interact with the package save the file somewhere on your machine. 
Then launch Macaulay M2 from the same directory. 
Then do this:
 
installPackage("ExteriorExtensions")
viewHelp ExteriorExtensions
 
The help documents give several basic examples to try out.

Subsequent times when you start M2, do this (this doesn’t re-generate the examples).
loadPackage ExteriorExtensions
