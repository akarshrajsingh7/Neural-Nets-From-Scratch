# Neural Networks from Scratch in NumPy

This repository provides a comprehensive implementation of Feedforward Neural Networks (FNN), Convolutional Neural Networks (CNN), and Recurrent Neural Networks (RNN) using only the NumPy library in Python. Understanding the fundamentals of these neural network architectures is crucial for gaining insights into deep learning.

## Introduction

This repository contains the code for building and training neural networks from scratch using NumPy. The implementations cover three fundamental types of neural networks:

1. **Feedforward Neural Network (FNN):** A basic fully connected neural network. (Layers/FullyConnected.py)
2. **Convolutional Neural Network (CNN):** Specifically designed for image-related tasks. (Layers/Conv.py)
3. **Recurrent Neural Network (RNN):** Suitable for sequential data. (Layers/RNN.py & Layers/BatchNormalization.py)

Each implementation is modular and can be easily extended or customized for specific use cases.

## Structure

The repository is organized as follows:

- `Layers`: Contains the implementation of FNN, CNN, and RNN. <br>
>	1. Different layers in CNN like - Conv.py, Pooling.py, Flatten.py, Initializers.py <br>
> 2. Different components in a Simple RNN like - BatchNormalization.py, RNN.py, Dropout.py<br>
> 3. Different activations - ReLU.py, Sigmoid.py, Softmax.py, TanH.py<br>
- `Optimization`: Includes implementation <br>
> 1. Different optimizers of weights like Sgd, Adam, Sgd with Momentum (Optimizers.py)<br>
> 2. L1 and L2 regularizers (Constraints.py)<br>
> 3. Cross-Entropy Loss (Loss.py)<br>

## Contributing

Feel free to contribute by opening issues, suggesting improvements, or directly submitting pull requests. Your contributions are highly valued!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
