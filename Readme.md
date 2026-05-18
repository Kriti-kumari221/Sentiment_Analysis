# 🎬 CineRead – NLP Sentiment Analysis DevOps Project

## 📌 Project Overview

CineRead is an AI-powered NLP Sentiment Analysis web application that predicts whether a movie review is **Positive 😊** or **Negative 😡** using Machine Learning and Natural Language Processing techniques.

The project was built using:
- Flask REST API
- Scikit-learn NLP pipeline
- Docker containerization
- GitHub Actions CI/CD
- Frontend + Backend integration

This project demonstrates the complete lifecycle of an AI application including:
- Model training
- API development
- Frontend integration
- Dockerized deployment
- CI/CD automation

---

# 🚀 Features

✅ NLP-based sentiment prediction  
✅ Flask REST API  
✅ Interactive frontend UI  
✅ Dockerized application  
✅ Docker Compose setup  
✅ GitHub Actions CI/CD pipeline  
✅ Health check endpoint  
✅ Prediction confidence score  
✅ CORS-enabled API  
✅ DevOps-ready structure  

---

# 🛠️ Tech Stack

## Machine Learning & NLP
- Python
- Scikit-learn
- CountVectorizer
- Random Forest Classifier
- Pandas
- NumPy
- NLTK
- Gensim

## Backend
- Flask
- REST API

## Frontend
- HTML
- CSS
- JavaScript

## DevOps
- Docker
- Docker Compose
- GitHub Actions (CI/CD)

---

# 📂 Project Structure

```bash
SENTIMENT_ANALYSIS/
│
├── .github/
│   └── workflows/
│       └── main.yml
│
├── backend/
│   ├── templates/
│   │   └── index.html
│   │
│   ├── app.py
│   ├── cv.pkl
│   └── rf_model.pkl
│
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── .gitignore
├── .dockerignore
└── README.md
```

---

# 🧠 Machine Learning Workflow

The model was trained using:

1. Data Cleaning  
2. HTML Tag Removal  
3. Lowercase Conversion  
4. Stopword Removal  
5. Count Vectorization  
6. Random Forest Classification  
7. Model Serialization using Joblib  

Additional NLP experiments:
- TF-IDF
- Word2Vec
- Gaussian Naive Bayes

---

# ⚙️ API Endpoints

## Home Route

```http
GET /
```

Returns API status.

---

## Health Check

```http
GET /health
```

Returns application health status.

---

## Predict Sentiment

```http
POST /predict
```

### Request Body

```json
{
  "text": "This movie was absolutely amazing!"
}
```

### Response

```json
{
  "input": "This movie was absolutely amazing!",
  "sentiment": "Positive 😊",
  "score": 0.9821,
  "positive_probability": 0.9821,
  "negative_probability": 0.0179
}
```

---

# 🐳 Docker Setup

## Build and Run Using Docker Compose

```bash
docker compose up --build
```

Application runs at:

```bash
http://localhost:8000
```
Live:

```bash
https://sentiment-analysis-4r1o.onrender.com/
```

---

# 🔄 CI/CD Pipeline

GitHub Actions automatically:

- Installs dependencies
- Verifies Flask app
- Tests Docker build
- Validates project on every push

Workflow file:

```bash
.github/workflows/main.yml
```

---

# 📸 Screenshots

## Frontend UI
<img width="1003" height="955" alt="image" src="https://github.com/user-attachments/assets/0eab8755-e470-488c-bd47-fd54da92760a" />


## Docker Running
<img width="1577" height="917" alt="image" src="https://github.com/user-attachments/assets/78c30ace-668a-4c7a-9767-e20b1fe4ece6" />


## GitHub Actions CI/CD
<img width="1912" height="922" alt="image" src="https://github.com/user-attachments/assets/e7317a25-6103-4fa4-a6dd-3457a91823be" />


---

# 🌐 Future Improvements

- Add Swagger API Documentation
- Add User Authentication
- Add Database Integration
- Add Kubernetes Deployment
- Add Monitoring & Logging

---

# 👩‍💻 Author

Kriti Kumari

GitHub:
https://github.com/Kriti-kumari221

---

# ⭐ Project Highlights

✅ AI + DevOps Integrated Project  
✅ End-to-End ML Deployment  
✅ Containerized Flask Application  
✅ CI/CD Automation with GitHub Actions  
✅ Production-Ready Project Structure
