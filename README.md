![Uploading image.png…]()
# Neural Network Training with PyTorch

This project implements a simple **feedforward neural network** using **PyTorch**, with two hidden layers and a final output layer. The model is trained using **backpropagation** and **Stochastic Gradient Descent (SGD)** to minimize the mean squared error (MSE).

## Features
-  **CUDA Support** – Runs on GPU if available for faster training.
-  **Optimized Training** – Uses `torch.optim.SGD` instead of manual weight updates.
-  **ReLU Activation** – Applied in hidden layers to improve gradient flow.
-  **Loss Curve Visualization** – Plots the loss function over training epochs.

## Project Structure
- **CustomModel**: A neural network with manually initialized weights.
- **Training Loop**: Iteratively updates weights using SGD.
- **Loss Function**: Mean Squared Error (MSE) for evaluation.
- **Visualization**: A matplotlib plot shows loss reduction over time.

## Installation & Usage
1. Install dependencies:
   ```bash
   pip install torch matplotlib
   ```  
2. Run the script:
   ```bash
   python train.py
   ```  
3. View the loss curve to monitor training progress.

## Requirements
- Python 3.7+
- PyTorch
- Matplotlib

- ## Author
![Untitled-3](https://github.com/user-attachments/assets/ff01ecca-2503-4f91-825f-c9e641e795fd)
