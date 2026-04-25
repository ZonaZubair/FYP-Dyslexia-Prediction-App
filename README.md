# 🧠 Dyslexia Prediction Web Application

## 📌 Overview
This project integrates *AI-based image classification** with an interactive web game designed to predict cognitive response patterns related to dyslexia.
It compares three approaches, **Deep Learning (CNN)**, Classical **Machine Learning**, and **Transfer Learning (VGG16)**, to classify images into three categories: **Normal**, **Correlated**, and **Reversal**.
The web interface provides an engaging, quiz-based experience for users while displaying real-time results and feedback.

---

## ⚙️ Key Features
- **AI Models Comparison:**  
  Evaluates CNN, ML ensemble, and Transfer Learning (VGG16) models based on accuracy, precision, recall, and F1-score.  
- **Interactive Frontend:**  
  Offers two quiz modes, *Alphabetical Quiz* and *Word Quiz*, with handwriting-based canvas input, dynamic question navigation, and real-time scoring.  
- **Real-time Evaluation:**  
  Predicts the user’s category (*Normal*, *Correlated*, or *Reversal*) based on performance.  
- **Graphical Feedback:**  
  Displays detailed results with percentage scores and class-wise ratio charts powered by Chart.js.  
- **User Feedback Form:**  
  Allows participants to share responses after completion.  

---

## 🧩 Tech Stack
- **Backend:** Python, Flask, TensorFlow/Keras, Scikit-learn, NumPy, Matplotlib  
- **Frontend:** HTML5, CSS3, Bootstrap, JavaScript, Chart.js  
- **Modeling Approaches:**  
  - CNN (Custom-built deep learning model)  
  - Ensemble ML (Random Forest + Gradient Boosting)  
  - Transfer Learning (VGG16)  

---

## 🚀 How to Run
1. **Clone the repository:**

   git clone (https://github.com/ZonaZubair/FYP-Dyslexia-Prediction-App.git)

---

## Install dependencies

pip install -r requirements.txt

---

## Run the app

python app.py

---

## 🖼️ UI Screenshots

**Home Page**

<img width="510" height="277" alt="UI 1" src="https://github.com/user-attachments/assets/2610809f-a17f-42c0-8541-a887a3c2ab6a" />

**Alphabetical Quiz with handwriting canvas input** 

<img width="425" height="275" alt="UI 2" src="https://github.com/user-attachments/assets/a508ad8b-d7a2-4ecd-b3bf-7ab36993c246" />

**Word Quiz Interface with handwriting canvas input**

<img width="458" height="296" alt="UI 3" src="https://github.com/user-attachments/assets/5b04fe2e-dc9b-4705-bb07-8cbef5ab734f" />

**Result Page with Score Summary and Prediction**

<img width="476" height="269" alt="UI 4" src="https://github.com/user-attachments/assets/cbd11fb0-7fe4-4f5e-a204-6dcc4f7dca0a" />

