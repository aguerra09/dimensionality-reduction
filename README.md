# Dimensionality Reduction Exploration

This project explores different methods for **dimensionality reduction** using the Wine dataset.

---

## 📑 Index

### 1. `PCA_Wine.ipynb`
- Implements **Principal Component Analysis** from scratch.  
- Uses eigenvalue decomposition of the covariance matrix.  
- Produces the exact solution for projecting data into lower dimensions.  
- Includes explained variance plots to visualize how much information each component captures.

### 2. `LAE_Wine.ipynb`
- Implements a **Linear Autoencoder** in PyTorch.  
- Trains an encoder–decoder architecture with Mean Squared Error (MSE) reconstruction loss.  
- Shows how the learned latent space relates to PCA.  
- Demonstrates that the autoencoder recovers the same subspace as PCA, but possibly rotated.  

---

## 🎯 Project Objective
- Understand how **linear methods** (PCA) and **neural approaches** (Autoencoders) perform dimensionality reduction.  
- Visualize the latent spaces in **2D and 3D** to compare class separability.

---
