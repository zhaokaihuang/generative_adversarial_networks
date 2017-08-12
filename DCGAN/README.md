The [gan.py](gan.py) implements a basic, simple version of Deep Convolution Generative Adversarial Learning (**DCGAN**) 
with convolutional discriminator & deconvolutional generator. Though some details are ignored in the implementation. The architecture of DCGAN is shown as below,
<p align="center">
<img src="imgs/DCGAN.png" width="750" height="280"><br/>
<i>Figure 1</i>, architecture of DCGAN.<br/><br/>
</p>

Inside the gan.py, the *function* of **main** pretrains a discriminator and trains discriminator & generator simultaneously while discriminator & generator 
are defined in *functions* of **discriminator** & **generator** respectively. For the ease of free computation, *function* of **load_generate** is defined to load the pretrained model on MNIST images and generate fake MNIST images as real as possible.

To illustrate convolution & deconvolution clearly, the images are shown as below,
<p align="center">
<img src="imgs/convolution.gif" width="250" height="180"><br/>
<i>Figure 2</i>, convolution.<br/><br/>
<img src="imgs/deconvolution.gif" width="230" height="200"><br/>
<i>Figure 3</i>, deconvolution.<br/><br/>
</p>
