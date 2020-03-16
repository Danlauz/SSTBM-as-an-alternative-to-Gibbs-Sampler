# SSTBM-as-an-alternative-to-Gibbs-Sampler

Programs to perform the sequential spectral turning bands method as an alternative to the Gibbs Sampler in large truncated- or pluri- Gaussian simulations. The programs provide examples for both situations. 

Description of each Matlab function  
Workplace.m : main program to execute the examples (Only run this Matlab file)
TruncatedGaussianSSTBM.m : Main code for the Truncated Gaussian Simulations
PluriGaussianSSTBM.m : Main code for the pluriGaussian Simulations
TourBandSpec.m : Code to simulate GRF (here reference) by the spectral turning band method
covardm.m : Function for computing covariances with specified models
DensSpec1Ddl.m : Function for computing the one-dimensional spectral densities of n-dimensional covariances models
grill2.m and grille3.m : Generates 2D and 3D grids respectively
VanCorput.m : Generates a quasi-random distribution over a half-sphere.
varioFFT2D_dl.m and varioFFT3D_dm.m : Computes 2D and 3D variogram respectively using the fast Fourier transform
