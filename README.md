# 🧠 Handwritten Digit Recognition using Neural Networks

## 🔍 Overview
This project demonstrates the use of **Artificial Neural Networks (ANN)** to recognize handwritten digits (0–9) from the **MNIST dataset**.  
Using **TensorFlow** and **Keras**, the model learns visual patterns from pixel data and accurately classifies handwritten numbers, achieving excellent performance on unseen test images.

---

## 🎯 Business Problem
In the digital era, converting handwritten text into machine-readable data is crucial for applications like:
- Postal address reading
- Bank cheque verification
- Digitizing handwritten forms  

Manual entry is **time-consuming** and **error-prone**.  
This project automates handwritten digit recognition through a **robust deep learning model**, minimizing errors and improving efficiency.

---

## 🧩 Problem Statement
Build and evaluate a neural network that can classify handwritten digits (0–9) from grayscale images in the **MNIST dataset**, ensuring **high accuracy** and **generalization performance**.

---

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)** and visualize image samples  
- Preprocess and normalize pixel values for efficient training  
- Implement a **Feedforward Neural Network (FNN)** using Keras  
- Apply **Dropout** for regularization and prevent overfitting  
- Evaluate model performance using **accuracy, loss, and confusion matrix**  
- Save and reload the trained model for reuse  

---

## 📚 Dataset
**Dataset:** [MNIST Handwritten Digits (Keras built-in)](https://keras.io/api/datasets/mnist/)  
- **Training Samples:** 60,000  
- **Testing Samples:** 10,000  
- **Image Size:** 28×28 pixels (grayscale)  

---

## 🧠 Model Architecture
| Layer | Description |
|-------|--------------|
| Input Layer | 784 neurons (flattened 28×28 image) |
| Hidden Layer 1 | Dense(512, activation='relu') |
| Dropout Layer | 20% |
| Hidden Layer 2 | Dense(256, activation='relu') |
| Dropout Layer | 20% |
| Output Layer | Dense(10, activation='softmax') |

**Loss Function:** Categorical Crossentropy  
**Optimizer:** Adam  
**Metrics:** Accuracy  

---

## ⚙️ Technologies Used
- 🐍 Python  
- 🧠 TensorFlow / Keras  
- 📊 NumPy & Pandas  
- 📈 Matplotlib & Seaborn  
- ⚙️ Scikit-learn  

---

## 📈 Model Evaluation
- **Accuracy:** ~98% on test set  
- **Metrics:** Precision, Recall, F1-score  
- **Visualizations:** Accuracy & Loss Curves, Confusion Matrix  

---

## 📊 Results
 1. The model achieved **98% accuracy** on test data  
 2. Visualizations showed **consistent learning** and **minimal overfitting**  
 3. Correctly identified most handwritten digits with **high precision**  

---

## 🔮 Future Enhancements
1. Add **Convolutional Neural Network (CNN)** for better feature extraction  
2. Apply **Hyperparameter Tuning** for further optimization  
3. Deploy via **Streamlit or Flask** for real-time predictions  
4. Integrate **web-based canvas input** for live handwriting recognition  

---

## 👤 Author
**Om Patil**  
📧 *Data Science & Machine Learning Enthusiast*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
