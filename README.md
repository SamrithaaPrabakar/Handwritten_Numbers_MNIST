
# Handwritten_Numbers_MNIST
# 🖊️ Handwritten Character Recognition (Feedforward Neural Network)

This project implements a **simple Feedforward Neural Network (FFNN)** using **TensorFlow/Keras**  
to recognize handwritten digits from the **MNIST dataset** (0–9).

---

## 🚀 Features
- Feedforward NN with **2 hidden layers** (128 and 64 neurons).
- **ReLU activation** for hidden layers, **Softmax** for output.
- **Accuracy evaluation** on test set.
- **Visualization** of sample predictions.
- **ROC curves** with AUC for all 10 classes.

---

## 📂 Project Structure
handwritten-character-recognition/
│
├── notebooks/ # Colab notebooks
│ └── mnist_ffnn.ipynb
│
├── src/ # Python modules
│ ├── model.py # model building
│ ├── visualize.py # visualization + ROC curve
│
├── main.py # training + evaluation script
├── requirements.txt # dependencies
├── README.md # this file
└── .gitignore


---

python main.py

