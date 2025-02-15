# **GAN-and-DCGAN-Architectures**

## Overview

This repository contains implementations of two projects showcasing Generative Adversarial Networks (GANs) for generating image data. Both projects leverage TensorFlow/Keras and explore different architectures to generate synthetic images.

### 1. **Simple GAN for MNIST**
![GAN](images/GANs.png)
   - Implements a basic GAN architecture to generate synthetic handwritten digits using the MNIST dataset.
   - The GAN consists of:
     - **Generator**: A feedforward neural network that learns to generate realistic-looking images.
     - **Discriminator**: A binary classifier distinguishing between real and generated images.
   - The training process involves adversarial learning, where the generator improves by "fooling" the discriminator.

### 2. **DCGAN for Fashion MNIST**
![DCGAN](images/DCGAN.png)
   - Implements a Deep Convolutional GAN (DCGAN) to generate synthetic fashion-related images using the Fashion MNIST dataset.
   - Key Features of DCGAN:
     - Convolutional and transposed convolutional layers in the generator.
     - Leaky ReLU activations and batch normalization for stable training.
     - Enhanced architecture for generating higher-quality images compared to the simple GAN.

---

## Requirements

To run both projects, ensure the following dependencies are installed:

- Python 3.8+
- TensorFlow 2.0+
- NumPy
- Matplotlib

You can install the required packages using:

```bash
pip install tensorflow numpy matplotlib
```

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your_username/GAN-and-DCGAN-Architectures.git
cd GAN-and-DCGAN-Architectures
```

### Running the Simple GAN
1. Open the script in jupyter notebook:
   ```bash
   GANs for MNIST.ipynb
   ```
2. Outputs:
   - Generated images will be saved in the specified directory.
   - Training logs will be displayed on the console.

### Running the DCGAN
1. Open the script in jupyter notebook:

   ```bash
   DCGANS for Fashion_MNIST.ipynb
   ```
3. Outputs:
   - Generated images will be saved in the specified directory.
   - Training logs will be displayed on the console.

---

## Repository Structure

```
GAN-and-DCGAN-Architectures/
|
|-- GANs for MNIST.ipynb              # Implementation of Simple GAN
|
|-- DCGANS for Fashion_MNIST.ipynb    # Implementation of DCGANS
|
|-- README.md
|-- Images                            # Results and Architecture Images
```

---

## Results

### Simple GAN for MNIST
Sample generated images after training:

![Simple GAN Results](images/mnist_results.png)

### DCGAN for Fashion MNIST
Sample generated images after training:

![DCGAN Results](images/fashionmnist_results.png)

---

## License

This repository is licensed under the MIT License.

---

## Acknowledgments

- [TensorFlow Documentation](https://www.tensorflow.org/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements or new features.
