# MusiRec – Music Recommendation System

MusiRec is a content-based music recommendation web application built using Flask and machine learning. It helps users discover new songs similar in style and feel to their favorites, based on audio features like energy and danceability.

# Live Demo

Try it out here:  
🔗 [https://musirec-music-recommendation-system.onrender.com](https://musirec-music-recommendation-system.onrender.com)

# How It Works

The system uses a pre-trained machine learning model to analyze songs and suggest recommendations based on similarity in key features. Once a user enters a song name, the model searches for its nearest neighbors and returns a curated list of similar tracks — complete with artist info and YouTube links.

# Features

-  Recommend similar songs based on track input
-  Live suggestions while typing
-  Uses danceability and energy scores for matching
-  Direct YouTube search link for each recommended song

# Technologies Used

- Frontend: HTML, CSS, Jinja (Flask templates)
- Backend: Python, Flask
- ML Model: Scikit-learn (KNN using `NearestNeighbors`)
- **Data Processing: pandas, NumPy, nltk
- Visualization: seaborn, matplotlib
- Deployment: Render

# Project Structure:
 Music-Recommendation-System/
├── app.py # Main Flask application
├── model/
│ ├── dataset.csv # Track metadata & features
│ ├── music_model.pkl # Trained ML model
│ └── scaler.pkl # Feature scaler
├── templates/
│ └── index.html # Main UI page
├── static/ # CSS & JS (if any)
├── requirements.txt
└── README.md

# How to Run Locally

git clone https://github.com/SR-2425/Music-Recommendation-System.git
cd Music-Recommendation-System
pip install -r requirements.txt
python app.py

