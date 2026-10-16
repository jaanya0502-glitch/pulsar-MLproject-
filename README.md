# 🌌 Pulsar Detection System

## 🔭 Project Overview
This project implements a Machine Learning pipeline to classify radio signals from space as either **Pulsars** or **Noise**. Using the HTRU2 dataset, the system identifies rare pulsar signals within a noisy interstellar background.

## 🛠 Technical Workflow
- **Standardization:** Used `StandardScaler` to ensure all signal measurements are on the same scale.
- **Class Imbalance Handling:** Implemented **Class Weighting** to prioritize the detection of the rare pulsar signals.
- **Architecture:** Implemented a Neural Network with a Sigmoid output for probability mapping.
- **Optimization:** The **Adam** optimizer was used for stability and efficiency.
- **Threshold Tuning:** Optimized the decision boundary to maximize the detection rate (Recall) of pulsars.

## 📊 Key Results
The final model is evaluated using a **Classification Report**, measuring Precision, Recall, and the F1-Score.
