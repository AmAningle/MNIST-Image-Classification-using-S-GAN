

---

### Project Overview
- A Semi-Supervised GAN (SGAN) is used to improve classification accuracy with limited labeled data.
- The SGAN architecture leverages both labeled and unlabeled data to classify digits by augmenting the small labeled dataset with generated samples.
- The performance of SGAN is compared with a CNN trained on the same small labeled dataset to evaluate its effectiveness in semi-supervised learning.

### Key Features:
- **SGAN Architecture**: Combines a discriminator for both classification and distinguishing real from generated images.
- **CNN Baseline**: A traditional Convolutional Neural Network is used as a baseline to compare performance against SGAN with few labeled examples.

### Prerequisites
- Python 3.x
- TensorFlow or Keras
- Numpy
- pandas
- Matplotlib

### Results
- The project compares the classification accuracy of CNN and SGAN with few labeled images from the MNIST dataset.
- **Model Accuracy**:
  - CNN: 77.21%
  - SGAN: 93.03%
- SGAN shows an advantage by utilizing both labeled and unlabeled data, while CNN struggles with limited labeled data.

---
