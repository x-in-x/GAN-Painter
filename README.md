# GAN-Painter

This is inspired by an ML Kaggle competition entitled *I'm Something of a Painter Myself*, in which one starts with 300 Monet paintings and about 7000 real photos, with the objective of building a Generative Adversarial Network (GAN) consisting of *generator* network which generates blends of a Monet painting and a real photo in order to trick the *discriminator* network, which attempts to predict whether it was a real Monet painting or not. 

Summary of notebooks:

**[GAN-Painter].Preprocessing** - Loading Monet and photo data and converting it to training and testing sets.  Theoretically we don't need a testing set for a GAN; however, we have selected one here for potential related model testing.

**[GAN-Painter].GAN-blend** - Construction and training of the GAN model.  This one gives the generator a kickstart with blended photos, and then feeds it through the hidden-layered generator.  

