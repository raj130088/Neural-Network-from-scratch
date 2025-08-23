# Neural Network from Scratch (NumPy Only)

This project is a **complete neural network implementation from scratch** — built entirely in **Python + NumPy** with **no deep learning frameworks** (no TensorFlow, no PyTorch).  

The focus is on **learning by doing**: every part of the network — layers, activations, forward pass, backpropagation, optimizers, and regularization — is coded manually to demystify the internals of modern deep learning.

---

## Key Highlights

- **Everything implemented from scratch**  
  - Dense layers, activation functions, loss functions, optimizers, and regularization — all coded manually.  
- **Object-Oriented Design**  
  - Classes for layers, activations, losses, and optimizers (mirroring pro ML frameworks).  
- **Full Forward & Backward Pass**  
  - Predictions via forward propagation  
  - Gradient calculation via backpropagation  
- **Modern Optimizers Implemented from Scratch**  
  - SGD (with Momentum + LR decay)  
  - AdaGrad  
  - RMSprop  
  - Adam  
- **Regularization**  
  - L1 & L2 (weight decay)  
  - Dropout layers  
- **Dataset**  
  - Trained on the **Spiral dataset** (classic non-linear classification problem).

---

## Architecture and Concepts Covered

### 1. Forward Pass
- `Layer_Dense` → fully-connected layers  
- `Activation_ReLU` → introduces non-linearity  
- `Activation_Softmax` → converts logits to probabilities  
- `Loss_CategoricalCrossentropy` → measures classification error  

### 2. Backward Pass (Backpropagation)
- Manual gradient derivation using the **chain rule**  
- Backward methods for every component: layers, activations, loss  

### 3. Optimization
- **Custom optimizers** coded from scratch:  
  - SGD, SGD + Momentum, AdaGrad, RMSprop, Adam  

### 4. Generalization & Regularization
- Overfitting demonstrations  
- **Scratch implementations** of:  
  - L1 & L2 regularization  
  - Dropout  

---

## How to Run

### Requirements
- Python 3.x  
- NumPy  
- nnfs (for spiral dataset)

Install:
```bash
pip install numpy nnfs
