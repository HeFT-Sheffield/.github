# Heat, Flow and Turbulence research group based at the University of Sheffield
This organisation host software repositories developed by the Heat, Flow and Turbulence (HeFT) research group at the University of Sheffield.

## Collaborations
Under the Collaborative Computational Project in Nuclear Thermal Hydraulics (CCP-NTH) we participate in the use and development of several community codes.

### CHAPSim
[CHAPSim](https://github.com/weiwangstfc/CHAPSim1.0) is a Fortran-MPI based finite difference code to solve the conservative variables ( ρ u , ρ v , ρ w , ρ h ) in Navier-Stokes equations with heat transfer. Initially developed by Dr Mehdi Seddighi-Moornani in f77 platform for simulations of unsteady turbulent flows in a channel during his PhD study starting from 2007, the code was later revamped by Dr Wei Wang for solving thermo-fluids problems in f90 platform in 2014/2015.

### CHAPSim2
[CHAPSim2](https://github.com/CCP-NTH/CHAPSim2) is a direct numerical solver for thermal-hydraulics with strong thermophysical property variations and magnetohydrodynamics. The [2decomp&FFT](https://github.com/2decomp-fft/2decomp-fft) library is used for domain decomposition and fast Fourier transforms. CHAPSim2 is highly scalable, tested on 32,000 cores on Archer2.
