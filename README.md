# Flower Classification using CNN 🌸

This project implements a **Convolutional Neural Network (CNN)** to automatically classify various flower species. By processing visual data through multiple neural layers, the model learns to identify unique botanical features for accurate recognition.

## 🚀 Project Overview
Deep learning has revolutionized image recognition. In this project, we built an end-to-end pipeline including data preprocessing, augmentation, and a custom CNN architecture to achieve high classification performance.

## 📊 Dataset & Interactive Notebook
Since the visual assets and large-scale training plots are hosted on Kaggle, you can access the full interactive environment here:

🔗 **[View Project on Kaggle](https://www.kaggle.com/datasets/harshjaglan01/image-classification-by-cnn)**

*Note: The Kaggle link contains the original dataset, training logs, and high-resolution performance charts (Accuracy/Loss).*

## Technical Stack
* **Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Data Processing:** NumPy, Pandas, Scikit-learn
* **Visualization:** Matplotlib, Seaborn

## Model Architecture
The model consists of a sequential flow designed for optimal feature extraction:
1. **Convolutional Layers:** To capture spatial features (edges, shapes).
2. **Pooling Layers:** To reduce dimensionality and computational load.
3. **Dropout:** To prevent overfitting and improve generalization.
4. **Dense Layers:** Final classification using Softmax activation.

## ⚙️ Installation
To run this project locally:
1. Clone the repo: `git clone https://github.com/username/project.git`
2. Install requirements: `pip install tensorflow numpy matplotlib`
3. Run: `python main.py`

---
*Created for deep learning research and portfolio purposes.*
