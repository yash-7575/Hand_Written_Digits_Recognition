# Hand_Written_Digits_Recognition

A simple deep learning project built using **TensorFlow** and **Keras** to classify handwritten digits (0-9) from the popular **MNIST dataset**.

---

## 📌 Overview
This project demonstrates the use of a basic **feedforward neural network** for image classification. It aims to help beginners understand the core concepts of building, training, and evaluating a neural network.

---

## 🧠 Model Architecture
- **Input Layer**: 28x28 pixel images, flattened into a 784-length vector
- **Hidden Layer**: Dense layer with 128 neurons and ReLU activation
- **Output Layer**: Dense layer with 10 neurons (0–9 digits) and Softmax activation

---

## 📊 Dataset: MNIST
- **Training images**: 60,000
- **Test images**: 10,000
- **Image size**: 28x28 pixels
- **Grayscale**: Yes (1 channel)

---

## 🚀 How It Works
1. Loads the MNIST dataset using `mnist.load_data()`
2. Preprocesses the data (normalizes pixel values)
3. Builds a Sequential model
4. Trains the model using `.fit()`
5. Evaluates model accuracy using `.evaluate()`
6. Makes predictions on test data

---

## 📦 Requirements
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib (optional for visualizations)

Install dependencies:
```bash
pip install tensorflow numpy matplotlib
```

---

## 🧪 Run the Project
```bash
python digit_classifier.py
```

---

## 📷 Sample Output
- Displays predicted probabilities
- Compares predicted and actual digit
- Shows the digit image using matplotlib

---

## 💡 Learning Outcome
This project helps in:
- Understanding neural networks
- Getting hands-on with TensorFlow & Keras
- Gaining experience in image preprocessing and evaluation

---

## 🔖 License
This project is open-source and free to use for educational purposes.

---

Happy Learning! ✨

---

> Built with ❤️ using TensorFlow & Python

