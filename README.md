🧠 Image Classification and Dyslexia Detection Web Application
📌 Overview

This project integrates AI-based image classification with an interactive web game designed to predict cognitive response patterns related to dyslexia.
It compares three approaches — Deep Learning (CNN), Classical Machine Learning, and Transfer Learning (VGG16) — to classify images into three categories: Normal, Correlated, and Reversal.

The web interface provides an engaging, quiz-based experience for users while displaying real-time results and feedback.

⚙️ Key Features

AI Models Comparison:
Evaluates CNN, ML ensemble, and Transfer Learning (VGG16) models based on accuracy, precision, recall, and F1-score.

Interactive Frontend:
Offers two quiz modes — Alphabetical Quiz and Word Quiz — with random questions and dynamic scoring.

Real-time Evaluation:
Predicts the user’s category (Normal, Correlated, or Reversal) based on performance.

Graphical Feedback:
Displays detailed results with percentage scores and class-wise ratio charts.

User Feedback Form:
Allows participants to share responses after completion.

🧩 Tech Stack

Backend: Python, TensorFlow/Keras, Scikit-learn, NumPy, Matplotlib

Frontend: Streamlit (or Flask, if applicable), HTML/CSS, JavaScript

Modeling Approaches:

CNN (Custom-built deep learning model)

Ensemble ML (Random Forest + Gradient Boosting)

Transfer Learning (VGG16)

🚀 How to Run

Clone the repository:

git clone https://github.com/username/repository-name.git


Install dependencies:

pip install -r requirements.txt


Run the app:

streamlit run main.py


Access the web interface and start the quiz.
