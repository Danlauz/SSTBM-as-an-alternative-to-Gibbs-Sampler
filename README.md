# SSTBM-as-an-alternative-to-Gibbs-Sampler

Programs to perform the sequential spectral turning bands method as an alternative to the Gibbs Sampler in large truncated- or pluri- Gaussian simulations. The programs provide simple examples for both situations. 

Description of each Matlab function  
Workplace.m : main program to execute the examples (Only run this Matlab file)
PluriGaussianSSTBM.m : Main code for the Truncated and pluriGaussian Simulations
TourBandSpec.m : Code to simulate GRF (here reference) by the spectral turning band method
covardm.m : Function for computing covariances with specified models
DensSpec1Ddl.m : Function for computing the one-dimensional spectral densities of n-dimensional covariances models
grille3.m : Generates 3D grid
VanCorput.m : Generates a quasi-random distribution over a half-sphere.
varioFFT2D_dl.m : Computes 2D variogram using the fast Fourier transform
Figures.m : Generates variogram figures and map realisation with the associated categorical field.
TGS.m and PGS.m : Initialization phase for TGS and PGS
knnsearchdl.m : directly finds the neighborhood in the T-SGS step 
private : for the truncated sequential gaussian simulation (from Botev 2016)
PluriGaussianTransform and PluriGaussianTransformRef : Transforms the gaussians to categorical field. PluriGaussianTransformRef version generate references with the exact proportion. 
trandn.m : truncated normal generator. (from Botev,2016)


note : the code has been adapted to introduce shifts and correlations between Gaussian latent fields as uses by Blevec et al. (2018). (08/10/2020)
note : this version supports gpu computing. Just set gpuOn=1. Currently set to 0. A parfor-loop can be used instead of a for-loop. 
