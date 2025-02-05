# Handwritten Digit Recognition using Neural Networks

## Overview
This project implements a neural network for handwritten digit recognition using the **MNIST dataset**. The model starts as a simple **single-layer neural network** and progressively evolves into a **multi-layer perceptron (MLP)** for improved performance.

## Features
- **Data Preprocessing:** Scales the MNIST dataset between 0 and 1 for better training efficiency.
- **Neural Network Architectures:**
  - **Single-Layer Model:** A basic network with 10 output neurons and a sigmoid activation function.
  - **One Hidden Layer Model:** A network with one hidden layer (100 neurons, ReLU activation).
  - **Multi-Layer Model:** A deep network with multiple hidden layers (up to 200 neurons per layer) and ReLU activation.
- **Training:**
  - Uses the **Adam optimizer** for adaptive learning.
  - Loss function: **Sparse Categorical Crossentropy**.
  - Evaluates model accuracy on test data.
- **Error Analysis:**
  - Generates a **confusion matrix** to analyze prediction errors.
  - Visualizes misclassifications using **Seaborn heatmaps**.

## Technologies Used
- Python 🐍
- TensorFlow/Keras 🤖
- NumPy 🔢
- Matplotlib 📊
- Seaborn 🔥

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/handwritten-digit-recognition.git
   cd handwritten-digit-recognition
2. Install dependencies:
     pip install tensorflow numpy matplotlib seaborn
3. Run the script

## Usage
1. Modify the model architecture in the script to experiment with different configurations.
2. Train the model by running the code blocks one by one in the script.
3. Evaluate performance using a confusion matrix visualization.

## Results
1. Initial single-layer model achieves basic classification.
2. **Multi-layer perceptron** significantly improves accuracy and generalization.
3. Error analysis highlights common misclassifications, allowing for further optimization.
4. Final Model Accuracy: **96.82%**

## Future Improvements
1. Implement **Convolutional Neural Networks (CNNs)** for better feature extraction.
2. Experiment with different activation functions and optimizers.
3. Fine-tune **hyperparameters** for optimal performance.
