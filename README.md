Planet parameter estimation using MESA simulations
===============================================================

This respository contains supplementary material to the paper Millholland, S., Petigura, K., \& Batygin, K. 2020, ApJ, submitted, <i> Tidal Inflation Reconciles Low-Density Sub-Saturns with Core Accretion. </i> (It is also relevant to the methods of the paper Millholland, S. 2019, ApJ, 886, 72, <i> Tidally Induced Radius Inflation of Sub-Neptunes. </i>)

The IPython notebook entitled "Parameter_estimation_from_MESA_sims_demo.ipynb" contains a demonstration of how to estimate the envelope fraction of an observed planet (in this case, K2-19 b) using a set of previously-generated MESA simulations, which are described in Section 2.2 of Millholland et al. (2020). The simulation results are provided in the data file named "sim_set_MESA_results.txt", the contents of which are outlined in the IPython notebook. We use Markov Chain Monte Carlo methods to constrain the planet parameters, and we present two cases with and without accounting for tidal heating. 
