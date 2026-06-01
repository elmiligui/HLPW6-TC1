# High Lift Prediction Workshop 6 - LAVA Unstructured Participant ID-014

This folder contains three files participants are expected to modify and submit for Test Case 1:

1. **FM.dat** = Converged or time-averaged Force and Moment data vs. angle of attack, multiple grid levels may be included
2. **gridconvergence\_FM.dat** =  Converged or time-averaged Force and Moment data vs. grid level, multiple angles of attack may be included (this is a transpose of #1)
3. **nominalgrid\_cpcf.dat** = Surface pressure and skin friction distributions at locations corresponding to experimental pressure belts. These are defined [here](https://aiaa-hlpw.org/assets/HLPW6/tc1/TC1_Pressure_Rows.xlsx)

Additionally, participants should revise the Readme.md (this file) within their submission directory to include the following data:

# PARTICIPANT INFO:

# Name(s) and Organization(s):
Emre Sozer (NASA Ames Research Center)
Jared C. Duensing (NASA Ames Research Center)

## Primary Email:  
emre.sozer@nasa.gov
jared.c.duensing@nasa.gov

## Primary Phone:  
N/A

## Address:  
N/A

# SOLVER INFORMATION:

## Solver Name and Version:
Launch, Ascent, and Vehicle Aerodynamics (LAVA) Framework, Version 1.0.1

## Basic Algorithm:  
LAVA Unstructured uses arbitrary polyhedral unstructured meshes with a cell-centered finite-volume formulation.
In this test, a WMLES approach is used with low dissipation, kinetic energy preserving convective flux paired with sensor-based application of localized upwinding. Time integration is explicit with the 3rd order accurate SSPRK33 scheme. A constant coefficient Vreman SGS model is used with directional filter size. An equilibrium wall model is used in conjunction with a turbulence sensor that switches between no-slip and wall model wall stress based on resolved turbulence kinetic energy level. The wall model uses the first cell center off the wall as the sampling location. Details about the scheme are documented in Sozer et al 2025, SciTech (https://arc.aiaa.org/doi/abs/10.2514/6.2025-0887). 

## Turbulence Model:  
- Constant coefficient Vreman subgrid scale model with directional filter size.
- Equilibrium wall model.

## Transition Method:
- Wall model switches between no-slip (laminar) and wall function (turbulent) wall stresses based on detected resolved turbulence kinetic energy at the first cell center off the wall.
- No true transition model is used.

## Convergence Criteria:
N/A

## Miscellaneous:  

# Test Case 1 GRID & SOLUTION INFO (CRM-HLS)

## Name of committee-supplied grid used (if other, supply the info below):
Insert name of committee-supplied grid here

For non-committee grids...
## Grid-Generator Name and Version:  
LAVA Voronoi Mesher v1.0.1

## Type (str, overset, unstr, etc):  
Unstructured Voronoi 

## Number of Total Nodes:  
(L11) 1608010550

## Number of Total Cells:
(L11) 260094313

## Miscellaneous:  
Insert any other information about the grids or solution procedure(s) used for Test Case 1 here

# "TYPICAL" SOLUTION PERFORMANCE INFORMATION 
## Grid size:
Insert the grid size here that was used for providing the subsequent statistics

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
