Estimate a planet's envelope fraction using MESA simulations
======================================================================

This repository contains supplementary material to the paper Millholland, S., Petigura, K., \& Batygin, K. 2020, ApJ, 897, 7, <i> Tidal Inflation Reconciles Low-Density Sub-Saturns with Core Accretion. </i> (It is also relevant to the methods of the paper Millholland, S. 2019, ApJ, 886, 72, <i> Tidally-Induced Radius Inflation of Sub-Neptunes. </i>)

The IPython notebook entitled "Parameter_estimation_from_MESA_sims_demo.ipynb" contains a demonstration of how to estimate the envelope mass fraction of an observed planet (in this case, K2-19 b) using a set of previously-generated MESA simulations. The simulations provide the planet radius according to two models: one model including tidal heating and one without tidal heating. The radius is calculated as a function of the age, planet mass, envelope mass fraction, strength of the incident stellar radiation flux with respect to Earth's, and strength of the tidal dissipation. The simulation results are provided in the data file named "sim_set_MESA_results.txt"; its contents are outlined in the IPython notebook. 

In order to constrain the envelope mass fraction of an observed planet, we construct an interpolation to the MESA simulation results and employ Markov Chain Monte Carlo methods using the affine invariant ensemble sampler, emcee (Foreman-Mackey et al. 2013). In doing this, one can choose to include or ignore the effects of tidal heating. We present both cases for our example planet, K2-19 b, and compare them. 

If you have any questions, please don't hesitate to email me at sarah.millholland@mit.edu.
