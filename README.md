# Docker CI/CD Project 

## Description
This project demonstrates a simple Continuous Integration (CI) pipeline using GitHub Actions and Docker.

Whenever code is pushed to the repository, GitHub Actions automatically builds a Docker image using the provided Dockerfile. This helps ensure that the application is always tested and ready for deployment.

## Technologies Used
- Docker
- GitHub Actions
- Nginx (as a sample app)

## How It Works
1. Developer pushes code to GitHub
2. GitHub Actions workflow is triggered
3. The pipeline checks out the code
4. Docker image is built automatically

## How to Run Locally
```bash
docker build -t myapp .
docker run -p 8080:80 myapp
