# Image Encoding annd Reconstruction

This is a Tensorflow based project on Image Encoding and reconstruction using Variational Auto Encoder.

# Motivation
An implementation of Variational Auto Encoder described in the papers:
* [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)
* [Deep Feature Consistent Variational Autoencoder](https://arxiv.org/abs/1610.00291)

# Dataset
The currect code uses CelebA dataset. It is a collection of 200,000 celebrity faces.

## Results
### Reproduce
Train the VAE to reconstruct the original image of a celebrity face! 
We can reproduce performance of learned generative models for different dimensionalities.  
The following results can be reproduced with command:  
```
python run_main.py --dim_z <each value> --num_epochs 60
``` 





