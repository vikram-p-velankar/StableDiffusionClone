# Generative Models for Image Synthesis
Advanced Data Mining Project (CIS 5700) — Winter 2025 (Dr. Srijita Das)

This repository contains a comprehensive exploration and implementation of generative models for image synthesis, including Generative Adversarial Networks (GANs) and Diffusion Models, along with their evaluation using widely-accepted metrics.

## 📘 Overview
The project is centered around building and evaluating generative models that learn to produce high-quality images. The key components of this project include:

GANs: Implementations of standard and advanced GAN architectures.

Diffusion Models: Step-wise generative modeling using noise scheduling and denoising techniques.

Evaluation: Use of metrics such as Inception Score (IS) and Fréchet Inception Distance (FID) to quantify the performance of generated images.

## 📂 Contents
Adv_Data_Mining_Proj.ipynb: The main Jupyter notebook containing:

Implementation of GANs and Diffusion models.

Training processes on image datasets.

Visualization of generated outputs.

Evaluation of model performance.

## 📦 Requirements
To run the notebook, you will need the following Python packages:

```bash
torch
torchvision
numpy
matplotlib
tqdm
scipy
Pillow
scikit-learn
seaborn
Install them using:
```
```bash
pip install torch torchvision numpy matplotlib tqdm scipy Pillow scikit-learn seaborn
You may also need Jupyter:
```
bash
```pip install notebook```
## 🧪 Evaluation Metrics
We used the following metrics to evaluate the performance of the generative models:

Inception Score (IS): Measures the quality and diversity of generated images.

Fréchet Inception Distance (FID): Compares the distribution of generated images with real images.

## 📊 Results
Generated outputs were visually assessed and quantitatively evaluated using IS and FID. Key findings and comparisons between GANs and Diffusion models are included in the notebook.

## 👨‍💻 Contributors
Vikram Velankar (vikramdv@umich.edu)
Implementation of GAN and Diffusion models

Shashank Chauhan (shashanc@umich.edu)
Evaluation metrics implementation and analysis

## 📝 License
This project is released for academic and research purposes.
