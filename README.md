# Denoising-Autoencoder-Spectral-Data
This is the repo for denosing of spectral data from the private rat lung dataset. The dataset originally in .mat file, which is converted into three .npy (Numpy Arrays) files, one file contains the original data, second file contains its backgroung and thrird file contains the wavelenghts. The code is develoved to denosie the signals using autoencoders whcih has to be validated with the SNR values and the corealation computatation. I use Pytorch as we have Cuda 12.8 version using on Tesla V100 32 GB GPU x 8. 
