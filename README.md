# DeepLearning_GANs
Final exam of the Deep Learning course 2022, UniTS
-# GAN's (Generical Adversarial networks)
* The following project is about creating a "generical adversarial network" using two convonutional neuronal networks which are compiting each other in order to generate a Data set
* the implementation is a DCGAN
* the generator which is the convolutional neuronal network in wich we generate the data
* the discriminator wich is the convolutional neuronal network in wich we will do binary classification (real vs fake)
* the main objective of GANs is create a model that can generate samples, given a bunch of samples from a particular distribution, and the GAN will give us new more samples from the same distribution, to generate this samples we will use a generator to have at the very end a discriminator that won't be able to indentify if the image is fake or not, and in that way the discriminator will give a probability of 0.5 to each image
