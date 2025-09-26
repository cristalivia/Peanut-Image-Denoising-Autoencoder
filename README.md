# Peanut Image Denoising Autoencoder
## Project Overview
When working with image data, noise is a common challenge that reduces quality and makes analysis harder. In this project, I built a **Convolutional Autoencoder** that learns how to remove noise from peanut images and make them clear again.

## Tools
- **Python**: NumPy
- **Deep Learning**: TensorFlow / Keras
- **Data Visualization**: Matplotlib
  
## Approach
- Gaussian noise (mean = 0, std = 0.1) was added to the peanut images to create noisy input for the autoencoder.
- Built an encoder–decoder network that learns important patterns (features) from noisy images.
- Training focused on minimizing reconstruction error (difference between clean and noisy images).

## Results
<img width="885" height="573" alt="image" src="https://github.com/user-attachments/assets/4422a7be-47d2-4d68-ae9b-980ce52b1c2d" />

- The baseline autoencoder removed some noise but lost details, making the outputs blurry.
- The modified autoencoder produced sharper edges and kept more image features.
  
## Conclusion
The project confirms that convolutional autoencoders are effective for image denoising. Small changes in network design made the results much better, and the same approach can be used in other fields like medical images, anomaly detection, or product quality checks.
