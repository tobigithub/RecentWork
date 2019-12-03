# Hi
## How to Speed up QCEIMS
### QC method
1. Multiple time step integrator
  break down GFN-xTB Hamiltonian into fast and slow part
2. Combine different methods
  OM2 as ground state MD and GFN-xTB as production
  ![GFN_energy](/image/new143energy.png)
  ![OM2_energy](/image/143energy.png)
### Statistical method
1. Get a stable spectrum with less MD times
  ![GFN_fragment](/image/newversion143.png)
  ![OM2_fragment](/image/143fragments.png)

2. Change parameters

### CS method
1. openMP
  how to parallel
2. running time analyses
  Find out witch step takes more time:
  [Performance Profiling](https://docs.oracle.com/cd/E19957-01/805-4940/6j4m1u7q2/index.html)
