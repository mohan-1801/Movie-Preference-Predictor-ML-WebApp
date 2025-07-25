# 🎬 Movie Preference Predictor — ML Model + Web App Deployment

This project is an end-to-end machine learning solution that predicts a user's movie genre preference (Animation, Action, or Drama) based on their age, gender, and interest levels. The project includes a trained **Decision Tree Classifier** and a **Flask-based web application** for real-time prediction.

## 🚀 Demo Video
Watch the full walkthrough including model training and web deployment:  
👉 [LinkedIn Post](https://www.linkedin.com/posts/mohan-prashath-s-1801-_machinelearning-webdevelopment-flask-activity-7354374862280216577-Yul0?utm_source=share&utm_medium=member_desktop&rcm=ACoAAE6QuvcBRtJG7viNckmrOdQNSJjwkz5pxOY) 

## 🧠 Machine Learning Overview

- **Algorithm:** Decision Tree Classifier  
- **Dataset:** CSV file containing demographic and preference data  
- **Features Used:** Age, Gender, Interest in Animation, Action, Drama  
- **Target:** Predict overall movie preference

## 🌐 Web App Features

- Built using **Flask**, **HTML/CSS**, and **Bootstrap**
- Accepts user input for:
  - Age
  - Gender
  - Genre interests (Animation, Action, Drama)
- Displays predicted movie genre in real-time
- Packaged and deployed using `venv` and `pickle`
## 📁 Project Structure 
<pre lang="markdown">
  MovieInterestPrediction/
├── data/
│   └── gdk.pkl               # Trained ML model (Pickle file)
├── static/
│   └── style.css             # CSS styling for the web app
├── templates/
│   ├── index.html            # Input form page
│   └── result.html           # Prediction result page
├── venv/                     # Virtual environment (excluded in .gitignore)
├── README.md                 # Project documentation
└── app.py                    # Flask application

</pre>


## ⚙️ Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/mohan-1801/Movie-Preference-Predictor-ML-WebApp.git
cd movie-preference-predictor-ml-webapp
```
2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```
3. Run the Flask app:
```bash
python app.py

```

## 📚 Requirements

  - Python 3.7+
  - Flask
  - pandas
  - scikit-learn
  - numpy
  - pickle

  
