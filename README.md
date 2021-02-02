# gan_project

## Cycle GAN
Image-to-image translation is the task of transforming an image from one domain (e.g., images of zebras), to another (e.g., images of horses). Cycle GAN (Generative Adversial Network) is used for Image to Image Translation. CycleGAN  uses two generators and two discriminators. 

We call one generator G, and have it convert images from the X domain to the Y domain. The other generator is called F, and converts images from Y to X. Each generator has a corresponding discriminator, which attempts to tell apart its synthesized images from real ones.

There are two components to the CycleGAN objective function, an adversarial loss and a cycle consistency loss.

## Project Details

In this project I haved used  the following:

- Cycle GAN to convert photos of people in 20-30 age group to 50-60 agegroup and vice versa. 
- Used MTCNN to get the face of people





