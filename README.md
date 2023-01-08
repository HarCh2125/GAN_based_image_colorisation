# Image Colorisation using GAN

###### This project aims at implementing the given paper(https://doi.org/10.48550/arXiv.1803.05400), i.e., use a Generative Adversarial Network to colorise non-coloured images. The CIFAR10 image dataset has been used, and the images have been converted to single-channeled ones, and have then been passed to the models.

###### A GAN consists of a __Generator__, a neural network that attempts to fabricate samples using the dataset as closely as possible, and a **Discriminator**, which, as the name suggests, aims to distinguish between a given image as real or fake (created through the generator). These NNs compete against each other in a __zero-sum game__. 

###### The task performed by this project is an **unsupervised learning** task, as it learns patterns from unlabeled data. GANs, since their creation in 2014 by Ian Goodfellow, have been extensively used for such tasks.
