
# CIFAR10 Denoising Using U-NET
In this project, I implemented a U-Net architecture for denoising images in the CIFAR-10 dataset. I then attempted to improve the Peak Signal-to-Noise Ratio (PSNR) of the denoised images by using a Generative Adversarial Network (GAN) with a U-Net as the generator and a U-Net with attention as the discriminator.



## Dataset

The CIFAR-10 dataset was used for training and testing the U-Net and GAN models. The dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. Salt and Pepper noise was added to each image to simulate noisy images.


## Preprocessing

Before feeding the noisy images into the models, some preprocessing steps were applied. The images were first normalized to have zero mean and unit variance. Data augmentation techniques such as random horizontal flipping and random cropping were also applied to increase the size of the training set and improve the performance of the models.

## U-Net Architecture
The U-Net architecture was used as the denoiser in this project. The U-Net architecture is a type of convolutional neural network that is commonly used for image segmentation and has been shown to be effective for image denoising. The hyperparameters such as learning rate and batch size were tuned for the U-Net.

## GAN Architecture
To improve the PSNR of the denoised images, a GAN architecture was used. The generator was a U-Net architecture, and the discriminator was a U-Net with attention. The generator was trained to produce denoised images that were similar to the clean images, while the discriminator was trained to distinguish between the denoised images and the clean images. The hyperparameters such as learning rate and batch size were tuned for the GAN.
## Documentation

You can see the description of the implementation method in the following file:
[Click Me](https://github.com/kiananvari/CIFAR10-Denoising-Using-UNET/raw/main/Documentation.pdf)


## Results

![App Screenshot](https://github.com/kiananvari/CIFAR10-Denoising-Using-UNET/blob/main/Results/1.png)

![App Screenshot](https://github.com/kiananvari/CIFAR10-Denoising-Using-UNET/blob/main/Results/2.png)

