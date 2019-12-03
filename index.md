## How to Speed up QCEIMS
### QC method
1. Multiple time step integrator
  break down GFN-xTB Hamiltonian into fast and slow part
  
 This is a challenging but doable part for me. To solve this problem, I need better understand on 
 quantum chemistry and molecular dynamics. Also, since Lee-Ping is the expert in this field,
 I need to talk to him more frequently and regularly. If I can solve this problem before my QE, 
 I will have 100% confidence to pass it.
 
 
2. Combine different methods
  OM2 as ground state MD and GFN-xTB as production
  
  **Ground state MD Energy**  
  ![GFN_energy](/image/new143energy.png)
  
  GFN *GFN has more energy levels*
  ![OM2_energy](/image/143energy.png)
  
  OM2 methods 
  
  This is an easy trial. Just modify the codes and keep the nodes running. Can be done at free time.
  
  
### Statistical method
1. Get a stable spectrum with less MD times

**Production MD #fragments**
  ![GFN_fragment](/image/newversion143.png)
  
  GFN *GFN has longer simulation time*
  
  ![OM2_fragment](/image/143fragments.png)
  
  OM2 methods

2. Change parameters

This could be the main part for my QE project. We already had some results and it's easy 
to draw some conclusions. But we need to collect more chemistry knowledge into explanation.


### CS method
1. openMP
  how to parallel
2. running time analyses
  Find out witch step takes more time:
  [Performance Profiling](https://docs.oracle.com/cd/E19957-01/805-4940/6j4m1u7q2/index.html)
  
  
I am very interested in this subproject, this will help us understand how it runs on CPUs better.
And we can find a way to optimize the codes, even transfer the code to GPUs. But this project is 
a littel far away from chemistry. I am more willing to dig into this after QE. 

## Need to do
* At this time, finishing the QCEIMS paper has the highest priority. **Before Friday Dec 6**
* Get the statistical method test code running. **This weekend**
* Finish a review paper on QCEIMS and it's application in metabolomics.**Before the end of this quarter**
* Finish the draft and talk with Dean about the gold project paper. **Winter break**

