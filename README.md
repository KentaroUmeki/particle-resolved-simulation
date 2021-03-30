# particle-resolved-simulation
This is the code for carrying out the simulation of flow field surrounding the particle that emits Stefan flow.
This has 2 separate solvers.
1.StefanSimpleIbFoam\\
This code is created by editing the 'simpleIbFoam' code to apply a Stefan flow velocity at the surface of the immersed boundary in isothermal conditions.\\
2.StefanNonisoSimpleIbFoam\\
This code is created by editing 'StefanSimpleIbFoam' including variations of thermophysical properties with temperature. Density is calculated based on pM/RT (rho=pM/RT). The code is applicable for low Mach number flows.\\
