# Name(s) and Organization(s):
- Eduardo Molina - Embraer
- Mauro Lopez - Embraer
- Pedro Ciloni - Embraer 
- Rodrigo Granzoto - Embraer

## Primary Email:  
eduardo.molina@embraer.com.br
 
# SOLVER INFORMATION:

## Solver Name and Version:
Volcano ScaLES - 2026.03.3

## Basic Algorithm:  
- Spatial discretization: Finite Difference 4th order (inviscid) + 2nd order (viscous)
- Time integration: Explicit (3rd order Runge-Kutta)  
- Initialization method: Freestream / impulsive start for free air and grid-sequencing
- Grid topology: Octree Cartesian grids with immersed boundary 
- Wall modeling: Equilibrium Wall Modeling (Algebraic) 
- SGS closure: Smagorinsky with Dynamic Procedure 
- Aspect ratio range (tangential spacing/wall-normal): 1 
- Wall model exchange location: 1.5 x (Dx) 

## Turbulence Model:  
None
## Transition Method:
None
## Convergence Criteria:
None

# Test Case 1 GRID & SOLUTION INFO (CRM-HLS)

## Grid-Generator Name and Version:  
VolcanoMesh 2026.3.3

## Type (str, overset, unstr, etc):  
Octree

## Number of Total Cells:
417835528

## Miscellaneous:  
Grid generated with one level finer on the flap upper surface compared to the wing and slat. 
