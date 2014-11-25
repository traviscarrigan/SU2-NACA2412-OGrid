# NACA 2412 Airfoil
[SU2](https://github.com/su2code/SU2) case for simulating turbulent flow over a NACA 2412 airfoil at 8 degrees angle of attack. The Reynolds number is approximately 3 million for this simulation. 

The airfoil is aligned with the x-axis, so it's the velocity components that control the angle of attack. The Spalart Allmaras turbulence model is used for this case. 

![Mesh Image](https://raw.github.com/traviscarrigan/SU2-NACA2412-OGrid/master/ogrid.png)

## Usage
This is to be run using *SU2_CFD*. The configuration file, *naca2412.cfg*, contains all the options for the CFD module. Within this file you can adjust the schemes, solver settings, and convergence criteria. 

To adjust the angle of attack, the velocity components must be modified in the configuration file, *naca2412.cfg*.

## Notes
If you have Pointwise, you can open the *naca2412.pw* file and manipulate and/or regenerate the mesh. 

