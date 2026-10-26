# Python-Django-App-Containerization
A Django web application containerized with Docker. This project demonstrates Docker image creation, container execution, port mapping, version tagging, and publishing images to Docker Hub.

# Django Containerization with Docker

This project demonstrates how to containerize a Django web application using Docker and publish the resulting image to Docker Hub.

## Technologies
- Python
- Django
- Docker
- Docker Hub

## Features
- Django application setup
- Dockerfile configuration
- Build and run Docker images
- Port mapping to access the application locally
- Image versioning and tagging
- Publishing Docker images to Docker Hub

## Run locally with Docker

Pull the image:

```bash
docker pull salim2/containerization-app:v1.0.1
```

Run the container:

```bash
docker run --rm -p 8000:8000 salim2/containerization-app:v1.0.1
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## Purpose

This project is a hands-on learning exercise in Docker fundamentals and deploying a containerized Django application.

