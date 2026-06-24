# 📈 Corporate Bankruptcy Prediction — PyTorch vs TensorFlow

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)

> A comparative deep learning study — building the same ANN bankruptcy prediction model in both PyTorch and TensorFlow/Keras to benchmark framework performance.

---

## 📌 Problem Statement
Two of the most popular deep learning frameworks — PyTorch and TensorFlow — have different APIs, training loops, and behaviors. This project implements identical ANN architectures in both frameworks to compare ease of use, training speed, and accuracy on a financial classification task.

## 🎯 Framework Comparison
| Aspect | PyTorch | TensorFlow/Keras |
|--------|---------|-----------------|
| API Style | Dynamic graph | Static/dynamic graph |
| Training Loop | Manual | fit() method |
| Flexibility | High | High (with tf.GradientTape) |
| Task | Bankruptcy Classification | Bankruptcy Classification |

## 🛠️ Tech Stack
- **Language:** Python
- **Deep Learning:** PyTorch, TensorFlow, Keras
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📂 Project Structure
```
bankruptcy-prediction-pytorch-tensorflow/
├── Bankrupt_Prediction_Pytorch_TensorFlow/
│   ├── data/      # Financial dataset
│   ├── python/    # PyTorch & TensorFlow notebooks
│   └── README.md
└── README.md
```

## 🚀 How to Run
```bash
# 1. Clone the repo
git clone https://github.com/shreesneha056-gif/bankruptcy-prediction-pytorch-tensorflow.git
cd bankruptcy-prediction-pytorch-tensorflow

# 2. Install dependencies
pip install torch tensorflow keras pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Launch Jupyter
jupyter notebook
```

## 📊 Pipeline Overview
1. **Data Loading & EDA** — Explore financial indicators dataset
2. **Preprocessing** — Handle missing values, normalize features
3. **PyTorch Model** — Build, train, and evaluate ANN in PyTorch
4. **TensorFlow Model** — Build, train, and evaluate identical ANN in Keras
5. **Framework Comparison** — Accuracy, training time, code complexity

---
📫 [Connect on LinkedIn](https://www.linkedin.com/in/sneha-shree-mu/) | [Portfolio](https://shreesneha056-gif.github.io/portfolio_website/)
