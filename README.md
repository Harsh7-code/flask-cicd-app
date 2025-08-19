# 🚀 Flask CI/CD Assignment

This repository demonstrates a complete CI/CD pipeline setup for a Flask application using **GitHub Actions** and **Docker**. The web app displays:

> **"Assignment from Harsh Khandelwal"**

---

## 🛠️ Tech Stack

- **Python**
- **Flask** – Lightweight web framework
- **Docker** – Containerization
- **GitHub Actions** – CI/CD pipeline

---

## 🧪 Features

- Flask server with a styled homepage
- Dockerized for easy deployment
- CI/CD pipeline using GitHub Actions
- `.dockerignore` to optimize Docker builds

---

## 📁 Project Structure

<pre>
flask-cicd-app/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── Dockerfile             # Docker build configuration
├── .dockerignore          # Exclude files from Docker build context
├── .github/
│   └── workflows/
│       └── main.yml       # GitHub Actions CI/CD pipeline
└── venv/      
</pre>


---

## 📸 Assignment Preview

### 🖥️ Final UI Output

<img width="1919" height="952" alt="screenshot" src="https://github.com/user-attachments/assets/c47e4e1f-9ae9-47cd-9489-92f308196607" />

---


## 🧪 Run Locally

```bash
# Clone the repository
git clone https://github.com/Harsh7-code/flask-cicd-app.git
cd flask-cicd-app

# Set up virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py


---
