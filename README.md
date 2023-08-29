# Neural Network for Digit Classification

## Overview

In this project at Carnegie Mellon University, I implemented a neural network from scratch for hand-written digit classification and later enhanced its capabilities using the PyTorch framework. The assignment spanned from deep dives into network initialization and gradient computation to practical applications in a modern deep learning environment.

This project was part of my assignment from the computer vision course i am taking from Carnegie Melon University. All code belongs to Carnegie Melon University

## Learning Objectives

- Thoroughly understand the architecture and functionality of neural networks.
- Design, implement, and train a deep neural network from scratch.
- Transition to PyTorch, a modern deep learning framework, for classifying hand-written digits.

## Assignment Breakdown

### Part I: Implement a Fully-connected Neural Network [100 pts]

- **Network Initialization (Xavier) [0 pts]**
  - Explored and implemented Xavier initialization to ensure weights are optimized for the activation function, leading to a more efficient training process.

- **Sigmoid Activation Function [10 pts]**
  - Designed and integrated the Sigmoid function, a foundational activation function, to introduce non-linear properties to the model.

- **Softmax Function [15 pts]**
  - Implemented the Softmax function to transform the network's raw output scores into probabilities, aiding in multi-class classification.

- **Loss Function (Cross-Entropy) [15 pts]**
  - Incorporated the Cross-Entropy loss function, ensuring a measure of the difference between the network's predictions and the actual labels.

- **Forward Pass [20 pts]**
  - Implemented the forward propagation mechanism, allowing the network to make predictions based on input data and initialized weights.

- **Gradient Computation [20 pts]**
  - Computed gradients essential for the backward propagation step, enabling the optimization of the model's weights.

- **Backward Propagation [0 pts]**
  - Orchestrated the backward pass, a vital process where the network learns by adjusting its weights based on the computed gradients.

- **Train Models with NIST36 [20 pts]**
  - With all the components in place, trained the neural network on the NIST36 dataset, witnessing the model learn and improve its accuracy over iterations.

### Part II: PyTorch for Digit Classification [0 pts]

- **PyTorch Installation [0 pts]**
  - Transitioned to the PyTorch framework, experiencing the ease of setting up and running models on this platform.

- **Train Models with NIST36 (PyTorch) [0 pts]**
  - Leveraged PyTorch's capabilities to train models on the NIST36 dataset, appreciating the simplification and speedup offered by the framework.

### Network Visualization and Performance:

- The model achieved an accuracy of 78 %
## visualization of output layer 
![download 1](https://github.com/sankalp-rajeev/hand-written-digit-classification/assets/81537336/085778aa-ab4b-47b1-a171-66700c2c76b2)

## Confusion Matrix generated:
![download 3](https://github.com/sankalp-rajeev/hand-written-digit-classification/assets/81537336/dbf15be1-95a1-48ef-9664-fcbdb3d58a3d)


## Insights & Takeaways

- Gained a profound understanding of neural networks, from the basics of activation functions to the complexities of forward and backward propagation.
- Witnessed firsthand the advantages of using modern deep learning frameworks like PyTorch – from reducing boilerplate code to GPU acceleration.

## Acknowledgments

I'm immensely grateful to my professors and peers at Carnegie Mellon University for their invaluable guidance, insights, and constructive feedback throughout this project.
