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

<table>
  <tr>
    <td align="center">
      <img src="screenshots/Home.png" width="400"/>
      <br/>
      <b>🏠 Home Page</b>
    </td>
    <td align="center">
      <img src="screenshots/Alphabetical_quiz.png" width="400"/>
      <br/>
      <b>🔤 Alphabetical Quiz with Handwriting Canvas Input</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="screenshots/Word_quiz.png" width="400"/>
      <br/>
      <b>📝 Word Quiz Interface with Handwriting Canvas Input</b>
    </td>
    <td align="center">
      <img src="screenshots/Result.png" width="400"/>
      <br/>
      <b>📊 Result Page with Score Summary and Prediction</b>
    </td>
  </tr>
</table>
