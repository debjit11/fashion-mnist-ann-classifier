# 👕 Fashion MNIST Classifier using ANN 

## 📌 Project Overview

This project focuses on building an **Artificial Neural Network (ANN)** to classify images from the **Fashion MNIST dataset**. The goal is to accurately identify clothing items such as shirts, sneakers, bags, etc., using deep learning techniques.

To improve model performance, **Optuna** is used for **automated hyperparameter tuning**, making the model more efficient and optimized.

---

## 📂 Dataset

The **Fashion MNIST** dataset consists of:

* 70,000 grayscale images (28x28 pixels)
* 10 classes of fashion items:

  * T-shirt/top
  * Trouser
  * Pullover
  * Dress
  * Coat
  * Sandal
  * Shirt
  * Sneaker
  * Bag
  * Ankle boot

Split:

* Training: 60,000 images
* Testing: 10,000 images

---

## ⚙️ Tech Stack

* Python 🐍
* PyTorch 🔥
* Optuna ⚡
* NumPy & Pandas
* Matplotlib / Seaborn (for visualization)

---

## 🧠 Model Architecture

The ANN model is dynamically built using:

* Input Layer (784 features after flattening 28x28 image)
* Multiple Hidden Layers (customizable)
* Activation Function: ReLU
* Dropout for regularization
* Output Layer: 10 classes

---

## 🚀 Hyperparameter Tuning (Optuna)

We use **Optuna** to find the best parameters automatically.

### Tuned Parameters:

* Number of hidden layers
* Neurons per layer
* Learning rate
* Dropout rate
* Optimizer choice

### Objective:

Maximize validation accuracy while preventing overfitting.

---

## 🧪 Training Process

1. Load and normalize dataset
2. Flatten images
3. Build ANN model dynamically
4. Define:

   * Loss Function: CrossEntropyLoss
   * Optimizer (Adam/SGD)
5. Train model
6. Evaluate on validation/test data

---

## 📊 Results

* Achieved high accuracy (~85–90% depending on tuning)
* Optuna significantly improved performance compared to manual tuning

---

## 📈 Sample Output

* Training Loss vs Epochs
* Validation Accuracy
* Confusion Matrix

---

## 📦 Installation

```bash
git clone https://github.com/your-username/fashion-mnist-ann.git
cd fashion-mnist-ann
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python train.py
```

To run hyperparameter tuning:

```bash
python optuna_tuning.py
```

---

## 🧩 Project Structure

```
├── data/
├── models/
├── train.py
├── optuna_tuning.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## 💡 Key Learnings

* Understanding ANN architecture design
* Importance of hyperparameter tuning
* Practical use of Optuna
* Model optimization and evaluation

---

## 🔮 Future Improvements

* Add CNN for better accuracy
* Deploy model using Flask / FastAPI
* Build web interface for predictions
* Add real-time image classification

---

## 🙌 Author

**Debjit Das**
B.Tech CSE (AI & ML) Student
Passionate about AI, ML, and building impactful projects 🚀

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub and share with others!
