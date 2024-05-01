# GAN

Notes: https://pouncing-digit-011.notion.site/GAN-6198b02d70734d28b7622e2feee44f1c?pvs=4

## Overview
This repository hosts a cutting-edge Generative Adversarial Network (GAN) implemented in Python, showcasing the model’s ability to generate new, synthetic instances of data that are indistinguishable from real data.

## Implementation
The MNIST dataset was used as samples in this project. The GAN model contains 2 parts: generator and discriminator. In a nutshell, the generator was used for generating images, and the discriminator was used for determining whether the image is fake. The generator would try to generate a very fake image to trick the discriminator, and the discriminator would improve to detect exactly the fake image during training.

The core of the project is contained in the jupyter notebook file (GAN.ipynb). After each 1000 epochs, the result of training process is saved in the folder (gan_images). In particular, I generated 25 new images from trained model after each 1000 epochs and saved them with corresponding name. 

## Evaluation
After 30000 epochs, the model generated successfully new data which is similar to MNIST dataset.