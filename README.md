# DCGAN-Tensorflow
A Tensorflow implementation of DCGAN proposed in the paper [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434).

### Architecture of DCGAN :
<p float="left">
  <img src="https://github.com/IMvision12/DCGAN-Tensorflow/blob/main/images/dcgan.PNG" width="800" />
</p>  

  ## About Model:
    1. Used strided convolutions (discriminator) and fractional-strided convolutions (generator)
    2. BatchNormalization in both the generator and the discriminator network
    3. Used LeakyReLU in both generator and discriminator and Tanh in last layer of generator
