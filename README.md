# gan_project

## Cycle GAN
Image-to-image translation is the task of transforming an image from one domain (e.g., images of zebras), to another (e.g., images of horses). Cycle GAN (Generative Adversial Network) is used for Image to Image Translation. CycleGAN  uses two generators and two discriminators. 

We call one generator G, and have it convert images from the X domain to the Y domain. The other generator is called F, and converts images from Y to X. Each generator has a corresponding discriminator, which attempts to tell apart its synthesized images from real ones.

There are two components to the CycleGAN objective function, an adversarial loss and a cycle consistency loss.

## Project Details

In this project I haved used  the following:

- I have used Cycle GAN to perform face aging of persons by convert face of people in 20-30 age group to 50-60 agegroup and vice versa.
- I have used datasets from UKN which has datasets for of images of persons across the world and each file name has age mentioned.
- I have put all the persons having age 20-30 kept in folder datasets/face_aging/trainA_temp and all the persons in age group 50-60 I have kept in folder datasets/face_aging/trainA_temp.
- I have extracted only face for persons using MTCNN openCV library 
- Used ResNet Generator and  PatchGAN Discriminator .
- Trained for 90 epochs

## Results

Here are the results after 90 ecochs. First row shows original face, second row when the face is transformed to other age groups (i.e. 20-30 age group for 50-60 age group person, 50-60 age group for 20-30 age group persons), thir row shows when the image is transformed back to original age group

![GAN Images](/epoch90.png)







