Image-denoising-using-Noise2Noise-with-Resnet

This project investigates image denoising using the Noise2Noise algorithm with ResNet-50 instead of the traditional U-Net. 
Noise2Noise learns to remove noise from images using pairs of noisy images without requiring clean references. The study compares U-Net with ResNet-50,
ResNet-101, and ResNet-152 on the Caltech101 dataset, introducing Gaussian, Poisson, and Bernoulli noise.
Despite ResNet's deep residual learning capabilities, results show that U-Net outperforms all ResNet variants in denoising accuracy, 
likely due to its encoder-decoder structure and skip connections that better preserve spatial details.
Thus, U-Net remains the preferred choice for Noise2Noise-based image denoising.
