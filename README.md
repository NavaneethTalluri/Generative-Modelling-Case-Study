## 📖 Overview

This project builds **Generative Adversarial Networks (GANs)** from scratch and applies them to synthetic data, medical images, cybersecurity traffic, and creative sketches.

## ⚙️ Key Tasks

### 🔹 1. Sine Wave GAN

Learned noisy sine distribution: y = sin(x) + epsilon

### 🔹 2. Conditional GAN (Curve Learning)

Modeled function:

y = sin(2x) + 0.3cos(5x) + epsilon

### 🔹 3. Improved GAN

* Deeper network + BatchNorm
* More stable and realistic outputs

## 🌍 Applications

### 🧬 Medical Imaging

* WGAN-GP on BloodMNIST
* Evaluated with FID

### 🔐 Cybersecurity

* GAN for synthetic network traffic
* Evaluated using t-SNE & statistical metrics

### 🎨 Creative AI

* DCGAN for generating pizza sketches

## 🧠 Key Insights

* GANs learn data distributions
* Training stability is critical
* Architecture strongly impacts performance

## 🚀 Tech Stack

PyTorch, NumPy, Matplotlib, Scikit-learn, MedMNIST

## 🧾 Conclusion

End-to-end GAN pipeline from simple data to real-world use cases, showing both capabilities and challenges of generative models.
