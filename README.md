# fashion-mnist-ann-scratch
Manual implementation of an Artificial Neural Network from scratch using only NumPy — trained on MNIST and Fashion-MNIST datasets. No frameworks, just raw math and code.

👨‍💻 What is this?
This repo is me trying to understand how neural networks actually work — no frameworks doing magic behind the scenes.

It classifies clothes from the Fashion MNIST dataset using:

✍️ Handwritten backpropagation

⚙️ Forward pass + ReLU + Softmax

🧠 Two-layer fully connected network

📊 25k image dataset

🔍 Pure Numpy. No cheats

Input Layer:     784 neurons (28x28 flattened)
Hidden Layer 1:  64 neurons (ReLU)
Hidden Layer 2:  32 neurons (ReLU)
Output Layer:    10 neurons (Softmax)

📈 Results
Accuracy: Around 85%+ on training data

No overfitting techniques yet — kept it raw

You can visualize predictions live


