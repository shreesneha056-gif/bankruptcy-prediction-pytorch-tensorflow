# DataScience_DeepLearning----TensorFlow_PyTorch----Bankrupt_Prediction_Pytorch_TensorFlow
# Corporate Bankruptcy Classification: A Framework Comparison (PyTorch vs. TensorFlow)

An end-to-end Deep Learning classification project designed to predict corporate bankruptcy metrics based on dynamic financial performance indicators. This repository features a comprehensive, parallel data science pipeline that constructs, optimizes, and evaluates sequential Artificial Neural Networks (ANN) across the industry's two main frameworks: **PyTorch** and **TensorFlow / Keras**.

## 🚀 Project Overview
Predicting financial distress is a critical classification risk problem requiring models capable of separating highly imbalanced decision boundaries. This project implements a standardized preprocessing workflow to ingest structural corporate indices, normalize multi-variance metrics, and train equivalent neural network architectures side-by-side to observe framework execution behaviors and optimization patterns.

## 📂 Repository Structure
* **`python.ipynb`**: The master Jupyter Notebook containing exploratory data handling, input pipeline engineering, and parallel deep learning training flows.
* **`data.csv`**: The operational dataset containing financial records, liquidity rates, operating margins, and asset performance metrics.

## 📊 Pipeline & Preprocessing Workflow
1. **Data Ingestion**: tabulates extensive features from `data.csv` isolating historical performance ratios (such as ROA, growth margins, working capital weights, and debt ratios).
2. **Feature Engineering & Imbalance Treatment**: 
   * Segregates the risk feature space from the native classification target (`Bankrupt?`).
   * Handles categorical indices and standardizes raw numeric inputs to ensure stable gradient propagation.
3. **Data Partitioning**: Standardizes feature sets via Scikit-Learn tools into discrete training and validation partitions to track model generalization.

## 🧠 Model Architecture & Dual-Framework Implementation
To preserve comparison validity, the network parameters remain identical across both framework builds:
* **Layer Topology**: Constructed as a dense fully connected sequence containing hidden processing layers wired via Rectified Linear Unit (`ReLU`) continuous activations.
* **Output Node**: Employs a single sigmoid prediction neuron to calculate discrete bankruptcy probabilities.
* **Compilation Protocols**: Standardized via the **Adam** gradient descent optimizer variant, minimizing Binary Cross-Entropy loss objectives.

### Framework Details:
* **TensorFlow / Keras Build**: Constructed using the direct Keras `Sequential` layer stack configuration tracking performance metrics automatically.
* **PyTorch Module Subclassing**: Built cleanly by subclassing `nn.Module`. Inputs are explicitly cast to PyTorch continuous float tensors (`torch.float32`), with training metrics executed via an explicit programmatic gradient training loop.

## 🛠️ Tech Stack & Requirements
* **Core Language:** Python
* **Deep Learning Frameworks:** PyTorch (`torch`, `torch.nn`), TensorFlow / Keras
* **Machine Learning & Preprocessing:** Scikit-Learn
* **Data Wrangling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 📈 Evaluation & Statistical Reporting
The performance of the models is tracked directly via Scikit-Learn metric matrices:
* Detailed performance snapshots are compiled using standard **Classification Reports**.
* Models are verified using exact classification arrays tracking precision distributions, recall thresholds, and F1-score balances for operational transparency.

## 🚀 Getting Started Locally

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
cd YOUR_REPOSITORY_NAME
