# 🚀 SpaceAI: Predicting Ion Distributions in Space with Neural Networks

[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-EE4C2C.svg?logo=pytorch)](https://pytorch.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-📓-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 🌌 Overview

**SpaceAI** is a research project that leverages **deep learning** to predict **ion energy distributions in near-Earth space**.  
We benchmark and compare four neural network architectures:

- **MLP** (Multi-Layer Perceptron)  
- **CNN** (Convolutional Neural Network)  
- **LSTM** (Long Short-Term Memory)  
- **Transformer**  

| Model           | Strengths                        | Limitations                            |
| --------------- | -------------------------------- | -------------------------------------- |
| **MLP**         | Fast, simple, easy to train      | Limited in capturing temporal features |
| **CNN**         | Good at local feature extraction | Less effective on sequential patterns  |
| **LSTM**        | Handles sequential dependencies  | Slower training, harder to tune        |
| **Transformer** | Captures long-range dependencies | Requires more compute & tuning         |



The models are trained using ion flux datasets from NASA missions and aim to improve **space weather forecasting**.

📄 This project is associated with the publication:  
> Li, J. et al. (2025). *Modeling ring current proton distribution using MLP, CNN, LSTM, and Transformer networks.* Frontiers in Astronomy and Space Science.  
[🔗 Read the paper](https://doi.org/10.3389/fspas.2025.1629056)

---

## 📂 Repository Structure

spaceai/
│── lws_training_display_torch_mlp_55keV.ipynb # MLP training notebook
│── lws_training_display_torch_cnn_55keV_v2.0.ipynb # CNN training notebook
│── lws_training_display_torch_lstm_268keV_v2.01.ipynb# LSTM training notebook
│── lws_transformer_55keV_v1.7_2.ipynb # Transformer training notebook
│── README.md # Project documentation
│── LICENSE # Open source license
