
# Digit Image Feneration

This Generative Adversial Model is trained on MNIST. This model is made as part of the deep learning specialization on coursera.


## Techstack
Python, Pytorch, TorchVision, Matplotlib

## Architecture

### Generator Block
- ConvTranspose2d
- BatchNorm2d
- ReLu

### Discriminator Block
- Conv2d
- BatchNorm2d
- LeakyReLU

### Generator Model Layers
- Generator Block
- Generator Block
- Generator Block
- Generator Block
- ConvTranspose2d
- Tanh

### Discriminator Model Layers
- Discriminator Block
- Discriminator Block
- Discriminator Block
- Conv2d

## Results

This is the after step 1000:
![image](https://github.com/user-attachments/assets/cb8d7621-5416-4383-b211-596e46d87102)


This is after training the model for 400 epochs:
![image](https://github.com/user-attachments/assets/85b0b0bc-e2d7-4769-9a08-fb8b0a2def5d)



