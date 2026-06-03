# High Lift Prediction Workshop 6 - Template Submission Files

This folder contains four files participants are expected to modify and submit for Test Case 1:

1. **FM.dat** = Converged or time-averaged Force and Moment data vs. angle of attack, multiple grid levels may be included
   - N.B.: append grid descriptor if providing results for multiple grids
3. **gridconvergence\_FM.dat** =  Converged or time-averaged Force and Moment data vs. grid level, multiple angles of attack may be included (this is a transpose of #1)
4. **nominalgrid\_cpcf.dat** = Surface pressure and skin friction distributions at locations corresponding to experimental pressure belts. These are defined [here](https://aiaa-hlpw.org/assets/HLPW6/tc1/TC1_Pressure_Rows.xlsx)
   - N.B.: remove nominal grid, add grid descriptor if providing results for multiple grids
6. **nominalgrid\_iterative.dat** = Solver iterative convergence with respect to iteration, or if time-dependent, with respect to convective time
   - N.B.: remove nominal grid, add grid descriptor if providing results for multiple grids

Additionally, participants should revise the Readme.md (this file) within their submission directory to include the following data:

# PARTICIPANT INFO:

# Name(s) and Organization(s):
Joshua Wagner, NASA LaRC

## Primary Email:  
joshua.j.wagner@nasa.gov

## Address:  
Mail Stop 128
1 Nasa Drive, Hampton, VA, 23681
 
# SOLVER INFORMATION:

## Solver Name and Version:
FUN3D v14.2, Stabilized Finite Element (SFE) solver 

## Basic Algorithm:
P1 finite elements with Streamline Upwind Petrov-Galerkin (SUPG)

## Turbulence Model:  
SA-neg

## Transition Method:
none

## Convergence Criteria:
Run until residuals flatten out

## Miscellaneous:  
Cold start

# Test Case 1 GRID & SOLUTION INFO (CRM-HLS)

## Name of committee-supplied grid used (if other, supply the info below):
R.1.TC1.02 HeldenMesh Adaptive grid family (Helden Series 04)

# "TYPICAL" SOLUTION PERFORMANCE INFORMATION 
## Grid size:
30840679

## Computer Platform:  
Insert computer platform here

## Number of Processors:  
Insert number of processors here

## Operating System:  
Insert operating system here

## Compiler:  
Insert compiler here

## Run Time CPU:  
Insert CPU run time here

## Run Time Wall-Clock:  
Insert wall-clock time here

## Memory Requirements:  
Insert memory requirements here

## Convergence Details
Insert convergence information here (if applicable)

## Miscellaneous:
Insert miscellaneous information here regarding solution performance

# OTHER
Provide any other information desired here
