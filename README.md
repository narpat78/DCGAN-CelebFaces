# DCGAN-CelebFaces
This project implements a **Deep Convolutional Generative Adversarial Network (DCGAN)** using **PyTorch** to generate realistic face images, trained on the CelebA dataset. The model is trained on the CelebA dataset and demonstrates the fundamental principles of adversarial training between a Generator and a Discriminator.

### Project Highlights

- Trains a DCGAN model with custom Generator and Discriminator networks.
- Initializes weights as per the DCGAN paper (Normal(0, 0.02)).
- Uses Binary Cross Entropy (BCE) loss for adversarial training.
- Visualizes intermediate samples to track model progression.
- Saves generated images and training samples for post-analysis.
