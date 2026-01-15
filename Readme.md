# DevOps CI Project

This project demonstrates a simple CI pipeline for a containerized Flask application using GitHub Actions.

## Tech Stack
- Python (Flask)
- Docker
- GitHub Actions

## CI Pipeline
- Installs dependencies
- Runs basic application check
- Builds Docker image

## How to Run Locally
```bash
docker build -t flask-devops-app .
docker run -p 5000:5000 flask-devops-app
