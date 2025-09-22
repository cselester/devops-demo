# 🚀 DevOps Demo Project

A simple **Flask web app** containerized with Docker and deployed via **GitHub Actions CI/CD pipeline**.

---

## 🔹 Features

- Simple Python Flask app (`app.py`)
- Dockerized using `Dockerfile`
- CI/CD pipeline with GitHub Actions
- (Optional) Push Docker image to Docker Hub

---

## 🛠 How to Run Locally

```bash
# Clone repo
git clone https://github.com/<your-username>/devops-demo.git
cd devops-demo

# Run app
python app.py

# Or with Docker
docker build -t devops-demo .
docker run -p 5000:5000 devops-demo
```
