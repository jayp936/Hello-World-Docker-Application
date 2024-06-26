 ## Hello-World-Docker-Application

This is a simple "Hello World" web application using Flask. The application includes a basic `app.py` file with Flask code to display "Hello World" on the home page. The project also includes a `requirements.txt` file for Python dependencies. The application is containerized using Docker and can be pushed to Docker Hub.

## Prerequisites

- Python 3.12 or later
- Docker
- Docker Hub account

## Project Structure
Hello World\
  ├── app.py\
  ├── requirements.txt\
  ├── Dockerfile

# Getting Started

## 1. Pulling and Running the Docker Image from Docker Hub:

`docker pull jayp936/hello-world-app`

## 2. Run the Docker Container:
`docker run -p 5000:5000 jayp936/hello-world-app`

## 3. Open browser:
Open your browser and navigate to `http://127.0.0.1:5000` to see "Hello, World!" from the Docker container pulled from Docker Hub.
