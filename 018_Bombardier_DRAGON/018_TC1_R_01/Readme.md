# High Lift Prediction Workshop 6 - Template Submission Files

This folder contains four files participants are expected to modify and submit for Test Case 1:

1. **FM.dat** = Converged or time-averaged Force and Moment data vs. angle of attack, multiple grid levels may be included
   - N.B.: append grid descriptor if providing results for multiple grids
3. **gridconvergence\_FM.dat** =  Converged or time-averaged Force and Moment data vs. grid level, multiple angles of attack may be included (this is a transpose of #1)
4. **nominalgrid\_cpcf.dat** = Surface pressure and skin friction distributions at locations corresponding to experimental pressure belts. These are defined here: <insert link to distribution definition>
   - N.B.: remove nominal grid, add grid descriptor if providing results for multiple grids
6. **nominalgrid\_iterative.dat** = Solver iterative convergence with respect to iteration, or if time-dependent, with respect to convective time
   - N.B.: remove nominal grid, add grid descriptor if providing results for multiple grids

Additionally, participants should revise the Readme.md (this file) within their submission directory to include the following data:

# PARTICIPANT INFO:

# Name(s) and Organization(s):
Marc Langlois		Bombardier
Hadrien Pratte-Ness	Bombardier
Hong Yang		Bombardier

## Primary Email:  
marc.h.langlois@aero.bombardier.com

## Primary Phone:  
1 514 469 3350

## Address:  
400, boul. de la Cote-Vertu Ouest
Montreal (QC)
H4S 2Y9   Canada
 
# SOLVER INFORMATION:

## Solver Name and Version:
Dragon v13.17.8

## Basic Algorithm:  
Cell-centered coupled RANS solver
Unstructured mixed-element grids
Implicit time stepping
2nd-order spatial discretization
SGS relaxation scheme

## Turbulence Model:  
SA-neg

## Transition Method:
None

## Convergence Criteria:
Maximum Delta CL/CD/CMp less than 10-5 over 100 last iterations


# Test Case 1 GRID & SOLUTION INFO (CRM-HLS)

## Name of committee-supplied grid used (if other, supply the info below):
R.1.TC1.03 (Pointwise) Meshes A,B,C and D


# "TYPICAL" SOLUTION PERFORMANCE INFORMATION 
## Grid size:
106M cells (Mesh C)

## Computer Platform:  
Google Cloud H3 machine series - Xeon Scalable Sapphire Rapids

## Number of Processors:  
1760

## Operating System:  
Linux

## Compiler:  
Intel OneAPI 2024 with Intel MPI 2021

## Run Time CPU:  
66531:42:46  (full polar, 10 AoAs, including I/O)

## Run Time Wall-Clock:  
38:03:55     (full polar, 10 AoAs, including I/O)

