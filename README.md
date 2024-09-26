# Captcha Solver 🔍

This project leverages basic image manipulation techniques and a Convolutional Neural Network (CNN) trained on the EMNIST dataset to solve CAPTCHA images.

## Overview 📜

- The **`Captcha_solver`** notebook contains all the relevant code for solving CAPTCHA images.
- The **`EMNIST_CNN`** notebook contains the code for training the CNN using the EMNIST dataset, which is a variant of the MNIST dataset designed for character recognition (including both digits and letters).

## Key Features 🧠

- **Captcha Solver**: Utilizes image processing techniques such as thresholding and contour detection to segment CAPTCHA characters.
- **CNN Model**: Trained on the EMNIST dataset for accurate character classification.
- **End-to-End Pipeline**: From image preprocessing to character recognition, the solver automatically cracks CAPTCHA images.

## Captcha Examples 🎯

Here are some CAPTCHA examples that the model successfully solved:

![Solved CAPTCHA](https://github.com/user-attachments/assets/9185d6a1-c3fe-464d-b451-d3e0d3518ff2)

You can generate this display by running the last cell in the **Captcha_solver** notebook.


## Future Improvements 🌟

- Support for more complex CAPTCHA structures.
- Fine-tuning the CNN architecture for better accuracy.
