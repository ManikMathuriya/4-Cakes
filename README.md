📌 4-Cakes — HealthAI Guardian

An AI-powered health monitoring and early-warning system that predicts diabetes, stress, and hypertension using symptoms, activity logs, images, and ML models.

🚀 Overview

HealthAI Guardian is a smart wellness platform that uses ML models to provide:

Risk prediction for Diabetes

Risk estimation for Stress

Face-emotion analysis for mental wellness

Personalized recommendations

Real-time visualisation and dashboard

Designed for students, working professionals, and anyone looking to track and improve their health.

✨ Key Features
🩺 Disease Risk Prediction

Diabetes prediction model

Stress prediction model

Multi-input form with medical + lifestyle parameters

😊 Emotion Detection

Supports both image upload & webcam capture

Live analysis using a facial-emotion ML model

📊 Interactive Dashboard

Real-time prediction results

History charts (using Chart.js)

Clean UI designed for fast workflow

⚙️ Backend (Flask)

API endpoints for predictions

Model loading (joblib)

Camera image handling

CORS enabled

🎨 Frontend (HTML / CSS / JS)

Responsive layout

Easy-to-use prediction forms

Integrated webcam capture

Modern UI & charts

🗂️ Project Structure
4-Cakes/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── routes.py
│   │   └── utils/
│   ├── models/
│   │   ├── diabetes_model.joblib
│   │   ├── stress_model.joblib
│   │   └── emotion_model.joblib
│   ├── data/
│   └── requirements.txt
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md

🔧 Tech Stack
Frontend

HTML

CSS

JavaScript

Chart.js

Backend

Python Flask

NumPy

Pandas

Joblib

OpenCV (Optional, if using webcam)

🧠 Machine Learning Models

The following ML models are used:

Feature	Model	Format
Diabetes Prediction	Logistic Regression	.joblib
Stress Prediction	Random Forest	.joblib
Emotion Detection	CNN Model	.h5 or .joblib
🔌 Backend API Endpoints
Method	Endpoint	Description
POST	/predict/diabetes	Returns diabetes risk based on input form
POST	/predict/stress	Returns stress level prediction
POST	/predict/emotion	Accepts image (Base64) and returns detected emotion
🖥️ How to Run Locally
1. Backend
cd backend
pip install -r requirements.txt
python app/main.py


Backend runs at:
👉 http://127.0.0.1:5000

2. Frontend
cd frontend
python -m http.server 5500


Frontend runs at:
👉 http://127.0.0.1:5500

🎯 Use Case

HealthAI Guardian is designed to help users:

Predict early risks

Track daily symptoms

Stay aware of mental health

Receive recommendations

Stay proactive and reduce hospital visits

Perfect for hackathons, students, wellness apps, and innovation challenges.

👥 Team 4-Cakes

Manik Mathuriya (ML + Backend + Frontend)

Amaan Ditawat

Utkarsh Mishra

Jayvardhan singh Goud

💡 Future Enhancements

Add sleep quality detection

Integrate smartwatch / wearable data

Weekly health insights

Add diet recommendations AI

Full authentication system

🏆 Submission Ready

This README follows hackathon-standard guidelines — clean, detailed, and evaluator-friendly.

Want me to improve the README design using emojis, badges, or