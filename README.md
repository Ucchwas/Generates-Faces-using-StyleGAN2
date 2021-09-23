A generative adversarial network (GAN) is a machine learning model in which two neural networks compete with each other to become more accurate in their predictions. GANs typically run unsupervised and use a cooperative zero-sum game framework to learn.

The two neural networks that make up a GAN are referred to as the generator and the discriminator. The generator is a convolutional neural network and the discriminator is a deconvolutional neural network. The goal of the generator is to artificially manufacture outputs that could easily be mistaken for real data. The goal of the discriminator is to identify which outputs it receives have been artificially created.

Two adversaries (generator + discriminator) compete with each other. Over time, the generator gets better at generating images.

In this project I tried to generate images using StyleGan2. 
