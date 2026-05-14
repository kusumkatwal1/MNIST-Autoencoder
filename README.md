# Simple MNIST-Autoencoder
This project implements a simple autoencoder using TensorFlow and Keras to reconstruct handwritten digit images from the MNIST dataset.
          => handwritten digit image → encoder → latent vector → decoder → reconstructed digit
          
## Overview
The model uses an encoder-decoder neural network architecture to learn compressed representations of handwritten digits and reconstruct them with minimal loss.

## Features
    - Deep learning autoencoder model
    - MNIST handwritten digit reconstruction
    - Encoder and decoder architecture
    - Image preprocessing and normalization
    - Reconstruction visualization using Matplotlib

## Technologies Used
    - Python
    - TensorFlow
    - Keras
    - NumPy
    - Matplotlib
    - Jupyter Notebook

## Project Goal
The goal of this project is to understand how neural network-based autoencoders work for image compression and reconstruction.

## Skills Demonstrated
    - Deep Learning
    - Neural Networks
    - Autoencoders
    - Machine Learning
    - Data Preprocessing
    - Image Reconstruction

# Big Picture Workflow:
    1. Install tools
    2. Import libraries
    3. Load MNIST data
    4. Normalize image values
    5. Show example digits
    6. Build an encoder
    7. Build a decoder
    8. Join them into an autoencoder
    9. Train model
    10. Test reconstruction
    11. Generate digit
    12. Interpolate between digits
    13. Save model
    14. Extend idea to time-series heat data
