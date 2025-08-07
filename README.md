"If you use this code, please cite: Himanshu Tiwari, Dr. Mahipal Jetta.
"RaFT-PDE: A Deep Prior-Free Framework for Unsupervised Vision Restoration in Medical Imaging", 2025."

# RaFT-PDE
Code for RaFT-PDE image restoration model
# RaFT-PDE: A Deep Prior-Free Framework for Image Denoising under Multiplicative Speckle Noise

This repository contains the official implementation of the **RaFT-PDE** model, a fully unsupervised, deep-learning-free image restoration method tailored for multiplicative speckle noise in modalities like **ultrasound** and **SAR imaging**.

---

##  Overview

RaFT-PDE (Ratio-guided Fractional-Time Partial Differential Equation) is a handcrafted image denoising method based on:

- Contrast-aware anisotropic diffusion
- Dynamic ratio prior (computed from the noisy image itself)
- Fractional-time evolution (memory-preserving)
- No reliance on DIP, deep learning, or training data

---

##  Key Features

-  **Unsupervised**: No clean images or learning required  
-  **Mathematically interpretable**: Based on PDEs and gradients  
-  **Lightweight**: Can run on CPU  
-  **Robust to noise**: Especially effective on gamma speckle noise

---

##  Dependencies

Install the following Python libraries before running:

```bash
pip install numpy matplotlib scikit-image scipy
