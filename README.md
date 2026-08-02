# MindSense AI

**AI-powered Student Mental Health Prediction Platform**

MindSense AI is an end-to-end machine learning web application that predicts a student's mental health score using academic, lifestyle, and social media behavior. The project demonstrates the complete workflow of deploying a machine learning model through a FastAPI REST API with a responsive web interface.

---

## Live Demo

**Application:** [Link](https://mental-health-score-predictor-2-hykc.onrender.com/)

---

## Features

* Real-time mental health score prediction
* Machine learning model served with FastAPI
* Responsive frontend built with HTML, CSS, and JavaScript
* REST API integration
* Production deployment on Render
* Clean and intuitive user interface

---

## Tech Stack

| Layer            | Technologies                        |
| ---------------- | ----------------------------------- |
| Frontend         | HTML5, CSS3, JavaScript             |
| Backend          | Python, FastAPI, Uvicorn            |
| Machine Learning | Scikit-learn, Pandas, NumPy, Joblib |
| Deployment       | Render                              |

---

## Project Structure

```text
MindSense-AI/
│
├── backend/
│   ├── main.py
│   ├── Mental_Health_Model.pkl
│   ├── requirements.txt
│   └── ...
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── assets/
│
├── README.md
└── .gitignore
```

---

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/MindSense-AI.git
cd MindSense-AI
```

### 2. Install backend dependencies

```bash
cd backend
pip install -r requirements.txt
```

### 3. Start the FastAPI server

```bash
uvicorn main:app --reload
```

The backend will be available at:

```
http://127.0.0.1:8000
```

### 4. Launch the frontend

Open the following file in your browser:

```
frontend/index.html
```

---

## API Endpoint

### POST `/predict`

Returns the predicted mental health score based on the submitted student data.

---

## Architecture

```text
                User
                  │
                  ▼
        HTML • CSS • JavaScript
                  │
             HTTP Request
                  │
                  ▼
             FastAPI Backend
                  │
                  ▼
     Scikit-learn Prediction Model
                  │
                  ▼
      Mental Health Score
                  │
                  ▼
          Interactive Dashboard
```

---

## Skills Demonstrated

* Machine Learning Deployment
* FastAPI REST API Development
* Frontend Development
* API Integration
* Responsive UI Design
* Production Deployment
* End-to-End ML Application Development

---

## Deployment

The application is deployed on **Render** and can be accessed through the live demo link.

---


