An AI-powered PCOS Detection system that uses machine learning to analyze medical data and predict the likelihood of PCOS. Includes a user-friendly frontend and backend integration, providing quick and accurate predictions to assist in early diagnosis.

🌐 Live Demo: https://ovacare-detectpcos.onrender.com


Predicts PCOS based on clinical features using a trained machine learning model.
User-friendly web interface (React + Flask)
Backend API with FastAPI
Real-time prediction support
Random Forest Classifier with Standard Scaler for normalization
Seamless integration between frontend and backend
Fully deployed on Render for public access

Frontend:
HTML/CSS
JavaScript
React.js
Flask (serves static frontend)
Python

Backend:
FastAPI
Python (pandas, scikit-learn, pickle)
CORS Middleware for frontend-backend integration

Model:
RandomForestClassifier
Trained on balanced PCOS dataset with 80/20 train-test split

Deployment:
Render (for backend and hosting)
GitHub (source control)
