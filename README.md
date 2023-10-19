# Hand-written-Digits-Generation-using-GAN
A simple generative adversarial network to generate images of handwritten numbers

## Topic
In this notebook I will experiement with a simple Generative Adversarial Network or GAN to try to generate images of handwriten digits using the MNIST dataset. The network is composed of
two adversarial network: a generator and a discriminator, the discriminator's job is to differentiate between real images and fake images made by the generator, and the generator's job is
to try and create new images of the same size as the input from some noise z using transposed convolution layers. After training the network I will generate some images so let's see how 
good they will be !

## Objectives
- Build two adversarial networks and train them simutaniously
- Generate images of hand-written digits

## Summary
- Importing libraries
- The dataset
- The discriminator
- The generator
- Building the network
- Setting up the losses
- Training the network
- Inference
- Conclusion

## Libraries
- Numpy
- Torch
- Torchvision
- CV2
- Matplotlib
