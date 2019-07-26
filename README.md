# Resonance Overlap

C code for calculation of trajectories in a Hamiltonian model of resonances overlap. 

---

`main_rk4.c` 
* main function to run a simulation for a set of initial conditions.
* system's parameters are set by hand in this file, along with run parameters.

`auxf.c` 
* auxiliary functions definitions. 
* included here are the motion equations, hamiltonian, integrator etc.

`auxf.h` 
* declaration of `auxf.c` functions
            
