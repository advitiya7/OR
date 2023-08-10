# Handwritten Digit Recognition Model without TensorFlow

This repository contains a Python script that demonstrates a handwritten digit recognition model using the MNIST dataset. The model is implemented without using TensorFlow and is trained to classify handwritten digits into their respective numerical values.

1. Loading and Preprocessing the Data:
   - The MNIST dataset is loaded using the `datasets.load_digits()` function from `scikit-learn`.
   - The images are flattened and normalized to values between 0 and 1.

2. Custom Model Definition:
   - A custom model class, `CustomModel`, is defined to implement the handwritten digit recognition model.
   - The model architecture includes input and output layers, as well as one or more hidden layers.
   - Activation functions, weights, and biases are manually defined and updated during training.

3. Training the Model:
   - The model is trained using the training images and labels.
   - Training involves forward and backward propagation, updating weights and biases using a chosen optimization algorithm (e.g., gradient descent).

4. Evaluation and Testing:
   - The trained model is evaluated using the test images and labels.
   - - Accuracy metrics are calculated to measure the model's performance.
  
   ## Prerequisites
- `numpy` library: Install it using `pip install numpy`
- `matplotlib` library: Install it using `pip install matplotlib`
- `scikit-learn` library: Install it using `pip install scikit-learn`
  ## Results

The model achieves an accuracy of approximately 97-98% on the test set, demonstrating its effectiveness in recognizing handwritten digits.

