# Vanilla Autoencoder

This repository contains an implementation of a vanilla autoencoder using TensorFlow. A vanilla autoencoder is a simple neural network used to learn efficient representations of data, typically for the purpose of dimensionality reduction or feature learning.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Autoencoders are unsupervised learning models that aim to learn a compressed representation of input data. This project demonstrates a simple vanilla autoencoder for image data, using the MNIST dataset as an example.

## Installation

To run this project, you need to have Python and the following packages installed:

- TensorFlow
- NumPy
- Matplotlib

You can install the required packages using pip:

pip install tensorflow numpy matplotlib

## Usage

To train the vanilla autoencoder, run the following command:

Download the ipynb file and run it in Google Colab or on your local machine.

## Dataset

The project uses the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits. The dataset is automatically downloaded using TensorFlow's dataset utilities.

## Model Architecture

The vanilla autoencoder consists of:

- **Encoder**: A dense layer with ReLU activation that compresses the input data.
- **Decoder**: A dense layer with sigmoid activation that reconstructs the input data from the compressed representation.

## Training

The model is trained using the Adam optimizer and binary cross-entropy loss. The training script includes options for setting the number of epochs and batch size.

## Results

After training, the autoencoder can be used to encode and decode images, effectively reducing the dimensionality of the data while preserving important features.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.